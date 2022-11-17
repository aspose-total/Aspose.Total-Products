---
title: Converti XLS in POWERPOINT con .NET 
description: Converti XLS in POWERPOINT su piattaforme .NET Framework, .NET Core, Mono o Xamarin

family: total
platformtag: net
feature: conversion
informat: XLS
outformat: PPTX
otherformats: PPTX WORD DOCX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converti XLS in POWERPOINT tramite C#" h2="Esporta Excel&reg; XLS a POWERPOINT su piattaforme .NET Framework, .NET Core, Mono o Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversione da XLS a POWERPOINT su .NET" %}}
1. Aprire il file XLS utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
2. Converti XLS in PDF e imposta SaveFormat su Auto
3. Caricare il file PDF convertito utilizzando la classe [Powerpointument](https://apiference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. Salva il powerpointumento in formato POWERPOINT utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) e imposta Powerpoint come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Codice .NET C# per la conversione da XLS a POWERPOINT" gistPath="" %}}
```cs
// load the XLS file using Workbook class
var book = new Aspose.Cells.Workbook("input.xls");
// save XLS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
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