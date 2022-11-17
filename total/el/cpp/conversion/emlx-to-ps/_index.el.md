---
title: Εξαγωγή EMLX σε PS μέσω C++
description: C++ API για μετατροπή EMLX σε PS χωρίς χρήση Microsoft Word ή Outlook

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: PS
otherformats: DOCM TEXT DOTM XPS DOT DOC TIFF ODT DOCX OTT PDF WORDML PNG MD FLATOPC GIF DOTX JPEG EPUB RTF EMF BMP SVG PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για εξαγωγή EMLX σε PS" h2="Μετατρέψτε το EMLX σε PS εντός της εφαρμογής C++ χωρίς να απαιτείται Microsoft Word ή Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Είστε προγραμματιστής C++ που θέλετε να προσθέσετε δυνατότητες μετατροπής emlx στις εφαρμογές σας; Χρησιμοποιώντας το [Aspose.Emlx για C++](https://products.aspose.com/emlx/cpp/) μπορείτε να μετατρέψετε τη μορφή αρχείου EMLX σε HTML. Μετά από αυτό, χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, μπορείτε να εξάγετε HTML σε PS. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για Μετατροπή EMLX σε PS" %}}
1. Ανοίξτε το αρχείο EMLX χρησιμοποιώντας την αναφορά κλάσης [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message)
2. Μετατρέψτε το EMLX σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Φορτώστε το HTML χρησιμοποιώντας την κλάση [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Αποθηκεύστε το έγγραφο σε μορφή PS χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) και ορίστε το Ps ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Ps as save format
doc->Save(u"convertedFile.Ps");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ανάλυση αρχείου EMLX μέσω C++" %}}
Όχι μόνο μπορείτε να μετατρέψετε το EMLX σας σε PS, αλλά μπορείτε να διαβάσετε, να χειριστείτε και να αναλύσετε το έγγραφο EMLX. Μπορείτε να λάβετε πληροφορίες θέματος, διεύθυνσης, σώματος, παραληπτών του μηνύματος ηλεκτρονικού ταχυδρομείου χρησιμοποιώντας την κλάση MapiMessage του API [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/). Για παράδειγμα, μπορείτε να ελέγξετε για ένα συγκεκριμένο emlx αποστολέα για τη μετατροπή χρησιμοποιώντας την ιδιότητα get_SenderEmlxAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.emlx");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlxAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API για περιορισμό της επεξεργασίας μορφής αρχείου PS" %}}
Μπορείτε επίσης να προσθέσετε λειτουργίες προστασίας εγγράφων στην εφαρμογή σας κατά την εξαγωγή του εγγράφου από το EMLX στο PS. Η προσθήκη προστασίας στο έγγραφό σας είναι μια απλή διαδικασία, καθώς το μόνο που χρειάζεται να κάνετε είναι να εφαρμόσετε τη μέθοδο προστασίας στο έγγραφό σας. Μπορείτε να ορίσετε τον τύπο προστασίας σε ReadOnly για να περιορίσετε τον χρήστη να επεξεργαστεί το έγγραφο.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Ps");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-docm/" name="EMLX Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-text/" name="EMLX Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-dotm/" name="EMLX Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-xps/" name="EMLX Προς την XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-dot/" name="EMLX Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-doc/" name="EMLX Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-tiff/" name="EMLX Προς την TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-odt/" name="EMLX Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-docx/" name="EMLX Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-ott/" name="EMLX Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-pdf/" name="EMLX Προς την PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-wordml/" name="EMLX Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-png/" name="EMLX Προς την PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-md/" name="EMLX Προς την MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-flatopc/" name="EMLX Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-gif/" name="EMLX Προς την GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-dotx/" name="EMLX Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-jpeg/" name="EMLX Προς την JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-epub/" name="EMLX Προς την EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-rtf/" name="EMLX Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-emf/" name="EMLX Προς την EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-ps/" name="EMLX Προς την PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-svg/" name="EMLX Προς την SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/emlx-to-pcl/" name="EMLX Προς την PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}