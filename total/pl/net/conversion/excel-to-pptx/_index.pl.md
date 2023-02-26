---
title: Konwertuj EXCEL na PPTX za pomocą .NET lub za pomocą bezpłatnego konwertera online
description: Konwertuj EXCEL na PPTX na platformach .NET Framework, .NET Core, Mono lub Xamarin lub online. Przetestuj szybko darmowy konwerter online EXCEL na DOC przed integracją kodu.

family: total
platformtag: net
feature: conversion
informat: CSV
outformat: PPTX
otherformats: DOC WORD POWERPOINT DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konwertuj EXCEL na PPTX za pomocą C# lub online" h2="Eksportuj Excel&reg; EXCEL do PPTX na platformach .NET Framework, .NET Core, Mono lub Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konwersja EXCEL do PPTX w .NET" %}}
1. Otwórz plik EXCEL za pomocą klasy [Książka](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Konwertuj EXCEL na PDF i ustaw SaveFormat na Auto
3. Załaduj przekonwertowany plik PDF za pomocą klasy [Pptxument](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument)
4. Zapisz dokument w formacie PPTX za pomocą metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5) i ustaw Pptx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Kod .NET C# do konwersji EXCEL na PPTX" gistPath="" %}}
```cs
// load the EXCEL file using Workbook class
var book = new Aspose.Cells.Workbook("input.excel");
// save EXCEL as PDF
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

<h3>Darmowy konwerter online dla EXCEL na PPTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xlsx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/csv-to-word/" name="CSV Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/csv-to-powerpoint/" name="CSV Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/csv-to-pptx/" name="CSV Do PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/csv-to-docx/" name="CSV Do DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}