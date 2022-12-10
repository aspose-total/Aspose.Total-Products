---
title: Konversi XLTX ke WORD dengan .NET 
description: Konversi XLTX ke WORD di .NET Framework, .NET Core, Mono atau Platform Xamarin

family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: DOC
otherformats: PPTX POWERPOINT DOC DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konversi XLTX ke WORD melalui C#" h2="Ekspor Excel&reg; XLTX ke WORD di .NET Framework, .NET Core, Mono atau Platform Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konversi XLTX ke WORD di .NET" %}}
1. Buka file XLTX menggunakan kelas [Buku Kerja](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Konversi XLTX ke PDF dan atur SaveFormat ke Auto
3. Muat file PDF yang dikonversi menggunakan kelas [Wordument](https://apireference.aspose.com/pdf/net/aspose.pdf/wordument)
4. Simpan dokumen ke format WORD menggunakan metode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.wordument/save/methods/5) dan setel Word sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code untuk Konversi XLTX ke WORD" gistPath="" %}}
```cs
// load the XLTX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltx");
// save XLTX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Wordument class
var wordument = new Aspose.Pdf.Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.Save("output.word", SaveFormat.Word); 
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