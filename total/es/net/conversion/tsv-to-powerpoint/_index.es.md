---
title: Convierta TSV a POWERPOINT con .NET 
description: Convierta TSV a POWERPOINT en plataformas .NET Framework, .NET Core, Mono o Xamarin

family: total
platformtag: net
feature: conversion
informat: TSV
outformat: PPTX
otherformats: PPTX WORD DOCX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convierta TSV a POWERPOINT a través de C#" h2="Exportar Excel&reg; TSV a POWERPOINT en plataformas .NET Framework, .NET Core, Mono o Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversión de TSV a POWERPOINT en .NET" %}}
1. Abra el archivo TSV usando la clase [Libro de trabajo](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Convierta TSV a PDF y configure SaveFormat en Auto
3. Cargue el archivo PDF convertido usando la clase [Powerpointumento](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. Guarde el powerpointumento en formato POWERPOINT usando el método [Guardar](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) y configure Powerpoint como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Código .NET C# para conversión de TSV a POWERPOINT" gistPath="" %}}
```cs
// load the TSV file using Workbook class
var book = new Aspose.Cells.Workbook("input.tsv");
// save TSV as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
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