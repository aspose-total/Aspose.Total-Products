---
title: Εξαγωγή SXC σε PPTX στο Android
description: Android API για μετατροπή SXC σε PPTX χωρίς χρήση του Microsoft Word
url: /el/android-java/conversion/sxc-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: SXC
outformat: PPTX
otherformats: POWERPOINT WORD DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το SXC στο PPTX στο Android μέσω Java" h2="Μετατρέψτε το SXC σε PPTX στις Εφαρμογές σας Android χωρίς να χρησιμοποιήσετε το Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) είναι ένα πακέτο ισχυρών API αυτοματισμού αρχείων. Χρησιμοποιώντας δύο από τα API του, μπορείτε να ενσωματώσετε τη δυνατότητα μετατροπής SXC σε PPTX στις εφαρμογές σας Android. Στο πρώτο βήμα, μπορείτε να εξαγάγετε SXC σε PDF χρησιμοποιώντας το [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Μετά από αυτό, χρησιμοποιώντας το [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), μπορείτε να μετατρέψετε το PDF σε PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API για εξαγωγή SXC σε PPTX" %}}
1. Ανοίξτε το αρχείο SXC χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Μετατρέψτε το SXC σε PDF και ορίστε το SaveFormat σε AUTO
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την κλάση [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. Αποθηκεύστε το έγγραφο σε μορφή PPTX χρησιμοποιώντας [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) μέθοδος
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total for Android via Java απευθείας από το [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και εγκαταστήστε το [Aspose.PDF for Android via Java](https://pptxs.aspose.com/pdf/androidjava/installation/) και το [Aspose.Cells for Android via Java](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) στις εφαρμογές σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// save SXC as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Καταργήστε τις προσαρμοσμένες ιδιότητες από το αρχείο SXC στο Android μέσω Java" %}}
Εκτός από τη μετατροπή εγγράφων, το [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) παρέχει επίσης πολλές άλλες δυνατότητες. Πριν από τη διαδικασία μετατροπής, μπορείτε να καταργήσετε προσαρμοσμένες ιδιότητες του εγγράφου SXC. Για να καταργήσετε προσαρμοσμένες ιδιότητες, καλέστε τη μέθοδο [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) και μεταβιβάστε το όνομα του την ιδιότητα του εγγράφου που πρέπει να αφαιρεθεί.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/sxc-to-powerpoint/" name="SXC Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/sxc-to-word/" name="SXC Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/sxc-to-pptx/" name="SXC Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/sxc-to-pptxx/" name="SXC Προς την PPTXX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}