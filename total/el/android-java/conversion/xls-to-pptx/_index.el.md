---
title: Εξαγωγή XLS σε PPTX στο Android
description: Android API για μετατροπή XLS σε PPTX χωρίς χρήση του Microsoft Word
url: /el/android-java/conversion/xls-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: PPTX
otherformats: WORD POWERPOINT DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το XLS στο PPTX στο Android μέσω Java" h2="Μετατρέψτε το XLS σε PPTX στις Εφαρμογές σας Android χωρίς να χρησιμοποιήσετε το Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total για Android μέσω Java](https://products.aspose.com/total/android-java/) είναι ένα πακέτο ισχυρών API αυτοματισμού αρχείων. Χρησιμοποιώντας δύο από τα API του, μπορείτε να ενσωματώσετε τη δυνατότητα μετατροπής XLS σε PPTX στις εφαρμογές σας Android. Στο πρώτο βήμα, μπορείτε να εξαγάγετε XLS σε PDF χρησιμοποιώντας το [Aspose.Cells για Android μέσω Java](https://products.aspose.com/cells/android-java/). Μετά από αυτό, χρησιμοποιώντας το [Aspose.PDF για Android μέσω Java](https://products.aspose.com/pdf/android-java/), μπορείτε να μετατρέψετε το PDF σε PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API για εξαγωγή XLS σε PPTX" %}}
1. Ανοίξτε το αρχείο XLS χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Μετατρέψτε το XLS σε PDF και ορίστε το SaveFormat σε AUTO
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την κλάση [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. Αποθηκεύστε το έγγραφο σε μορφή PPTX χρησιμοποιώντας [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) μέθοδος
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total για Android μέσω Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε το [Aspose.PDF για Android μέσω Java](https://pptxs.aspose.com/pdf/androidjava/installation/) και το [Aspose.Cells για Android μέσω Java](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) στις εφαρμογές σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Καταργήστε τις προσαρμοσμένες ιδιότητες από το αρχείο XLS στο Android μέσω Java" %}}
Εκτός από τη μετατροπή εγγράφων, το [Aspose.Cells για Android μέσω Java](https://products.aspose.com/cells/android-java/) παρέχει επίσης πολλές άλλες δυνατότητες. Πριν από τη διαδικασία μετατροπής, μπορείτε να καταργήσετε προσαρμοσμένες ιδιότητες του εγγράφου XLS. Για να καταργήσετε προσαρμοσμένες ιδιότητες, καλέστε τη μέθοδο [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) και μεταβιβάστε το όνομα του την ιδιότητα του εγγράφου που πρέπει να αφαιρεθεί.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xls-to-word/" name="XLS Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xls-to-powerpoint/" name="XLS Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xls-to-pptx/" name="XLS Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/xls-to-pptxx/" name="XLS Προς την PPTXX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}