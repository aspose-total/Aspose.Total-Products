---
title: Εξαγωγή OFT σε DOCX μέσω C++
description: C++ API για μετατροπή OFT σε DOCX χωρίς χρήση Microsoft Word ή Outlook

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: DOCX
otherformats: MD GIF PNG DOCM DOTM PCL PDF BMP EPUB EMF DOC TEXT WORDML SVG FLATOPC DOTX RTF PS OTT DOT JPEG TIFF ODT XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για εξαγωγή OFT σε DOCX" h2="Μετατρέψτε το OFT σε DOCX εντός της εφαρμογής C++ χωρίς να απαιτείται Microsoft Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Είστε προγραμματιστής C++ που θέλετε να προσθέσετε δυνατότητες μετατροπής oft στις εφαρμογές σας; Χρησιμοποιώντας το [Aspose.Oft για C++](https://products.aspose.com/oft/cpp/) μπορείτε να μετατρέψετε τη μορφή αρχείου OFT σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, μπορείτε να εξάγετε HTML σε DOCX. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για Μετατροπή OFT σε DOCX" %}}
1. Ανοίξτε το αρχείο OFT χρησιμοποιώντας την αναφορά κλάσης [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message)
2. Μετατρέψτε το OFT σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Αποθηκεύστε το έγγραφο σε μορφή DOCX χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) και ορίστε το Docx ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Docx as save format
doc->Save(u"convertedFile.Docx");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου OFT μέσω C++" %}}
Όχι μόνο μπορείτε να μετατρέψετε το OFT σας σε DOCX, αλλά μπορείτε να διαβάσετε, να χειριστείτε και να αναλύσετε το έγγραφο OFT. Μπορείτε να λάβετε πληροφορίες θέματος, διεύθυνσης, σώματος, παραληπτών του μηνύματος ηλεκτρονικού ταχυδρομείου χρησιμοποιώντας την κλάση MapiMessage του API [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/). Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο oft αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα get_SenderOftAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.oft");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderOftAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API για περιορισμό της επεξεργασίας μορφής αρχείου DOCX" %}}
Μπορείτε επίσης να προσθέσετε λειτουργίες προστασίας εγγράφων στην εφαρμογή σας κατά την εξαγωγή του εγγράφου από το OFT στο DOCX. Η προσθήκη προστασίας στο έγγραφό σας είναι μια απλή διαδικασία, καθώς το μόνο που χρειάζεται να κάνετε είναι να εφαρμόσετε τη μέθοδο προστασίας στο έγγραφό σας. Μπορείτε να ορίσετε τον τύπο προστασίας σε ReadOnly για να περιορίσετε τον χρήστη να επεξεργαστεί το έγγραφο.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Docx");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-md/" name="OFT Προς την MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-gif/" name="OFT Προς την GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-png/" name="OFT Προς την PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-docm/" name="OFT Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-dotm/" name="OFT Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-pcl/" name="OFT Προς την PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-pdf/" name="OFT Προς την PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-docx/" name="OFT Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-epub/" name="OFT Προς την EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-emf/" name="OFT Προς την EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-doc/" name="OFT Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-text/" name="OFT Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-wordml/" name="OFT Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-svg/" name="OFT Προς την SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-flatopc/" name="OFT Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-dotx/" name="OFT Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-rtf/" name="OFT Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-ps/" name="OFT Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-ott/" name="OFT Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-dot/" name="OFT Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-jpeg/" name="OFT Προς την JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-tiff/" name="OFT Προς την TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-odt/" name="OFT Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/oft-to-xps/" name="OFT Προς την XPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}