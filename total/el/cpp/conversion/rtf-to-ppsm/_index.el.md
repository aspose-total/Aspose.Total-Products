---
title: Μετατροπή RTF σε PPSM μέσω C++
description: Εξαγωγή RTF σε PPSM στις εφαρμογές σας C++ χωρίς χρήση του Microsoft Word του PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: PPSM
otherformats: ODP PPTX POT POWERPOINT PPSX PPTM POTX POTM PPS PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για μετατροπή RTF σε PPSM" h2="Εξαγωγή RTF σε PPSM εντός των εφαρμογών σας C++ χωρίς χρήση του Microsoft Word&reg; ή PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total for C++](https://products.aspose.com/total/cpp/) αποτελείται από ισχυρά API αυτοματισμού αρχείων που επιτρέπουν την αυτοματοποίηση της μετατροπής RTF σε PPSM ενώ χρησιμοποιούνται δύο από τα API του. Φορτώστε το RTF σας χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) και μετατρέψτε το σε HTML και, στη συνέχεια, φορτώστε το HTML μέσω χειρισμού του PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) για να δημιουργήσετε μια νέα παρουσίαση και να την αποθηκεύσετε ως PPSM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή RTF σε PPSM σε C++" %}}
1. Ανοίξτε το αρχείο RTF χρησιμοποιώντας την αναφορά κλάσης [Rtfument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument)
2. Μετατρέψτε το RTF σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_stdbasicostream_saveoptions)
3. Αρχικοποιήστε ένα νέο αντικείμενο [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Προσθέστε ένα AutoShape στη διαφάνειά σας και προσθέστε το AddTextFrame σε αυτό
5. Φορτώστε το περιεχόμενο HTML και γράψτε το στο αρχείο παρουσίασης
6. Αποθηκεύστε το έγγραφο σε μορφή PPSM χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) και ορίστε το Ppsm ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκαταστήστε από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load RTF file with an instance of Rtfument
Rtfument rtfument = new Rtfument("template.rtf");
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"sourceFile.rtf");
// save the rtfument in HTML file format
rtf->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Ppsm
pres->Save(output.ppsm, Aspose::Slides::Export::SaveFormat::Ppsm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Φόρτωση εγγράφου RTF που προστατεύεται με κωδικό πρόσβασης μέσω C++" %}}
Εκτός από τη μετατροπή εγγράφων, το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API επιτρέπει τόνους λειτουργιών χειρισμού εγγράφων για προγραμματιστές C++. Σε περίπτωση που η μορφή αρχείου RTF του Microsoft Word προστατεύεται με κωδικό πρόσβασης, μπορείτε να την ανοίξετε χρησιμοποιώντας το API. Για να φορτώσετε το κρυπτογραφημένο έγγραφο, μπορείτε να χρησιμοποιήσετε μια ειδική υπερφόρτωση κατασκευαστή, η οποία δέχεται ένα αντικείμενο [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Αυτό το αντικείμενο περιέχει την ιδιότητα Κωδικός πρόσβασης, η οποία καθορίζει τη συμβολοσειρά κωδικού πρόσβασης.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected rtfument, the password is passed to the rtfument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"rtfPassword");
// load the rtfument from the local file system by filename:
SharedPtr<Rtfument> rtf = MakeObject<Rtfument>(u"Encrypted.rtf", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Προσθήκη σχολίων στο έγγραφο PPSM μέσω C++" %}}
Κατά την αποθήκευση του RTF ως PPSM, μπορείτε επίσης να χρησιμοποιήσετε το [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) για να προσθέσετε επιπλέον δυνατότητες στο έγγραφο PPSM. Για παράδειγμα, μπορείτε να προσθέσετε σχόλια στην παρουσίασή σας. Το σχόλιο της διαφάνειας παρουσίασης σχετίζεται με έναν συγκεκριμένο συγγραφέα. Η κλάση Presentation περιέχει τη συλλογή των συγγραφέων στο ICommentAuthorCollection που είναι υπεύθυνοι για την προσθήκη σχολίων διαφάνειας. Για κάθε συγγραφέα, υπάρχει μια συλλογή σχολίων στο ICommentCollection.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Ppsm
pres->Save(output.ppsm, Aspose::Slides::Export::SaveFormat::Ppsm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/rtf-to-ppsm/" name="RTF Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/rtf-to-pptx/" name="RTF Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/rtf-to-pot/" name="RTF Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/rtf-to-powerpoint/" name="RTF Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/rtf-to-ppsx/" name="RTF Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/rtf-to-pptm/" name="RTF Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/rtf-to-potx/" name="RTF Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/rtf-to-potm/" name="RTF Προς την POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/rtf-to-pps/" name="RTF Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/rtf-to-ppt/" name="RTF Προς την PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}