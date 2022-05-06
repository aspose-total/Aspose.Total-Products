---
title: Μετατροπή FODS σε POWERPOINT χρησιμοποιώντας Java
description: Java API για εξαγωγή FODS σε POWERPOINT με χρήση Excel ή Word
url_ignore: /el/java/conversion/fods-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: PPTX
otherformats: POWERPOINT WORD PPTX POWERPOINTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API για εξαγωγή FODS σε POWERPOINT" h2="On Premise Java API για εξαγωγή FODS σε POWERPOINT χωρίς να βασίζεστε στο Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Η απόδοση του FODS σε POWERPOINT είναι μια διαδικασία δύο βημάτων. Θα χρησιμοποιήσετε πρώτα το [Aspose.Cells for Java](https://products.aspose.com/cells/java) API για να μετατρέψετε το δεδομένο έγγραφο FODS σε PDF και, στη συνέχεια, χρησιμοποιώντας το [Aspose.Pdf για Java](https ://products.aspose.com/pdf/java) API, μπορείτε εύκολα να μετατρέψετε το έγγραφο PDF σας σε POWERPOINT. Και τα δύο API ανήκουν στη συλλογή των βιβλιοθηκών αυτοματισμού μορφών αρχείων [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Πώς να μετατρέψετε FODS σε POWERPOINT μέσω Java API" %}}
1. Ανοίξτε το αρχείο FODS χρησιμοποιώντας την τάξη [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Μετατρέψτε το FODS σε PDF και ορίστε το SaveFormat σε AUTO
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την κλάση [Powerpointument](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Αποθηκεύστε το έγγραφο σε μορφή POWERPOINT χρησιμοποιώντας [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions-) και ορίστε το Powerpoint ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Πρέπει να χρησιμοποιήσετε το Aspose.Total για Java απευθείας από ένα έργο που βασίζεται στο [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) και συμπεριλάβετε βιβλιοθήκες στο pom.xml σας.

Εναλλακτικά, μπορείτε να λάβετε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές μετατροπής" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/fods-to-powerpointx/" name="FODS Προς την POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/fods-to-pptx/" name="FODS Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/fods-to-powerpoint/" name="FODS Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/net/conversion/fods-to-word/" name="FODS Προς την WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}