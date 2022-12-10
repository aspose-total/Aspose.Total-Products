---
title: Converter EXCEL para WORD com .NET 
description: Converter EXCEL para WORD em plataformas .NET Framework, .NET Core, Mono ou Xamarin

family: total
platformtag: net
feature: conversion
informat: CSV
outformat: DOC
otherformats: POWERPOINT DOCX PPTX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converter EXCEL para WORD via C#" h2="Exportar Excel&reg; EXCEL para WORD em plataformas .NET Framework, .NET Core, Mono ou Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversão de EXCEL para WORD em .NET" %}}
1. Abra o arquivo EXCEL usando a classe [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Converta EXCEL para PDF e defina SaveFormat para Auto
3. Carregue o arquivo PDF convertido usando a classe [Wordument](https://apireference.aspose.com/pdf/net/aspose.pdf/wordument)
4. Salve o wordumento no formato WORD usando o método [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.wordument/save/methods/5) e defina Word como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Código .NET C# para conversão de EXCEL para WORD" gistPath="" %}}
```cs
// load the EXCEL file using Workbook class
var book = new Aspose.Cells.Workbook("input.excel");
// save EXCEL as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Wordument class
var wordument = new Aspose.Pdf.Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.Save("output.word", SaveFormat.Word); 
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