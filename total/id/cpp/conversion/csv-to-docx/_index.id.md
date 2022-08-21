---
title: Konversi CSV ke DOCX dengan C++
description: Konversi CSV ke DOCX dalam aplikasi C++
url: /id/cpp/conversion/csv-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOCX
otherformats: POWERPOINT DOC PPTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi CSV ke DOCX melalui C++" h2="Ekspor Excel<sup>&reg;</sup> CSV ke DOCX dalam aplikasi C++ yang berfungsi penuh" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi CSV ke DOCX di C++" %}}
1. Buka file CSV menggunakan [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) fungsi anggota [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) referensi kelas
2. Konversi CSV ke PDF dan atur SaveFormat ke Pdf
3. Muat file PDF yang dikonversi menggunakan referensi kelas [Docxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument)
4. Simpan dokumen ke format DOCX menggunakan fungsi anggota [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument#a6383c010776212483f51cc41235924db) dan setel Docx sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
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
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/csv-to-powerpoint/" name="CSV Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/csv-to-docx/" name="CSV Ke DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/csv-to-pptx/" name="CSV Ke PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/csv-to-word/" name="CSV Ke WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}