---
title: C++ API για Μετατροπή PPSM σε DOCM
description: Εξαγωγή PPSM σε DOCM στις εφαρμογές σας C++

family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: DOCM
otherformats: TEXT DOT DOTX ODT FLATOPC DOCX RTF DOTM WORD DOC OTT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για απόδοση PPSM σε DOCM" h2="Εξαγωγή PPSM σε DOCM σε εφαρμογές C++ χωρίς εξαρτήσεις Microsoft PowerPoint ή Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total for C++](https://products.aspose.com/total/cpp/) είναι ένα πλήρες πακέτο βιβλιοθηκών αυτοματισμού μορφής αρχείου C++. Χρησιμοποιώντας τις πλούσιες δυνατότητες των API που είναι διαθέσιμα στο πακέτο, μπορούμε εύκολα να μετατρέψουμε το PowerPoint PPSM σε Word DOCM. Για να πραγματοποιήσετε τη μετατροπή, μπορείτε πρώτα να χρησιμοποιήσετε το [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API για να μετατρέψετε το PPSM σε HTML. Στη συνέχεια, χρησιμοποιώντας το πλούσιο σε δυνατότητες API επεξεργασίας κειμένου [Aspose.Words for C++](https://products.aspose.com/words/cpp/) μπορείτε να μετατρέψετε το HTML σε DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για Μετατροπή PPSM σε DOCM" %}}
1. Φορτώστε το αρχείο PPSM χρησιμοποιώντας την αναφορά κλάσης [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Αποδώστε το PPSM σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) και ορίστε το Html ως SaveFormat
3. Φορτώστε το αρχείο HTML που έχει μετατραπεί χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument)
4. Αποθηκεύστε το έγγραφο σε μορφή DOCM χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> docm = System::MakeObject<Document>(u"htmlOutput.html");
// save docmument in DOCM format
docm->Save(u"output.docm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-text/" name="PPSM Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-dot/" name="PPSM Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-dotx/" name="PPSM Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-odt/" name="PPSM Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-flatopc/" name="PPSM Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-docmx/" name="PPSM Προς την DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-rtf/" name="PPSM Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-dotm/" name="PPSM Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-word/" name="PPSM Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-docm/" name="PPSM Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-ott/" name="PPSM Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ppsm-to-wordml/" name="PPSM Προς την WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}