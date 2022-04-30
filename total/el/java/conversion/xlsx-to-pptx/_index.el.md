---
title: Μετατροπή XLSX σε PPTX χρησιμοποιώντας Java
description: Java API για εξαγωγή XLSX σε PPTX με χρήση Excel ή Word
url: /el/java/conversion/xlsx-to-pptx/
family: total
platformtag: net
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: PPTX POWERPOINT PPTXX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API για εξαγωγή XLSX σε PPTX" h2="On Premise Java API για εξαγωγή XLSX σε PPTX χωρίς να βασίζεστε στο Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Η απόδοση του XLSX σε PPTX είναι μια διαδικασία δύο βημάτων. Θα χρησιμοποιήσετε πρώτα το [Aspose.Cells for Java](https://products.aspose.com/cells/java) API για να μετατρέψετε το δεδομένο έγγραφο XLSX σε PDF και, στη συνέχεια, χρησιμοποιώντας το [Aspose.Pdf για Java](https ://products.aspose.com/pdf/java) API, μπορείτε εύκολα να μετατρέψετε το έγγραφο PDF σας σε PPTX. Και τα δύο API ανήκουν στη συλλογή των βιβλιοθηκών αυτοματισμού μορφών αρχείων [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε XLSX σε PPTX μέσω Java API" %}}
1. Ανοίξτε το αρχείο XLSX χρησιμοποιώντας την τάξη [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Μετατρέψτε το XLSX σε PDF και ορίστε το SaveFormat σε AUTO
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την κλάση [Pptxument](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. Αποθηκεύστε το έγγραφο σε μορφή PPTX χρησιμοποιώντας [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions-) και ορίστε το Pptx ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Πρέπει να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xlsx-to-pptxx/" name="XLSX Προς την PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xlsx-to-pptx/" name="XLSX Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xlsx-to-powerpoint/" name="XLSX Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/xlsx-to-word/" name="XLSX Προς την WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}