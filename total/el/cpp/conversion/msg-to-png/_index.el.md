---
title: Εξαγωγή MSG σε PNG μέσω C++
description: C++ API για μετατροπή MSG σε PNG χωρίς χρήση Microsoft Word ή Outlook

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: PNG
otherformats: DOTX RTF DOCX DOC TEXT DOTM FLATOPC DOT DOCM TIFF GIF XPS EMF WORDML PS EPUB ODT SVG PDF PCL MD OTT BMP JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για εξαγωγή MSG σε PNG" h2="Μετατρέψτε το MSG σε PNG εντός της εφαρμογής C++ χωρίς να απαιτείται Microsoft Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Είστε προγραμματιστής C++ που θέλετε να προσθέσετε δυνατότητες μετατροπής msg στις εφαρμογές σας; Χρησιμοποιώντας το [Aspose.Msg για C++](https://products.aspose.com/msg/cpp/) μπορείτε να μετατρέψετε τη μορφή αρχείου MSG σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, μπορείτε να εξάγετε HTML σε PNG. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για Μετατροπή MSG σε PNG" %}}
1. Ανοίξτε το αρχείο MSG χρησιμοποιώντας την αναφορά κλάσης [MailMessage](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message)
2. Μετατρέψτε το MSG σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Αποθηκεύστε το έγγραφο σε μορφή PNG χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) και ορίστε το Png ως SaveFormat
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
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου MSG μέσω C++" %}}
Όχι μόνο μπορείτε να μετατρέψετε το MSG σας σε PNG, αλλά μπορείτε να διαβάσετε, να χειριστείτε και να αναλύσετε το έγγραφο MSG. Μπορείτε να λάβετε πληροφορίες θέματος, διεύθυνσης, σώματος, παραληπτών του μηνύματος ηλεκτρονικού ταχυδρομείου χρησιμοποιώντας την κλάση MapiMessage του API [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/). Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο msg αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα get_SenderMsgAddress().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API για περιορισμό της επεξεργασίας μορφής αρχείου PNG" %}}
Μπορείτε επίσης να προσθέσετε λειτουργίες προστασίας εγγράφων στην εφαρμογή σας κατά την εξαγωγή του εγγράφου από το MSG στο PNG. Η προσθήκη προστασίας στο έγγραφό σας είναι μια απλή διαδικασία, καθώς το μόνο που χρειάζεται να κάνετε είναι να εφαρμόσετε τη μέθοδο προστασίας στο έγγραφό σας. Μπορείτε να ορίσετε τον τύπο προστασίας σε ReadOnly για να περιορίσετε τον χρήστη να επεξεργαστεί το έγγραφο.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Png");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-dotx/" name="MSG Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-rtf/" name="MSG Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-docx/" name="MSG Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-doc/" name="MSG Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-text/" name="MSG Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-dotm/" name="MSG Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-flatopc/" name="MSG Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-dot/" name="MSG Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-docm/" name="MSG Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-tiff/" name="MSG Προς την TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-gif/" name="MSG Προς την GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-xps/" name="MSG Προς την XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-emf/" name="MSG Προς την EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-wordml/" name="MSG Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-ps/" name="MSG Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-epub/" name="MSG Προς την EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-odt/" name="MSG Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-svg/" name="MSG Προς την SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-pdf/" name="MSG Προς την PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-pcl/" name="MSG Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-md/" name="MSG Προς την MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-ott/" name="MSG Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-png/" name="MSG Προς την PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/msg-to-jpeg/" name="MSG Προς την JPEG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}