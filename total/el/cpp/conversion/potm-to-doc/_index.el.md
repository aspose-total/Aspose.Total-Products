---
title: C++ API για Μετατροπή POTM σε DOC
description: Εξαγωγή POTM σε DOC στις εφαρμογές σας C++

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: DOC
otherformats: DOTX TEXT FLATOPC WORD DOCM WORDML RTF DOCX OTT ODT DOT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για απόδοση POTM σε DOC" h2="Εξαγωγή POTM σε DOC σε εφαρμογές C++ χωρίς εξαρτήσεις Microsoft PowerPoint ή Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total for C++](https://products.aspose.com/total/cpp/) είναι ένα πλήρες πακέτο βιβλιοθηκών αυτοματισμού μορφής αρχείου C++. Χρησιμοποιώντας τις πλούσιες δυνατότητες των API που είναι διαθέσιμα στο πακέτο, μπορούμε εύκολα να μετατρέψουμε το PowerPoint POTM σε Word DOC. Για να πραγματοποιήσετε τη μετατροπή, μπορείτε πρώτα να χρησιμοποιήσετε το [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API για να μετατρέψετε το POTM σε HTML. Στη συνέχεια, χρησιμοποιώντας το πλούσιο σε δυνατότητες API επεξεργασίας κειμένου [Aspose.Words for C++](https://products.aspose.com/words/cpp/) μπορείτε να μετατρέψετε το HTML σε DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για Μετατροπή POTM σε DOC" %}}
1. Φορτώστε το αρχείο POTM χρησιμοποιώντας την αναφορά κλάσης [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Αποδώστε το POTM σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) και ορίστε το Html ως SaveFormat
3. Φορτώστε το αρχείο HTML που έχει μετατραπεί χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Αποθηκεύστε το έγγραφο σε μορφή DOC χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"htmlOutput.html");
// save document in DOC format
doc->Save(u"output.doc"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-dotx/" name="POTM Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-text/" name="POTM Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-flatopc/" name="POTM Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-word/" name="POTM Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-docm/" name="POTM Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-wordml/" name="POTM Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-rtf/" name="POTM Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-docx/" name="POTM Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-ott/" name="POTM Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-odt/" name="POTM Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-dot/" name="POTM Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/potm-to-dotm/" name="POTM Προς την DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}