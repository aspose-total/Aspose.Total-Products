---
title: Convierta XLSB a DOC con .NET o con el convertidor en línea gratuito
description: Convierta XLSB a DOC en plataformas .NET Framework, .NET Core, Mono o Xamarin o en línea. Pruebe el convertidor en línea gratuito de CSV a DOC rápidamente antes de integrar el código.

family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOC
otherformats: DOCX PPTX POWERPOINT WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Convierta XLSB a DOC a través de C# o aplicación en línea" h2="Exportar Excel&reg; XLSB a DOC en plataformas .NET Framework, .NET Core, Mono o Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversión de XLSB a DOC en .NET" %}}
1. Abra el archivo XLSB usando la clase [Libro de trabajo](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Convierta XLSB a PDF y configure SaveFormat en Auto
3. Cargue el archivo PDF convertido usando la clase [Documento](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. Guarde el documento en formato DOC usando el método [Guardar](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) y configure Doc como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Código .NET C# para conversión de XLSB a DOC" gistPath="" %}}
```cs
// load the XLSB file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsb");
// save XLSB as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Convertidor en línea gratuito para XLSB a DOC</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=xlsb" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}