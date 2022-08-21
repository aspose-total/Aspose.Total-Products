---
title: Μετατροπή XLSX σε POWERPOINT με C++
description: Μετατροπή XLSX σε POWERPOINT εντός εφαρμογών C++
url: /el/cpp/conversion/xlsx-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: PPTX DOCX DOC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή XLSX σε POWERPOINT μέσω C++" h2="Εξαγωγή Excel<sup>&reg;</sup> XLSX σε POWERPOINT σε πλήρως λειτουργικές εφαρμογές C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή XLSX σε POWERPOINT σε C++" %}}
1. Ανοίξτε το αρχείο XLSX χρησιμοποιώντας τη λειτουργία μέλους [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) του [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) αναφορά κλάσης
2. Μετατρέψτε το XLSX σε PDF και ορίστε το SaveFormat σε Pdf
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την αναφορά κλάσης [Powerpointument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument)
4. Αποθηκεύστε το έγγραφο σε μορφή POWERPOINT χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) και ορίστε το Powerpoint ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsx");
// save XLSX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xlsx-to-pptx/" name="XLSX Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xlsx-to-powerpointx/" name="XLSX Προς την POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xlsx-to-powerpoint/" name="XLSX Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xlsx-to-word/" name="XLSX Προς την WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}