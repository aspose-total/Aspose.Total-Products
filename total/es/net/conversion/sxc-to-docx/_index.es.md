---
title: Convierta SXC a DOCX con .NET 
description: Convierta SXC a DOCX en plataformas .NET Framework, .NET Core, Mono o Xamarin
url: /es/net/conversion/sxc-to-docx/
family: total
platformtag: net
feature: conversion
informat: SXC
outformat: DOCX
otherformats: WORD PPTX POWERPOINT DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convierta SXC a DOCX a través de C#" h2="Exportar Excel&reg; SXC a DOCX en plataformas .NET Framework, .NET Core, Mono o Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversión de SXC a DOCX en .NET" %}}
1. Abra el archivo SXC usando la clase [Libro de trabajo](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Convierta SXC a PDF y configure SaveFormat en Auto
3. Cargue el archivo PDF convertido usando la clase [Docxumento](https://apireference.aspose.com/pdf/net/aspose.pdf/docxument)
4. Guarde el docxumento en formato DOCX usando el método [Guardar](https://apireference.aspose.com/pdf/net/aspose.pdf.docxument/save/methods/5) y configure Docx como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Código .NET C# para conversión de SXC a DOCX" gistPath="" %}}
```cs
// load the SXC file using Workbook class
var book = new Aspose.Cells.Workbook("input.sxc");
// save SXC as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Docxument class
var docxument = new Aspose.Pdf.Docxument("pdfOutput.pdf");
// save docxument in DOCXX format
docxument.Save("output.docxx", SaveFormat.DocxX); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/csv-to-word/" name="CSV A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/csv-to-powerpoint/" name="CSV A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/csv-to-pptx/" name="CSV A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/csv-to-docx/" name="CSV A DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}