---
title: Μετατροπή DOCX σε POTM μέσω C++
description: Εξαγωγή DOCX σε POTM στις εφαρμογές σας C++ χωρίς χρήση του Microsoft Word του PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: POTM
otherformats: PPTX PPT PPS PPSM POWERPOINT PPSX POTX PPTM POT ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για μετατροπή DOCX σε POTM" h2="Εξαγωγή DOCX σε POTM εντός των εφαρμογών σας C++ χωρίς χρήση του Microsoft Word&reg; ή PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total for C++](https://products.aspose.com/total/cpp/) αποτελείται από ισχυρά API αυτοματισμού αρχείων που επιτρέπουν την αυτοματοποίηση της μετατροπής DOCX σε POTM ενώ χρησιμοποιούνται δύο από τα API του. Φορτώστε το DOCX σας χρησιμοποιώντας το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) και μετατρέψτε το σε HTML και, στη συνέχεια, φορτώστε το HTML μέσω χειρισμού του PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) για να δημιουργήσετε μια νέα παρουσίαση και να την αποθηκεύσετε ως POTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή DOCX σε POTM σε C++" %}}
1. Ανοίξτε το αρχείο DOCX χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
2. Μετατρέψτε το DOCX σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions)
3. Αρχικοποιήστε ένα νέο αντικείμενο [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Προσθέστε ένα AutoShape στη διαφάνειά σας και προσθέστε το AddTextFrame σε αυτό
5. Φορτώστε το περιεχόμενο HTML και γράψτε το στο αρχείο παρουσίασης
6. Αποθηκεύστε το έγγραφο σε μορφή POTM χρησιμοποιώντας τη μέθοδο [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) και ορίστε το Potm ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκαταστήστε από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOCX file with an instance of Document
Document document = new Document("template.docx");
System::SharedPtr<Document> docx = System::MakeObject<Document>(u"sourceFile.docx");
// save the document in HTML file format
docx->Save(u"HtmlOutput.HTML");
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
// save presentation as Potm
pres->Save(output.potm, Aspose::Slides::Export::SaveFormat::Potm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Φόρτωση εγγράφου DOCX που προστατεύεται με κωδικό πρόσβασης μέσω C++" %}}
Εκτός από τη μετατροπή εγγράφων, το [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API επιτρέπει τόνους λειτουργιών χειρισμού εγγράφων για προγραμματιστές C++. Σε περίπτωση που η μορφή αρχείου DOCX του Microsoft Word προστατεύεται με κωδικό πρόσβασης, μπορείτε να την ανοίξετε χρησιμοποιώντας το API. Για να φορτώσετε το κρυπτογραφημένο έγγραφο, μπορείτε να χρησιμοποιήσετε μια ειδική υπερφόρτωση κατασκευαστή, η οποία δέχεται ένα αντικείμενο [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Αυτό το αντικείμενο περιέχει την ιδιότητα Κωδικός πρόσβασης, η οποία καθορίζει τη συμβολοσειρά κωδικού πρόσβασης.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docxPassword");
// load thDocumentnt from the local fiDocument by filename:
SharedPtr<Docxument> docx = MakeObject<Docxument>(u"Encrypted.docx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Προσθήκη σχολίων στο έγγραφο POTM μέσω C++" %}}
Κατά την αποθήκευση του DOCX ως POTM, μπορείτε επίσης να χρησιμοποιήσετε το [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) για να προσθέσετε επιπλέον δυνατότητες στο έγγραφο POTM. Για παράδειγμα, μπορείτε να προσθέσετε σχόλια στην παρουσίασή σας. Το σχόλιο της διαφάνειας παρουσίασης σχετίζεται με έναν συγκεκριμένο συγγραφέα. Η κλάση Presentation περιέχει τη συλλογή των συγγραφέων στο ICommentAuthorCollection που είναι υπεύθυνοι για την προσθήκη σχολίων διαφάνειας. Για κάθε συγγραφέα, υπάρχει μια συλλογή σχολίων στο ICommentCollection.
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
// save presentation as Potm
pres->Save(output.potm, Aspose::Slides::Export::SaveFormat::Potm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docx-to-pptx/" name="DOCX Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docx-to-ppt/" name="DOCX Προς την PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docx-to-pps/" name="DOCX Προς την PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docx-to-ppsm/" name="DOCX Προς την PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docx-to-powerpoint/" name="DOCX Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docx-to-ppsx/" name="DOCX Προς την PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docx-to-potx/" name="DOCX Προς την POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docx-to-pptm/" name="DOCX Προς την PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docx-to-pot/" name="DOCX Προς την POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/docx-to-potm/" name="DOCX Προς την POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}