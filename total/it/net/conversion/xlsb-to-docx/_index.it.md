---
title: Converti XLSB in DOCX con .NET 
description: Converti XLSB in DOCX su piattaforme .NET Framework, .NET Core, Mono o Xamarin
url: /it/net/conversion/xlsb-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOCX
otherformats: POWERPOINT WORD DOC PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converti XLSB in DOCX tramite C#" h2="Esporta Excel&reg; XLSB a DOCX su piattaforme .NET Framework, .NET Core, Mono o Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversione da XLSB a DOCX su .NET" %}}
1. Aprire il file XLSB utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
2. Converti XLSB in PDF e imposta SaveFormat su Auto
3. Caricare il file PDF convertito utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
4. Salva il documento in formato DOCX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) e imposta Docx come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Codice .NET C# per la conversione da XLSB a DOCX" gistPath="" %}}
```cs
// load the XLSB file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsb");
// save XLSB as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.Docx); 
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