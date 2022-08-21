---
title: Μετατροπή XLTM σε WORD με C++
description: Μετατροπή XLTM σε WORD εντός εφαρμογών C++
url: /el/cpp/conversion/xltm-to-word/
family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: DOC
otherformats: PPTX POWERPOINT DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Μετατροπή XLTM σε WORD μέσω C++" h2="Εξαγωγή Excel<sup>&reg;</sup> XLTM σε WORD σε πλήρως λειτουργικές εφαρμογές C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Μετατροπή XLTM σε WORD σε C++" %}}
1. Ανοίξτε το αρχείο XLTM χρησιμοποιώντας τη λειτουργία μέλους [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) του [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) αναφορά κλάσης
2. Μετατρέψτε το XLTM σε PDF και ορίστε το SaveFormat σε Pdf
3. Φορτώστε το αρχείο PDF που έχει μετατραπεί χρησιμοποιώντας την αναφορά κλάσης [Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)
4. Αποθηκεύστε το έγγραφο σε μορφή WORD χρησιμοποιώντας τη λειτουργία μέλους [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) και ορίστε το Word ως SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις μετατροπής" %}}
Εγκατάσταση από τη γραμμή εντολών ως ```nuget install Aspose.Total.Cpp``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Total.Cpp``.

Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα αρχεία DLL σε ένα αρχείο ZIP από το [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltm");
// save XLTM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xltm-to-pptx/" name="XLTM Προς την PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xltm-to-powerpoint/" name="XLTM Προς την POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xltm-to-wordx/" name="XLTM Προς την WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/el/cpp/conversion/xltm-to-word/" name="XLTM Προς την WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}