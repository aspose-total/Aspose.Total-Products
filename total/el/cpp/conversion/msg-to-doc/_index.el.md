---
title: Εξαγωγή MSG σε DOC μέσω C++
description: C++ API για μετατροπή MSG σε DOC χωρίς χρήση Microsoft Word ή Outlook

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: DOC
otherformats: ODT DOCM BMP DOTX EMF DOCX TEXT SVG PS WORDML DOT PCL PNG DOTM PDF GIF OTT RTF FLATOPC XPS MD JPEG TIFF EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για εξαγωγή MSG σε DOC" h2="Μετατρέψτε το MSG σε DOC εντός της εφαρμογής C++ χωρίς να απαιτείται Microsoft Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Είστε προγραμματιστής C++ που θέλετε να προσθέσετε δυνατότητες μετατροπής msg στις εφαρμογές σας; Χρησιμοποιώντας το [Aspose.Msg για C++](https://products.aspose.com/msg/cpp/) μπορείτε να μετατρέψετε τη μορφή αρχείου MSG σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, μπορείτε να εξάγετε HTML σε DOC. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για Μετατροπή MSG σε DOC" %}}
1. Ανοίξτε το αρχείο MSG χρησιμοποιώντας την αναφορά κλάσης [MailMessage](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message)
2. Μετατρέψτε το MSG σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Αποθηκεύστε το έγγραφο σε μορφή DOC χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) και ορίστε το Doc ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the MSG file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save MSG as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Doc as save format
doc->Save(u"convertedFile.Doc");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου MSG μέσω C++" %}}
Όχι μόνο μπορείτε να μετατρέψετε το MSG σας σε DOC, αλλά μπορείτε να διαβάσετε, να χειριστείτε και να αναλύσετε το έγγραφο MSG. Μπορείτε να λάβετε πληροφορίες θέματος, διεύθυνσης, σώματος, παραληπτών του μηνύματος ηλεκτρονικού ταχυδρομείου χρησιμοποιώντας την κλάση MapiMessage του API [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/). Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο msg αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα get_SenderMsgAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderMsgAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API για περιορισμό της επεξεργασίας μορφής αρχείου DOC" %}}
Μπορείτε επίσης να προσθέσετε λειτουργίες προστασίας εγγράφων στην εφαρμογή σας κατά την εξαγωγή του εγγράφου από το MSG στο DOC. Η προσθήκη προστασίας στο έγγραφό σας είναι μια απλή διαδικασία, καθώς το μόνο που χρειάζεται να κάνετε είναι να εφαρμόσετε τη μέθοδο προστασίας στο έγγραφό σας. Μπορείτε να ορίσετε τον τύπο προστασίας σε ReadOnly για να περιορίσετε τον χρήστη να επεξεργαστεί το έγγραφο.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}