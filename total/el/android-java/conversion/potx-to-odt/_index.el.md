---
title: Εξαγωγή POTX σε ODT στο Andorid μέσω Java
description: Μετατρέψτε το POTX σε ODT σε εφαρμογές για κινητά χωρίς εγκατάσταση λογισμικού
url: /el/android-java/conversion/potx-to-odt/
family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: ODT
otherformats: DOT DOCX OTT WORDML RTF TEXT FLATOPC DOCM DOTM WORD DOC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το POTX στο ODT στο Andorid μέσω Java" h2="API μορφής αρχείου για μετατροπή POTX σε ODT εντός εφαρμογών Android χωρίς να εξαρτάται από το Microsoft PowerPoint ή το Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total για Android μέσω Java](https://products.aspose.com/total/android-java/) επιτρέπει τον χειρισμό μορφών αρχείων εντός εφαρμογών Android. Χρησιμοποιώντας τα API που παρέχονται στο πακέτο, μπορείτε να αυτοματοποιήσετε τη διαδικασία μετατροπής PowerPoint POTX σε Word ODT στις εφαρμογές σας.
Μπορείτε να μετατρέψετε το δεδομένο έγγραφό σας σε δύο βήματα. Μπορείτε να χρησιμοποιήσετε το [Aspose.Slides για Andorid μέσω Java](https://products.aspose.com/slides/android-java/) που είναι ένα PowerPoint API για εφαρμογές Android για απόδοση του POTX σε HTML. Στη συνέχεια, χρησιμοποιώντας το API επεξεργασίας εγγράφων [Aspose.Words για Android μέσω Java](https://products.aspose.com/words/android-java/) μπορείτε να μετατρέψετε το HTML σε ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Απόδοση POTX σε ODT στο Android" %}}
1. Ανοίξτε το αρχείο POTX χρησιμοποιώντας την τάξη [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Μετατρέψτε το POTX σε HTML χρησιμοποιώντας το [save](https://reference.aspose.com/slides/java/) και ορίστε το Html ως SaveFormat
3. Φορτώστε το αρχείο HTML που έχει μετατραπεί χρησιμοποιώντας την κλάση [Odtument](https://reference.aspose.com/words/java/com.aspose.words/Odtument)
4. Αποθηκεύστε το έγγραφο σε μορφή ODT χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,int)) και ορίστε το Odt ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Android μέσω Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε τα [Aspose.Slides για Android μέσω Java](https://odts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) και [Aspose.Words για Andorid μέσω Java](https://odts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) στο εφαρμογές.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("input.potx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Odtument
Odtument odtument = new Odtument("htmlOutput.html");
// save odtument in ODT format
odtument.save("output.odt",SaveFormat.Odt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-dot/" name="POTX Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-odtx/" name="POTX Προς την ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-ott/" name="POTX Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-wordml/" name="POTX Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-rtf/" name="POTX Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-text/" name="POTX Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-flatopc/" name="POTX Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-odtm/" name="POTX Προς την ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-dotm/" name="POTX Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-word/" name="POTX Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-odt/" name="POTX Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/potx-to-dotx/" name="POTX Προς την DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}