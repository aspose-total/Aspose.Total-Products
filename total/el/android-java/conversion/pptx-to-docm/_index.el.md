---
title: Εξαγωγή PPTX σε DOCM στο Andorid μέσω Java
description: Μετατρέψτε το PPTX σε DOCM σε εφαρμογές για κινητά χωρίς εγκατάσταση λογισμικού
url: /el/android-java/conversion/pptx-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: DOCM
otherformats: OTT DOTX FLATOPC DOC WORD DOT ODT DOTM RTF DOCX WORDML TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το PPTX στο DOCM στο Andorid μέσω Java" h2="API μορφής αρχείου για μετατροπή PPTX σε DOCM εντός εφαρμογών Android χωρίς να εξαρτάται από το Microsoft PowerPoint ή το Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total για Android μέσω Java](https://products.aspose.com/total/android-java/) επιτρέπει τον χειρισμό μορφών αρχείων εντός εφαρμογών Android. Χρησιμοποιώντας τα API που παρέχονται στο πακέτο, μπορείτε να αυτοματοποιήσετε τη διαδικασία μετατροπής PowerPoint PPTX σε Word DOCM στις εφαρμογές σας.
Μπορείτε να μετατρέψετε το δεδομένο έγγραφό σας σε δύο βήματα. Μπορείτε να χρησιμοποιήσετε το [Aspose.Slides για Andorid μέσω Java](https://products.aspose.com/slides/android-java/) που είναι ένα PowerPoint API για εφαρμογές Android για απόδοση του PPTX σε HTML. Στη συνέχεια, χρησιμοποιώντας το API επεξεργασίας εγγράφων [Aspose.Words για Android μέσω Java](https://products.aspose.com/words/android-java/) μπορείτε να μετατρέψετε το HTML σε DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Απόδοση PPTX σε DOCM στο Android" %}}
1. Ανοίξτε το αρχείο PPTX χρησιμοποιώντας την τάξη [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Μετατρέψτε το PPTX σε HTML χρησιμοποιώντας το [save](https://reference.aspose.com/slides/java/) και ορίστε το Html ως SaveFormat
3. Φορτώστε το αρχείο HTML που έχει μετατραπεί χρησιμοποιώντας την κλάση [Docmument](https://reference.aspose.com/words/java/com.aspose.words/Docmument)
4. Αποθηκεύστε το έγγραφο σε μορφή DOCM χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,int)) και ορίστε το Docm ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Android μέσω Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε τα [Aspose.Slides για Android μέσω Java](https://docms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) και [Aspose.Words για Andorid μέσω Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) στο εφαρμογές.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Docmument
Docmument docmument = new Docmument("htmlOutput.html");
// save docmument in DOCM format
docmument.save("output.docm",SaveFormat.Docmm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-ott/" name="PPTX Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-dotx/" name="PPTX Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-flatopc/" name="PPTX Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-docm/" name="PPTX Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-word/" name="PPTX Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-dot/" name="PPTX Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-odt/" name="PPTX Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-dotm/" name="PPTX Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-rtf/" name="PPTX Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-docmx/" name="PPTX Προς την DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-wordml/" name="PPTX Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-text/" name="PPTX Προς την TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}