---
title: Μετατροπή ODS σε PPTX με C++
description: Μετατροπή ODS σε PPTX εντός εφαρμογών C++

family: total
platformtag: cpp
feature: conversion
informat: ODS
outformat: PPTX
otherformats: POWERPOINT DOCX WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή ODS σε PPTX μέσω C++" h2="Εξαγωγή Excel<sup>&reg;</sup> ODS σε PPTX σε πλήρως λειτουργικές εφαρμογές C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή ODS σε PPTX σε C++" %}}
1. Ανοίξτε το αρχείο ODS χρησιμοποιώντας τη λειτουργία μέλους [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) του [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) αναφορά κλάσης
2. Μετατρέψτε το ODS σε PDF και ορίστε το SaveFormat σε Pdf
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την αναφορά κλάσης [Pptxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument)
4. Αποθηκεύστε το έγγραφο σε μορφή PPTX χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) και ορίστε το Pptx ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.ods");
// save ODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ods-to-powerpoint/" name="ODS Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ods-to-pptxx/" name="ODS Προς την PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ods-to-word/" name="ODS Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/ods-to-pptx/" name="ODS Προς την PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}