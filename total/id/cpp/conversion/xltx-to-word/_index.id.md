---
title: Konversi XLTX ke WORD dengan C++
description: Konversi XLTX ke WORD dalam aplikasi C++
url: /id/cpp/conversion/xltx-to-word/
family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: DOC
otherformats: DOCX POWERPOINT PPTX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi XLTX ke WORD melalui C++" h2="Ekspor Excel<sup>&reg;</sup> XLTX ke WORD dalam aplikasi C++ yang berfungsi penuh" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi XLTX ke WORD di C++" %}}
1. Buka file XLTX menggunakan [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) fungsi anggota [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) referensi kelas
2. Konversi XLTX ke PDF dan atur SaveFormat ke Pdf
3. Muat file PDF yang dikonversi menggunakan referensi kelas [Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)
4. Simpan dokumen ke format WORD menggunakan fungsi anggota [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) dan setel Word sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltx");
// save XLTX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/xltx-to-wordx/" name="XLTX Ke WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/xltx-to-powerpoint/" name="XLTX Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/xltx-to-pptx/" name="XLTX Ke PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/xltx-to-word/" name="XLTX Ke WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}