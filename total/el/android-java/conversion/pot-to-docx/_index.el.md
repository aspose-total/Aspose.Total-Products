---
title: Εξαγωγή POT σε DOCX στο Andorid μέσω Java
description: Μετατρέψτε το POT σε DOCX σε εφαρμογές για κινητά χωρίς εγκατάσταση λογισμικού
url: /el/android-java/conversion/pot-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: DOCX
otherformats: WORDML OTT DOT DOC DOTM DOTX ODT DOCM FLATOPC WORD RTF TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το POT στο DOCX στο Andorid μέσω Java" h2="API μορφής αρχείου για μετατροπή POT σε DOCX εντός εφαρμογών Android χωρίς να εξαρτάται από το Microsoft PowerPoint ή το Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total για Android μέσω Java](https://products.aspose.com/total/android-java/) επιτρέπει τον χειρισμό μορφών αρχείων εντός εφαρμογών Android. Χρησιμοποιώντας τα API που παρέχονται στο πακέτο, μπορείτε να αυτοματοποιήσετε τη διαδικασία μετατροπής PowerPoint POT σε Word DOCX στις εφαρμογές σας.
Μπορείτε να μετατρέψετε το δεδομένο έγγραφό σας σε δύο βήματα. Μπορείτε να χρησιμοποιήσετε το [Aspose.Slides για Andorid μέσω Java](https://products.aspose.com/slides/android-java/) που είναι ένα PowerPoint API για εφαρμογές Android για απόδοση του POT σε HTML. Στη συνέχεια, χρησιμοποιώντας το API επεξεργασίας εγγράφων [Aspose.Words για Android μέσω Java](https://products.aspose.com/words/android-java/) μπορείτε να μετατρέψετε το HTML σε DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Απόδοση POT σε DOCX στο Android" %}}
1. Ανοίξτε το αρχείο POT χρησιμοποιώντας την τάξη [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Μετατρέψτε το POT σε HTML χρησιμοποιώντας το [save](https://reference.aspose.com/slides/java/) και ορίστε το Html ως SaveFormat
3. Φορτώστε το αρχείο HTML που έχει μετατραπεί χρησιμοποιώντας την κλάση [Docxument](https://reference.aspose.com/words/java/com.aspose.words/Docxument)
4. Αποθηκεύστε το έγγραφο σε μορφή DOCX χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,int)) και ορίστε το Docx ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Android μέσω Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε τα [Aspose.Slides για Android μέσω Java](https://docxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) και [Aspose.Words για Andorid μέσω Java](https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) στο εφαρμογές.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("input.pot");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Docxument
Docxument docxument = new Docxument("htmlOutput.html");
// save docxument in DOCX format
docxument.save("output.docx",SaveFormat.Docxx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-wordml/" name="POT Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-ott/" name="POT Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-dot/" name="POT Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-docx/" name="POT Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-dotm/" name="POT Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-dotx/" name="POT Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-odt/" name="POT Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-docxm/" name="POT Προς την DOCXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-flatopc/" name="POT Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-word/" name="POT Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-rtf/" name="POT Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pot-to-text/" name="POT Προς την TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}