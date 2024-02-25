---
title: Εξαγωγή EML σε XPS μέσω C++
description: C++ API για μετατροπή EML σε XPS χωρίς χρήση Microsoft Word ή Outlook

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: XPS
otherformats: DOTM PNG TEXT PDF PCL EMF JPEG PS DOTX FLATOPC OTT EPUB DOT DOCM SVG ODT WORDML GIF RTF MD DOCX BMP TIFF DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για εξαγωγή EML σε XPS" h2="Μετατρέψτε το EML σε XPS εντός της εφαρμογής C++ χωρίς να απαιτείται Microsoft Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Είστε προγραμματιστής C++ που θέλετε να προσθέσετε δυνατότητες μετατροπής eml στις εφαρμογές σας; Χρησιμοποιώντας το [Aspose.Eml για C++](https://products.aspose.com/eml/cpp/) μπορείτε να μετατρέψετε τη μορφή αρχείου EML σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, μπορείτε να εξάγετε HTML σε XPS. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για Μετατροπή EML σε XPS" %}}
1. Ανοίξτε το αρχείο EML χρησιμοποιώντας την αναφορά κλάσης [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. Μετατρέψτε το EML σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Αποθηκεύστε το έγγραφο σε μορφή XPS χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) και ορίστε το Xps ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Xps as save format
doc->Save(u"convertedFile.Xps");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EML μέσω C++" %}}
Όχι μόνο μπορείτε να μετατρέψετε το EML σας σε XPS, αλλά μπορείτε να διαβάσετε, να χειριστείτε και να αναλύσετε το έγγραφο EML. Μπορείτε να λάβετε πληροφορίες θέματος, διεύθυνσης, σώματος, παραληπτών του μηνύματος ηλεκτρονικού ταχυδρομείου χρησιμοποιώντας την κλάση MapiMessage του API [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/). Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο eml αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα get_SenderEmlAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.eml");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API για περιορισμό της επεξεργασίας μορφής αρχείου XPS" %}}
Μπορείτε επίσης να προσθέσετε λειτουργίες προστασίας εγγράφων στην εφαρμογή σας κατά την εξαγωγή του εγγράφου από το EML στο XPS. Η προσθήκη προστασίας στο έγγραφό σας είναι μια απλή διαδικασία, καθώς το μόνο που χρειάζεται να κάνετε είναι να εφαρμόσετε τη μέθοδο προστασίας στο έγγραφό σας. Μπορείτε να ορίσετε τον τύπο προστασίας σε ReadOnly για να περιορίσετε τον χρήστη να επεξεργαστεί το έγγραφο.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Xps");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}