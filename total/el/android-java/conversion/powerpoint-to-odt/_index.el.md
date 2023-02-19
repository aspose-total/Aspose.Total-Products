---
title: Εξαγωγή POWERPOINT σε ODT στο Andorid μέσω Java
description: Μετατρέψτε το POWERPOINT σε ODT σε εφαρμογές για κινητά χωρίς εγκατάσταση λογισμικού

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: ODT
otherformats: DOT WORD FLATOPC DOCM DOCX DOC WORDML DOTX TEXT RTF DOTM OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το POWERPOINT στο ODT στο Andorid μέσω Java" h2="API μορφής αρχείου για μετατροπή POWERPOINT σε ODT εντός εφαρμογών Android χωρίς να εξαρτάται από το Microsoft PowerPoint ή το Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) επιτρέπει τον χειρισμό μορφών αρχείων εντός εφαρμογών Android. Χρησιμοποιώντας τα API που παρέχονται στο πακέτο, μπορείτε να αυτοματοποιήσετε τη διαδικασία μετατροπής PowerPoint POWERPOINT σε Word ODT στις εφαρμογές σας.
Μπορείτε να μετατρέψετε το δεδομένο έγγραφό σας σε δύο βήματα. Μπορείτε να χρησιμοποιήσετε το [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) που είναι ένα PowerPoint API για εφαρμογές Android για απόδοση του POWERPOINT σε HTML. Στη συνέχεια, χρησιμοποιώντας το API επεξεργασίας εγγράφων [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) μπορείτε να μετατρέψετε το HTML σε ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Απόδοση POWERPOINT σε ODT στο Android" %}}
1. Ανοίξτε το αρχείο POWERPOINT χρησιμοποιώντας την τάξη [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Μετατρέψτε το POWERPOINT σε HTML χρησιμοποιώντας το [save](https://reference.aspose.com/slides/java/) και ορίστε το Html ως SaveFormat
3. Φορτώστε το αρχείο HTML που έχει μετατραπεί χρησιμοποιώντας την κλάση [Odtument](https://reference.aspose.com/words/java/com.aspose.words/Odtument)
4. Αποθηκεύστε το έγγραφο σε μορφή ODT χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,int)) και ορίστε το Odt ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total for Android via Java απευθείας από το [Maven](https://releases.aspose.com/total/java/) και εγκαταστήστε τα [Aspose.Slides for Android via Java](https://odts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) και [Aspose.Words για Andorid μέσω Java](https://odts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) στο εφαρμογές.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Odtument
Odtument odtument = new Odtument("htmlOutput.html");
// save odtument in ODT format
odtument.save("output.odt",SaveFormat.Odt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Δωρεάν Online Μετατροπέας για POWERPOINT σε ODT</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=odt&from=pptx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-dot/" name="PPTX Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-word/" name="PPTX Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-flatopc/" name="PPTX Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-odtm/" name="PPTX Προς την ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-odtx/" name="PPTX Προς την ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-odt/" name="PPTX Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-wordml/" name="PPTX Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-dotx/" name="PPTX Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-text/" name="PPTX Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-rtf/" name="PPTX Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-dotm/" name="PPTX Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pptx-to-ott/" name="PPTX Προς την OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}