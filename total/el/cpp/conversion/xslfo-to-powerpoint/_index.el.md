---
title: C++ API για μετατροπή XSLFO σε POWERPOINT
description: Μετατρέψτε το XSLFO σε POWERPOINT μέσω C++ χωρίς τη χρήση του Microsoft Word ή του Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPT
otherformats: SWF POT PPT POTM PPTM PPS PPSM ODP POTX XAML PPSX OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το XSLFO σε POWERPOINT εντός των εφαρμογών C++" h2="Μετατροπή XSLFO σε POWERPOINT εντός των εφαρμογών σας C++ χωρίς τη χρήση του Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Είστε προγραμματιστής C++ που θέλετε να προσθέσετε για να ενσωματώσετε τη δυνατότητα μετατροπής XSLFO σε POWERPOINT στις εφαρμογές σας C++; Μπορείτε να το κάνετε με δύο απλά βήματα. Μπορείτε να εξαγάγετε το XSLFO σε PPTX χρησιμοποιώντας το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Δεύτερον, χρησιμοποιώντας το [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), μπορείτε να μετατρέψετε το PPTX σε POWERPOINT. Και τα δύο API περιλαμβάνονται στο πακέτο [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για εξαγωγή XSLFO σε POWERPOINT" %}}
1. Ανοίξτε το αρχείο XSLFO χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Μετατρέψτε το XSLFO σε PPTX χρησιμοποιώντας τη συνάρτηση μεθόδου [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Φορτώστε το έγγραφο PPTX χρησιμοποιώντας την αναφορά κλάσης [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Αποθηκεύστε το έγγραφο σε μορφή POWERPOINT χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) και ορίστε το "Powerpoint" ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XSLFO file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xslfo");
// save XSLFO as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Αλλάξτε τον κωδικό πρόσβασης του εγγράφου XSLFO μέσω C++" %}}
Κατά τη διαδικασία απόδοσης του XSLFO σε POWERPOINT, μπορείτε να ανοίξετε ένα XSLFO που προστατεύεται με κωδικό πρόσβασης και επίσης να αλλάξετε τον κωδικό πρόσβασής του. Για να αλλάξετε τον κωδικό πρόσβασης ενός αρχείου XSLFO, πρέπει να γνωρίζετε τον κωδικό πρόσβασης κατόχου αυτού του εγγράφου. Μπορείτε να φορτώσετε ένα έγγραφο PDF που προστατεύεται με κωδικό πρόσβασης με το [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) καθορίζοντας τον κωδικό πρόσβασης κατόχου του και να χρησιμοποιήσετε τη μέθοδο ChangePasswords για να αλλάξετε τον κωδικό πρόσβασης.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XSLFO Document
auto doc = MakeObject<Document>(L"input.xslfo", L"owner");
// change password of XSLFO Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Προσθήκη εικόνων από τον Ιστό σε αρχείο POWERPOINT μέσω C++" %}}
Μετά τη μετατροπή του XSLFO σε POWERPOINT, μπορείτε επίσης να προσθέσετε εικόνες από τον ιστό στο έγγραφο εξόδου σας. Το [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) υποστηρίζει λειτουργίες με εικόνες σε αυτές τις δημοφιλείς μορφές: JPEG, PNG, BMP, GIF και άλλες. Μπορείτε να προσθέσετε μία ή περισσότερες εικόνες στον υπολογιστή σας σε μια διαφάνεια μιας παρουσίασης. Αυτό το δείγμα κώδικα στη C++ σάς δείχνει πώς να προσθέσετε μια εικόνα σε ένα αρχείο POWERPOINT
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POWERPOINT file
auto pres = System::MakeObject<Presentation>("output.powerpoint");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.powerpoint", SaveFormat::Ppt);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-swf/" name="XSLFO Προς την SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-pot/" name="XSLFO Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-ppt/" name="XSLFO Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-potm/" name="XSLFO Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-pptm/" name="XSLFO Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-pps/" name="XSLFO Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-ppsm/" name="XSLFO Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-powerpoint/" name="XSLFO Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-potx/" name="XSLFO Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-xaml/" name="XSLFO Προς την XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-ppsx/" name="XSLFO Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xslfo-to-otp/" name="XSLFO Προς την OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}