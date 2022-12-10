---
title: Konvertera XLT till WORD med .NET 
description: Konvertera XLT till WORD på .NET Framework, .NET Core, Mono eller Xamarin-plattformar

family: total
platformtag: net
feature: conversion
informat: XLT
outformat: DOC
otherformats: DOC DOCX POWERPOINT PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertera XLT till WORD via C#" h2="Exportera Excel&reg; XLT till WORD på .NET Framework, .NET Core, Mono eller Xamarin-plattformar">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLT till WORD-konvertering på .NET" %}}
1. Öppna XLT-filen med klassen [Arbetsbok](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Konvertera XLT till PDF och ställ in SaveFormat till Auto
3. Ladda den konverterade PDF-filen med klassen [Wordument](https://apireference.aspose.com/pdf/net/aspose.pdf/wordument)
4. Spara dokumentet i WORD-format med metoden [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.wordument/save/methods/5) och ställ in Word som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C#-kod för XLT till WORD-konvertering" gistPath="" %}}
```cs
// load the XLT file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlt");
// save XLT as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Wordument class
var wordument = new Aspose.Pdf.Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.Save("output.word", SaveFormat.Word); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/csv-to-word/" name="CSV Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/csv-to-powerpoint/" name="CSV Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/csv-to-pptx/" name="CSV Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/csv-to-docx/" name="CSV Till DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}