---
title: Μετατροπή XLT σε DOC με C++
description: Μετατροπή XLT σε DOC εντός εφαρμογών C++

family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: DOC
otherformats: DOCX WORD POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή XLT σε DOC μέσω C++" h2="Εξαγωγή Excel<sup>&reg;</sup> XLT σε DOC σε πλήρως λειτουργικές εφαρμογές C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή XLT σε DOC σε C++" %}}
1. Ανοίξτε το αρχείο XLT χρησιμοποιώντας τη λειτουργία μέλους [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) του [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) αναφορά κλάσης
2. Μετατρέψτε το XLT σε PDF και ορίστε το SaveFormat σε Pdf
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την αναφορά κλάσης [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
4. Αποθηκεύστε το έγγραφο σε μορφή DOC χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) και ορίστε το Doc ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLT file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlt");
// save XLT as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOC format
doc->Save(u"convertedFile.doc", SaveFormat::Doc);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xlt-to-docx/" name="XLT Προς την DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xlt-to-word/" name="XLT Προς την WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xlt-to-powerpoint/" name="XLT Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xlt-to-pptx/" name="XLT Προς την PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}