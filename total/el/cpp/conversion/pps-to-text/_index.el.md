---
title: C++ API για Μετατροπή PPS σε TEXT
description: Εξαγωγή PPS σε TEXT στις εφαρμογές σας C++

family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: TEXT
otherformats: RTF DOCM DOCX DOTX ODT FLATOPC WORDML DOC DOT WORD OTT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API για απόδοση PPS σε TEXT" h2="Εξαγωγή PPS σε TEXT σε εφαρμογές C++ χωρίς εξαρτήσεις Microsoft PowerPoint ή Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total for C++](https://products.aspose.com/total/cpp/) είναι ένα πλήρες πακέτο βιβλιοθηκών αυτοματισμού μορφής αρχείου C++. Χρησιμοποιώντας τις πλούσιες δυνατότητες των API που είναι διαθέσιμα στο πακέτο, μπορούμε εύκολα να μετατρέψουμε το PowerPoint PPS σε Word TEXT. Για να πραγματοποιήσετε τη μετατροπή, μπορείτε πρώτα να χρησιμοποιήσετε το [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API για να μετατρέψετε το PPS σε HTML. Στη συνέχεια, χρησιμοποιώντας το πλούσιο σε δυνατότητες API επεξεργασίας κειμένου [Aspose.Words for C++](https://products.aspose.com/words/cpp/) μπορείτε να μετατρέψετε το HTML σε TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API για Μετατροπή PPS σε TEXT" %}}
1. Φορτώστε το αρχείο PPS χρησιμοποιώντας την αναφορά κλάσης [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Αποδώστε το PPS σε HTML χρησιμοποιώντας τη συνάρτηση μέλους [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) και ορίστε το Html ως SaveFormat
3. Φορτώστε το αρχείο HTML που έχει μετατραπεί χρησιμοποιώντας την αναφορά κλάσης [Textument](https://reference.aspose.com/words/cpp/class/aspose.words.textument)
4. Αποθηκεύστε το έγγραφο σε μορφή TEXT χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/words/cpp/class/aspose.words.textument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPS file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pps");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Textument
System::SharedPtr<Textument> text = System::MakeObject<Textument>(u"htmlOutput.html");
// save textument in TEXT format
text->Save(u"output.text"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-rtf/" name="PPS Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-textm/" name="PPS Προς την TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-textx/" name="PPS Προς την TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-dotx/" name="PPS Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-odt/" name="PPS Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-flatopc/" name="PPS Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-wordml/" name="PPS Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-text/" name="PPS Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-dot/" name="PPS Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-word/" name="PPS Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-ott/" name="PPS Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/pps-to-dotm/" name="PPS Προς την DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}