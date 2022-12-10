---
title: Εξαγωγή FODS σε WORD στο Android
description: Android API για μετατροπή FODS σε WORD χωρίς χρήση του Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: DOC
otherformats: PPTX DOCX POWERPOINT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Αποδώστε το FODS στο WORD στο Android μέσω Java" h2="Μετατρέψτε το FODS σε WORD στις Εφαρμογές σας Android χωρίς να χρησιμοποιήσετε το Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Το [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) είναι ένα πακέτο ισχυρών API αυτοματισμού αρχείων. Χρησιμοποιώντας δύο από τα API του, μπορείτε να ενσωματώσετε τη δυνατότητα μετατροπής FODS σε WORD στις εφαρμογές σας Android. Στο πρώτο βήμα, μπορείτε να εξαγάγετε FODS σε PDF χρησιμοποιώντας το [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Μετά από αυτό, χρησιμοποιώντας το [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), μπορείτε να μετατρέψετε το PDF σε WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API για εξαγωγή FODS σε WORD" %}}
1. Ανοίξτε το αρχείο FODS χρησιμοποιώντας την τάξη [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Μετατρέψτε το FODS σε PDF και ορίστε το SaveFormat σε AUTO
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την κλάση [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. Αποθηκεύστε το έγγραφο σε μορφή WORD χρησιμοποιώντας [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) μέθοδος
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Μπορείτε εύκολα να χρησιμοποιήσετε το Aspose.Total for Android via Java απευθείας από το [Maven](https://releases.aspose.com/total/java/) και εγκαταστήστε το [Aspose.PDF for Android via Java](https://words.aspose.com/pdf/androidjava/installation/) και το [Aspose.Cells for Android via Java](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) στις εφαρμογές σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από τις [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Καταργήστε τις προσαρμοσμένες ιδιότητες από το αρχείο FODS στο Android μέσω Java" %}}
Εκτός από τη μετατροπή εγγράφων, το [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) παρέχει επίσης πολλές άλλες δυνατότητες. Πριν από τη διαδικασία μετατροπής, μπορείτε να καταργήσετε προσαρμοσμένες ιδιότητες του εγγράφου FODS. Για να καταργήσετε προσαρμοσμένες ιδιότητες, καλέστε τη μέθοδο [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) και μεταβιβάστε το όνομα του την ιδιότητα του εγγράφου που πρέπει να αφαιρεθεί.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/fods-to-pptx/" name="FODS Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/fods-to-wordx/" name="FODS Προς την WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/fods-to-powerpoint/" name="FODS Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/android-java/conversion/fods-to-word/" name="FODS Προς την WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}