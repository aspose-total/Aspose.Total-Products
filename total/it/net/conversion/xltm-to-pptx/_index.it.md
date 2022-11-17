---
title: Converti XLTM in PPTX con .NET 
description: Converti XLTM in PPTX su piattaforme .NET Framework, .NET Core, Mono o Xamarin

family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: DOCX POWERPOINT WORD DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converti XLTM in PPTX tramite C#" h2="Esporta Excel&reg; XLTM a PPTX su piattaforme .NET Framework, .NET Core, Mono o Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversione da XLTM a PPTX su .NET" %}}
1. Aprire il file XLTM utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
2. Converti XLTM in PDF e imposta SaveFormat su Auto
3. Caricare il file PDF convertito utilizzando la classe [Pptxument](https://apiference.aspose.com/pdf/net/aspose.pdf/pptxument)
4. Salva il pptxumento in formato PPTX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5) e imposta Pptx come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Codice .NET C# per la conversione da XLTM a PPTX" gistPath="" %}}
```cs
// load the XLTM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltm");
// save XLTM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/csv-to-word/" name="CSV Per WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/csv-to-powerpoint/" name="CSV Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/csv-to-pptx/" name="CSV Per PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/csv-to-docx/" name="CSV Per DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}