---
title: Εξαγωγή PPS σε OTT στο Andorid μέσω Java
description: Μετατρέψτε το PPS σε OTT σε εφαρμογές για κινητά χωρίς εγκατάσταση λογισμικού
url: /el/android-java/conversion/pps-to-ott/
family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: OTT
otherformats: DOTM TEXT WORD FLATOPC WORDML RTF DOCX DOTX DOCM ODT DOT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το PPS στο OTT στο Andorid μέσω Java" h2="API μορφής αρχείου για μετατροπή PPS σε OTT εντός εφαρμογών Android χωρίς να εξαρτάται από το Microsoft PowerPoint ή το Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total για Android μέσω Java](https://products.aspose.com/total/android-java/) επιτρέπει τον χειρισμό μορφών αρχείων εντός εφαρμογών Android. Χρησιμοποιώντας τα API που παρέχονται στο πακέτο, μπορείτε να αυτοματοποιήσετε τη διαδικασία μετατροπής PowerPoint PPS σε Word OTT στις εφαρμογές σας.
Μπορείτε να μετατρέψετε το δεδομένο έγγραφό σας σε δύο βήματα. Μπορείτε να χρησιμοποιήσετε το [Aspose.Slides για Andorid μέσω Java](https://products.aspose.com/slides/android-java/) που είναι ένα PowerPoint API για εφαρμογές Android για απόδοση του PPS σε HTML. Στη συνέχεια, χρησιμοποιώντας το API επεξεργασίας εγγράφων [Aspose.Words για Android μέσω Java](https://products.aspose.com/words/android-java/) μπορείτε να μετατρέψετε το HTML σε OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Απόδοση PPS σε OTT στο Android" %}}
1. Ανοίξτε το αρχείο PPS χρησιμοποιώντας την τάξη [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Μετατρέψτε το PPS σε HTML χρησιμοποιώντας το [save](https://reference.aspose.com/slides/java/) και ορίστε το Html ως SaveFormat
3. Φορτώστε το αρχείο HTML που έχει μετατραπεί χρησιμοποιώντας την κλάση [Ottument](https://reference.aspose.com/words/java/com.aspose.words/Ottument)
4. Αποθηκεύστε το έγγραφο σε μορφή OTT χρησιμοποιώντας τη μέθοδο [save](https://reference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,int)) και ορίστε το Ott ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Android μέσω Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε τα [Aspose.Slides για Android μέσω Java](https://otts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) και [Aspose.Words για Andorid μέσω Java](https://otts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) στο εφαρμογές.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Ottument
Ottument ottument = new Ottument("htmlOutput.html");
// save ottument in OTT format
ottument.save("output.ott",SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-dotm/" name="PPS Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-text/" name="PPS Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-word/" name="PPS Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-flatopc/" name="PPS Προς την FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-wordml/" name="PPS Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-rtf/" name="PPS Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-ottx/" name="PPS Προς την OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-dotx/" name="PPS Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-ottm/" name="PPS Προς την OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-odt/" name="PPS Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-dot/" name="PPS Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-ott/" name="PPS Προς την OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}