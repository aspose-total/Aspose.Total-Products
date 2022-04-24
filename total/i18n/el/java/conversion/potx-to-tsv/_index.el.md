---
title: Μετατροπή POTX σε μορφή TSV μέσω Java
description: Μετατροπή POTX σε μορφή TSV μέσω Java χωρίς χρήση Microsoft Excel ή PowerPoint
url: /el/java/conversion/potx-to-tsv/
family: total
platformtag: net
feature: conversion
informat: POTXX
outformat: TSV
otherformats: MARKDOWN XLT TSV EXCEL MHTML XLSM FODS XLTM SXC XLSB XLS DIF XLTX XLAM XLSX ODS DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή POTX σε TSV μέσω Java" h2="Στο Premise Java API για εξαγωγή POTX σε TSV χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε το αρχείο POTX σε TSV μέσω του [Aspose.Total for Java](https://products.aspose.com/total/java/) σε δύο βήματα. Στο πρώτο βήμα μπορείτε να εξαγάγετε το POTX σε HTML χρησιμοποιώντας το [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Δεύτερον, χρησιμοποιώντας το [Aspose.Cells για Java](https://products.aspose.com/cells/java/), μπορείτε να μετατρέψετε HTML σε TSV.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το POTX σε TSV μέσω Java" %}}
1. Ανοίξτε το αρχείο POTX χρησιμοποιώντας την τάξη [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Μετατρέψτε το POTX σε HTML χρησιμοποιώντας το [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. μέθοδος ISaveOptions-).
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή TSV χρησιμοποιώντας [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) μέθοδο
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Για να μετατρέψετε το POTX σε TSV, μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/ έργο που βασίζεται σε aspose/aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να ανοίξετε το έγγραφο που προστατεύεται με κωδικό πρόσβασης. Εάν το έγγραφο POTX εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε TSV χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Το API σάς επιτρέπει να ανοίξετε το κρυπτογραφημένο έγγραφο περνώντας τον σωστό κωδικό πρόσβασης σε ένα αντικείμενο LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή Προστατευμένου POTX σε TSV μέσω Java" %}}
Κατά τη μετατροπή του αρχείου POTX σε TSV, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου TSV. Για να προσθέσετε ένα υδατογράφημα, δημιουργήστε ένα νέο βιβλίο εργασίας για να ανοίξετε το αρχείο HTML που έχει μετατραπεί. Επιλέξτε φύλλο εργασίας μέσω του ευρετηρίου του, δημιουργήστε ένα σχήμα και χρησιμοποιήστε τη λειτουργία addTextEffect, ορίστε χρώματα, διαφάνεια και άλλα. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας HTML ως TSV με το υδατογράφημα. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-fods/" name="POTX Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-xltm/" name="POTX Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-xlt/" name="POTX Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-xlam/" name="POTX Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-markdown/" name="POTX Προς την MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-excel/" name="POTX Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-mhtml/" name="POTX Προς την MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-xlsb/" name="POTX Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-ods/" name="POTX Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-sxc/" name="POTX Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-xls/" name="POTX Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-xltx/" name="POTX Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-xlsx/" name="POTX Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-tsv/" name="POTX Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-dif/" name="POTX Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-xlsm/" name="POTX Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-doc/" name="POTX Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-docx/" name="POTX Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-docm/" name="POTX Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-dot/" name="POTX Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-dotm/" name="POTX Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-dotx/" name="POTX Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-odt/" name="POTX Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-ott/" name="POTX Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-rtf/" name="POTX Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-word/" name="POTX Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-wordml/" name="POTX Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-text/" name="POTX Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/potx-to-flatopx/" name="POTX Προς την FLAΠρος τηνPX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}