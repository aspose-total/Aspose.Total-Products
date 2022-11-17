---
title: Konversi XLTX ke DOC dengan .NET 
description: Konversi XLTX ke DOC di .NET Framework, .NET Core, Mono atau Platform Xamarin

family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: DOC
otherformats: WORD DOCX POWERPOINT PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konversi XLTX ke DOC melalui C#" h2="Ekspor Excel&reg; XLTX ke DOC di .NET Framework, .NET Core, Mono atau Platform Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konversi XLTX ke DOC di .NET" %}}
1. Buka file XLTX menggunakan kelas [Buku Kerja](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Konversi XLTX ke PDF dan atur SaveFormat ke Auto
3. Muat file PDF yang dikonversi menggunakan kelas [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. Simpan dokumen ke format DOC menggunakan metode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) dan setel Doc sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code untuk Konversi XLTX ke DOC" gistPath="" %}}
```cs
// load the XLTX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltx");
// save XLTX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
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