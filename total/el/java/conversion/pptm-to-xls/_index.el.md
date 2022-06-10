---
title: Μετατροπή PPTM σε μορφή XLS μέσω Java
description: Μετατροπή PPTM σε μορφή XLS μέσω Java χωρίς χρήση Microsoft Excel ή PowerPoint
url_ignore: /el/java/conversion/pptm-to-xls/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: XLS
otherformats: MHTML FODS XLSX DIF XLTX EXCEL XLAM XLSB XLSM XLTM MARKDOWN TSV XLS SXC ODS XLT DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή PPTM σε XLS μέσω Java" h2="Στο Premise Java API για εξαγωγή PPTM σε XLS χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε το αρχείο PPTM σε XLS μέσω του [Aspose.Total for Java](https://products.aspose.com/total/java/) σε δύο βήματα. Στο πρώτο βήμα μπορείτε να εξαγάγετε το PPTM σε HTML χρησιμοποιώντας το [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Δεύτερον, χρησιμοποιώντας το [Aspose.Cells για Java](https://products.aspose.com/cells/java/), μπορείτε να μετατρέψετε HTML σε XLS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το PPTM σε XLS μέσω Java" %}}
1. Ανοίξτε το αρχείο PPTM χρησιμοποιώντας την τάξη [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Μετατρέψτε το PPTM σε HTML χρησιμοποιώντας το [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. μέθοδος ISaveOptions-).
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή XLS χρησιμοποιώντας [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) μέθοδο
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Για να μετατρέψετε το PPTM σε XLS, μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/ έργο που βασίζεται σε aspose/aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να ανοίξετε το έγγραφο που προστατεύεται με κωδικό πρόσβασης. Εάν το έγγραφο PPTM εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε XLS χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Το API σάς επιτρέπει να ανοίξετε το κρυπτογραφημένο έγγραφο περνώντας τον σωστό κωδικό πρόσβασης σε ένα αντικείμενο LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή Προστατευμένου PPTM σε XLS μέσω Java" %}}
Κατά τη μετατροπή του αρχείου PPTM σε XLS, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου XLS. Για να προσθέσετε ένα υδατογράφημα, δημιουργήστε ένα νέο βιβλίο εργασίας για να ανοίξετε το αρχείο HTML που έχει μετατραπεί. Επιλέξτε φύλλο εργασίας μέσω του ευρετηρίου του, δημιουργήστε ένα σχήμα και χρησιμοποιήστε τη λειτουργία addTextEffect, ορίστε χρώματα, διαφάνεια και άλλα. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας HTML ως XLS με το υδατογράφημα. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-fods/" name="PPTM Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xltm/" name="PPTM Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xlt/" name="PPTM Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xlam/" name="PPTM Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-markdown/" name="PPTM Προς την MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-excel/" name="PPTM Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-mhtml/" name="PPTM Προς την MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xlsb/" name="PPTM Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-ods/" name="PPTM Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-sxc/" name="PPTM Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xls/" name="PPTM Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xltx/" name="PPTM Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xlsx/" name="PPTM Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-tsv/" name="PPTM Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-dif/" name="PPTM Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-xlsm/" name="PPTM Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-doc/" name="PPTM Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-docx/" name="PPTM Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-docm/" name="PPTM Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-dot/" name="PPTM Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-dotm/" name="PPTM Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-dotx/" name="PPTM Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-odt/" name="PPTM Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-ott/" name="PPTM Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-rtf/" name="PPTM Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-word/" name="PPTM Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-wordml/" name="PPTM Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-text/" name="PPTM Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptm-to-flatopx/" name="PPTM Προς την FLAΠρος τηνPX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}