---
title: Konversi FODS ke PPTX dengan .NET 
description: Konversi FODS ke PPTX di .NET Framework, .NET Core, Mono atau Platform Xamarin
url: /id/net/conversion/fods-to-pptx/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: PPTX
otherformats: DOC DOCX WORD POWERPOINT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konversi FODS ke PPTX melalui C#" h2="Ekspor Excel&reg; FODS ke PPTX di .NET Framework, .NET Core, Mono atau Platform Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konversi FODS ke PPTX di .NET" %}}
1. Buka file FODS menggunakan kelas [Buku Kerja](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Konversi FODS ke PDF dan atur SaveFormat ke Auto
3. Muat file PDF yang dikonversi menggunakan kelas [Pptxument](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument)
4. Simpan dokumen ke format PPTX menggunakan metode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5) dan setel Pptx sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code untuk Konversi FODS ke PPTX" gistPath="" %}}
```cs
// load the FODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.fods");
// save FODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/csv-to-word/" name="CSV Ke WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/csv-to-powerpoint/" name="CSV Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/csv-to-pptx/" name="CSV Ke PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/csv-to-docx/" name="CSV Ke DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}