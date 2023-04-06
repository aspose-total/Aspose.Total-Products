---
title: A XLSB konvertálása DOCX formátumba .NET segítségével vagy ingyenes online konverterrel
description: A XLSB konvertálása DOCX formátumba .NET Framework, .NET Core, Mono vagy Xamarin platformokon vagy online. A kód integrálása előtt gyorsan tesztelje az ingyenes CSV-DOC online konvertert.

family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOCX
otherformats: POWERPOINT WORD DOC PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="A XLSB konvertálása DOCX formátumba C# segítségével vagy Online App" h2="Exportálás Excel&reg; XLSB-ből DOCX-ba .NET Framework, .NET Core, Mono vagy Xamarin platformokon">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSB-ből DOCX-ba konvertálás .NET-en" %}}
1. Nyissa meg a XLSB-fájlt a [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) osztály segítségével
2. Alakítsa át a XLSB-t PDF-be, és állítsa a SaveFormat beállítást Automatikusra
3. Töltse be a konvertált PDF-fájlt a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
4. Mentse a dokumentumot DOCX formátumba a [Mentés](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel, és állítsa be a dokumentumot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# kód a XLSB-ből DOCX-ba való konvertáláshoz" gistPath="" %}}
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

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Ingyenes online konverter XLSB-hez DOCX-be</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsb" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}