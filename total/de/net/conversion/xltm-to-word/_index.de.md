---
title: Konvertieren Sie XLTM in WORD mit .NET oder mit dem kostenlosen Online Converter
description: Konvertieren Sie XLTM in WORD auf .NET Framework-, .NET Core-, Mono- oder Xamarin-Plattformen oder online. Testen Sie schnell den kostenlosen CSV-zu-DOC-Online-Konverter, bevor Sie den Code integrieren.

family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: DOC
otherformats: POWERPOINT DOCX DOC PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Konvertieren Sie XLTM in WORD über C# oder Online-App" h2="Excel exportieren&reg; XLTM zu WORD auf .NET Framework-, .NET Core-, Mono- oder Xamarin-Plattformen">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLTM-zu-WORD-Konvertierung auf .NET" %}}
1. Öffnen Sie die XLTM-Datei mit der Klasse [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
2. Konvertieren Sie XLTM in PDF und setzen Sie SaveFormat auf Auto
3. Laden Sie die konvertierte PDF-Datei mit der Klasse [Wordument](https://apireference.aspose.com/pdf/net/aspose.pdf/wordument).
4. Speichern Sie das Dokument mit der Methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.wordument/save/methods/5) im WORD-Format und legen Sie Word als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C#-Code für die Konvertierung von XLTM in WORD" gistPath="" %}}
```cs
// load the XLTM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltm");
// save XLTM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Wordument class
var wordument = new Aspose.Pdf.Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.Save("output.word", SaveFormat.Word); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Kostenloser Online-Konverter für XLTM zu WORD</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xltm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}