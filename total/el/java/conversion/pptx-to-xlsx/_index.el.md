---
title: Μετατροπή PPTX σε μορφή XLSX μέσω Java
description: Μετατροπή PPTX σε μορφή XLSX μέσω Java χωρίς χρήση Microsoft Excel ή PowerPoint
url_ignore: /el/java/conversion/pptx-to-xlsx/
family: total
platformtag: net
feature: conversion
informat: PPTX
outformat: XLSX
otherformats: XLS XLTM MARKDOWN SXC EXCEL XLAM TSV XLSB XLTX FODS DIF XLT ODS MHTML XLSM XLSX DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή PPTX σε XLSX μέσω Java" h2="Στο Premise Java API για εξαγωγή PPTX σε XLSX χωρίς χρήση Microsoft<sup>&reg;</sup> Excel ή PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Μπορείτε να μετατρέψετε το αρχείο PPTX σε XLSX μέσω του [Aspose.Total for Java](https://products.aspose.com/total/java/) σε δύο βήματα. Στο πρώτο βήμα μπορείτε να εξαγάγετε το PPTX σε HTML χρησιμοποιώντας το [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Δεύτερον, χρησιμοποιώντας το [Aspose.Cells για Java](https://products.aspose.com/cells/java/), μπορείτε να μετατρέψετε HTML σε XLSX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε το PPTX σε XLSX μέσω Java" %}}
1. Ανοίξτε το αρχείο PPTX χρησιμοποιώντας την τάξη [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Μετατρέψτε το PPTX σε HTML χρησιμοποιώντας το [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. μέθοδος ISaveOptions-).
3. Φορτώστε το έγγραφο HTML χρησιμοποιώντας την τάξη [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Αποθηκεύστε το έγγραφο σε μορφή XLSX χρησιμοποιώντας [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) μέθοδο
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Για να μετατρέψετε το PPTX σε XLSX, μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/ έργο που βασίζεται σε aspose/aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Απαιτήσεις μετατροπής" %}}
Χρησιμοποιώντας το API, μπορείτε επίσης να ανοίξετε το έγγραφο που προστατεύεται με κωδικό πρόσβασης. Εάν το έγγραφο PPTX εισόδου σας προστατεύεται με κωδικό πρόσβασης, δεν μπορείτε να το μετατρέψετε σε XLSX χωρίς να χρησιμοποιήσετε τον κωδικό πρόσβασης. Το API σάς επιτρέπει να ανοίξετε το κρυπτογραφημένο έγγραφο περνώντας τον σωστό κωδικό πρόσβασης σε ένα αντικείμενο LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Μετατροπή Προστατευμένου PPTX σε XLSX μέσω Java" %}}
Κατά τη μετατροπή του αρχείου PPTX σε XLSX, μπορείτε επίσης να προσθέσετε υδατογράφημα στη μορφή αρχείου εξόδου XLSX. Για να προσθέσετε ένα υδατογράφημα, δημιουργήστε ένα νέο βιβλίο εργασίας για να ανοίξετε το αρχείο HTML που έχει μετατραπεί. Επιλέξτε φύλλο εργασίας μέσω του ευρετηρίου του, δημιουργήστε ένα σχήμα και χρησιμοποιήστε τη λειτουργία addTextEffect, ορίστε χρώματα, διαφάνεια και άλλα. Μετά από αυτό, μπορείτε να αποθηκεύσετε το έγγραφό σας HTML ως XLSX με το υδατογράφημα. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-fods/" name="PPTX Προς την FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-xltm/" name="PPTX Προς την XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-xlt/" name="PPTX Προς την XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-xlam/" name="PPTX Προς την XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-markdown/" name="PPTX Προς την MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-excel/" name="PPTX Προς την EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-mhtml/" name="PPTX Προς την MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-xlsb/" name="PPTX Προς την XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-ods/" name="PPTX Προς την ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-sxc/" name="PPTX Προς την SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-xls/" name="PPTX Προς την XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-xltx/" name="PPTX Προς την XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-xlsx/" name="PPTX Προς την XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-tsv/" name="PPTX Προς την TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-dif/" name="PPTX Προς την DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-xlsm/" name="PPTX Προς την XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-doc/" name="PPTX Προς την DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-docx/" name="PPTX Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-docm/" name="PPTX Προς την DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-dot/" name="PPTX Προς την DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-dotm/" name="PPTX Προς την DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-dotx/" name="PPTX Προς την DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-odt/" name="PPTX Προς την ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-ott/" name="PPTX Προς την OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-rtf/" name="PPTX Προς την RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-word/" name="PPTX Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-wordml/" name="PPTX Προς την WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-text/" name="PPTX Προς την TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/pptx-to-flatopx/" name="PPTX Προς την FLAΠρος τηνPX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}