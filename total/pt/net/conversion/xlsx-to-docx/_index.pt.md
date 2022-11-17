---
title: Converter XLSX para DOCX com .NET 
description: Converter XLSX para DOCX em plataformas .NET Framework, .NET Core, Mono ou Xamarin

family: total
platformtag: net
feature: conversion
informat: XLSX
outformat: DOCX
otherformats: DOC PPTX POWERPOINT WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converter XLSX para DOCX via C#" h2="Exportar Excel&reg; XLSX para DOCX em plataformas .NET Framework, .NET Core, Mono ou Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversão de XLSX para DOCX em .NET" %}}
1. Abra o arquivo XLSX usando a classe [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Converta XLSX para PDF e defina SaveFormat para Auto
3. Carregue o arquivo PDF convertido usando a classe [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. Salve o documento no formato DOCX usando o método [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) e defina Docx como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Código .NET C# para conversão de XLSX para DOCX" gistPath="" %}}
```cs
// load the XLSX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsx");
// save XLSX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.Docx); 
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