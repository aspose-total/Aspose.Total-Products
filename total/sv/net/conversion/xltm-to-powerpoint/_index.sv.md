---
title: Konvertera XLTM till POWERPOINT med .NET 
description: Konvertera XLTM till POWERPOINT på .NET Framework, .NET Core, Mono eller Xamarin-plattformar

family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: DOCX WORD PPTX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertera XLTM till POWERPOINT via C#" h2="Exportera Excel&reg; XLTM till POWERPOINT på .NET Framework, .NET Core, Mono eller Xamarin-plattformar">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLTM till POWERPOINT-konvertering på .NET" %}}
1. Öppna XLTM-filen med klassen [Arbetsbok](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Konvertera XLTM till PDF och ställ in SaveFormat till Auto
3. Ladda den konverterade PDF-filen med klassen [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. Spara dokumentet i POWERPOINT-format med metoden [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) och ställ in Powerpoint som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C#-kod för XLTM till POWERPOINT-konvertering" gistPath="" %}}
```cs
// load the XLTM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltm");
// save XLTM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
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