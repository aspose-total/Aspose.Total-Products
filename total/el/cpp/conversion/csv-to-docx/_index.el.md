---
title: Μετατροπή CSV σε DOCX με C++
description: Μετατροπή CSV σε DOCX εντός εφαρμογών C++
url: /el/cpp/conversion/csv-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOCX
otherformats: POWERPOINT DOC PPTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή CSV σε DOCX μέσω C++" h2="Εξαγωγή Excel<sup>&reg;</sup> CSV σε DOCX σε πλήρως λειτουργικές εφαρμογές C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή CSV σε DOCX σε C++" %}}
1. Ανοίξτε το αρχείο CSV χρησιμοποιώντας τη λειτουργία μέλους [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) του [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) αναφορά κλάσης
2. Μετατρέψτε το CSV σε PDF και ορίστε το SaveFormat σε Pdf
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την αναφορά κλάσης [Docxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument)
4. Αποθηκεύστε το έγγραφο σε μορφή DOCX χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument#a6383c010776212483f51cc41235924db) και ορίστε το Docx ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the CSV file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.csv");
// save CSV as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Docxument class reference
auto docx = MakeObject<Docxument>(u"pdfOutput.pdf");
// save docxument in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/csv-to-powerpoint/" name="CSV Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/csv-to-docx/" name="CSV Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/csv-to-pptx/" name="CSV Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/csv-to-word/" name="CSV Προς την WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}