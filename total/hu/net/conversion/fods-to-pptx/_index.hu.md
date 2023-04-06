---
title: A FODS konvertálása PPTX formátumba .NET segítségével vagy ingyenes online konverterrel
description: A FODS konvertálása PPTX formátumba .NET Framework, .NET Core, Mono vagy Xamarin platformokon vagy online. A kód integrálása előtt gyorsan tesztelje az ingyenes CSV-DOC online konvertert.

family: total
platformtag: net
feature: conversion
informat: FODS
outformat: PPTX
otherformats: DOC DOCX WORD POWERPOINT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="A FODS konvertálása PPTX formátumba C# segítségével vagy Online App" h2="Exportálás Excel&reg; FODS-ből PPTX-ba .NET Framework, .NET Core, Mono vagy Xamarin platformokon">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS-ből PPTX-ba konvertálás .NET-en" %}}
1. Nyissa meg a FODS-fájlt a [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály segítségével
2. Alakítsa át a FODS-t PDF-be, és állítsa a SaveFormat beállítást Automatikusra
3. Töltse be a konvertált PDF-fájlt a [Pptxument](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument) osztály használatával
4. Mentse a dokumentumot PPTX formátumba a [Mentés](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5) módszerrel, és állítsa be a dokumentumot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# kód a FODS-ből PPTX-ba való konvertáláshoz" gistPath="" %}}
```cs
// load the FODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.fods");
// save FODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Ingyenes online konverter FODS-hez PPTX-be</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=fods" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}