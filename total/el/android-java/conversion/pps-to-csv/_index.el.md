---
title: Μετατροπή PPS σε CSV στο Android μέσω Java
description: Μετατροπή PPS σε CSV στο Android μέσω Java χωρίς χρήση Microsoft Excel ή PowerPoint
url: /el/android-java/conversion/pps-to-csv/
family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: CSV
otherformats: MHTML XLS ODS XLSM MARKDOWN XLTX TSV FODS XLSX DIF EXCEL XLTM SXC XLAM XLT XLSB DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή PPS σε CSV στο Android μέσω Java" h2="Εξαγωγή αρχείου PPS σε CSV σε εφαρμογές Android χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε εύκολα να μετατρέψετε το αρχείο PPS σε CSV στις εφαρμογές σας Android σε μια διαδικασία δύο βημάτων μέσω του [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). Στο πρώτο βήμα, μπορείτε να εξαγάγετε αρχείο PPS σε HTML χρησιμοποιώντας το [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/). Δεύτερον, χρησιμοποιώντας το [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), μπορείτε να μετατρέψετε HTML σε CSV. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το PPS σε CSV στο Android" %}}
1. Ανοίξτε το αρχείο PPS χρησιμοποιώντας την τάξη [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Μετατρέψτε το PPS σε HTML χρησιμοποιώντας το [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.μέθοδοςISaveOptions-).
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή CSV χρησιμοποιώντας το [save](https://reference.aspose.com/cells/java/com.aspose.cells/)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Για να μετατρέψετε το PPS σε CSV, μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total for Android via Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε βιβλιοθήκες στην εφαρμογή σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Μετατρέψτε το Protected PPS σε CSV στο Android μέσω Java" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να ανοίξετε το έγγραφο που προστατεύεται με κωδικό πρόσβασης. Εάν το έγγραφο PPS εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε CSV χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Το API σάς επιτρέπει να ανοίξετε το κρυπτογραφημένο έγγραφο περνώντας τον σωστό κωδικό πρόσβασης σε ένα αντικείμενο LoadOptions. Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να προσπαθήσετε να ανοίξετε ένα κρυπτογραφημένο έγγραφο με κωδικό πρόσβασης:
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Μετατρέψτε το αρχείο PPS σε CSV με το υδατογράφημα στο Android" %}}
Κατά τη μετατροπή του αρχείου PPS σε CSV, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου CSV. Για να προσθέσετε ένα υδατογράφημα, δημιουργήστε ένα νέο βιβλίο εργασίας για να ανοίξετε το αρχείο HTML που έχει μετατραπεί. Επιλέξτε φύλλο εργασίας μέσω του ευρετηρίου του, δημιουργήστε ένα σχήμα και χρησιμοποιήστε τη λειτουργία addTextEffect, ορίστε χρώματα, διαφάνεια και άλλα. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας HTML ως CSV με το υδατογράφημα.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-mhtml/" name="PPS Προς την MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-xls/" name="PPS Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-ods/" name="PPS Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-xlsm/" name="PPS Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-markdown/" name="PPS Προς την MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-xltx/" name="PPS Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-tsv/" name="PPS Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-fods/" name="PPS Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-xlsx/" name="PPS Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-dif/" name="PPS Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-excel/" name="PPS Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-xltm/" name="PPS Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-sxc/" name="PPS Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-xlam/" name="PPS Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-xlt/" name="PPS Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-xlsb/" name="PPS Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-doc/" name="PPS Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-docx/" name="PPS Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-docm/" name="PPS Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-dot/" name="PPS Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-dotm/" name="PPS Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-dotx/" name="PPS Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-odt/" name="PPS Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-ott/" name="PPS Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-rtf/" name="PPS Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-word/" name="PPS Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-wordml/" name="PPS Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-text/" name="PPS Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/pps-to-flatopx/" name="PPS Προς την FLATOPX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}