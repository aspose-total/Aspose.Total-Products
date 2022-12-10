---
title: Convierta FODS a DOC con .NET 
description: Convierta FODS a DOC en plataformas .NET Framework, .NET Core, Mono o Xamarin

family: total
platformtag: net
feature: conversion
informat: FODS
outformat: DOC
otherformats: PPTX POWERPOINT WORD DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convierta FODS a DOC a través de C#" h2="Exportar Excel&reg; FODS a DOC en plataformas .NET Framework, .NET Core, Mono o Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversión de FODS a DOC en .NET" %}}
1. Abra el archivo FODS usando la clase [Libro de trabajo](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Convierta FODS a PDF y configure SaveFormat en Auto
3. Cargue el archivo PDF convertido usando la clase [Documento](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. Guarde el documento en formato DOC usando el método [Guardar](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) y configure Doc como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Código .NET C# para conversión de FODS a DOC" gistPath="" %}}
```cs
// load the FODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.fods");
// save FODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
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