---
title: Converter FODS para DOCX com .NET 
description: Converter FODS para DOCX em plataformas .NET Framework, .NET Core, Mono ou Xamarin
url: /pt/net/conversion/fods-to-docx/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: DOCX
otherformats: DOC POWERPOINT PPTX WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converter FODS para DOCX via C#" h2="Exportar Excel&reg; FODS para DOCX em plataformas .NET Framework, .NET Core, Mono ou Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversão de FODS para DOCX em .NET" %}}
1. Abra o arquivo FODS usando a classe [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Converta FODS para PDF e defina SaveFormat para Auto
3. Carregue o arquivo PDF convertido usando a classe [Docxument](https://apireference.aspose.com/pdf/net/aspose.pdf/docxument)
4. Salve o docxumento no formato DOCX usando o método [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.docxument/save/methods/5) e defina Docx como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Código .NET C# para conversão de FODS para DOCX" gistPath="" %}}
```cs
// load the FODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.fods");
// save FODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Docxument class
var docxument = new Aspose.Pdf.Docxument("pdfOutput.pdf");
// save docxument in DOCXX format
docxument.Save("output.docxx", SaveFormat.DocxX); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/csv-to-word/" name="CSV Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/csv-to-powerpoint/" name="CSV Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/csv-to-pptx/" name="CSV Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/csv-to-docx/" name="CSV Para DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}