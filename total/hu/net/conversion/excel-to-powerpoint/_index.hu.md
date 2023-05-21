---
title: A EXCEL konvertálása POWERPOINT formátumba .NET segítségével 
description: A EXCEL konvertálása POWERPOINT formátumba .NET Framework, .NET Core, Mono vagy Xamarin platformokon

family: total
platformtag: net
feature: conversion
informat: EXCEL
outformat: POWERPOINT
otherformats: WORD PPTX DOCX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="A EXCEL konvertálása POWERPOINT formátumba C# segítségével" h2="Exportálás Excel&reg; EXCEL-ből POWERPOINT-ba .NET Framework, .NET Core, Mono vagy Xamarin platformokon">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="EXCEL-ből POWERPOINT-ba konvertálás .NET-en" %}}
1. Nyissa meg a EXCEL-fájlt a [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály segítségével
2. Alakítsa át a EXCEL-t PDF-be, és állítsa a SaveFormat beállítást Automatikusra
3. Töltse be a konvertált PDF-fájlt a [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument) osztály használatával
4. Mentse a dokumentumot POWERPOINT formátumba a [Mentés](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) módszerrel, és állítsa be a dokumentumot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# kód a EXCEL-ből POWERPOINT-ba való konvertáláshoz" gistPath="" %}}
```cs
// load the EXCEL file using Workbook class
var book = new Aspose.Cells.Workbook("input.excel");
// save EXCEL as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}