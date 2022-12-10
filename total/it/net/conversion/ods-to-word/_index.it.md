---
title: Converti ODS in WORD con .NET 
description: Converti ODS in WORD su piattaforme .NET Framework, .NET Core, Mono o Xamarin

family: total
platformtag: net
feature: conversion
informat: ODS
outformat: DOC
otherformats: DOCX POWERPOINT DOC PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converti ODS in WORD tramite C#" h2="Esporta Excel&reg; ODS a WORD su piattaforme .NET Framework, .NET Core, Mono o Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversione da ODS a WORD su .NET" %}}
1. Aprire il file ODS utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
2. Converti ODS in PDF e imposta SaveFormat su Auto
3. Caricare il file PDF convertito utilizzando la classe [Wordument](https://apiference.aspose.com/pdf/net/aspose.pdf/wordument)
4. Salva il wordumento in formato WORD utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.wordument/save/methods/5) e imposta Word come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Codice .NET C# per la conversione da ODS a WORD" gistPath="" %}}
```cs
// load the ODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.ods");
// save ODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Wordument class
var wordument = new Aspose.Pdf.Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.Save("output.word", SaveFormat.Word); 
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