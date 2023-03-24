---
title: Konwertuj CSV na DOC za pomocą .NET lub za pomocą bezpłatnego konwertera online
description: Konwertuj CSV na DOC na platformach .NET Framework, .NET Core, Mono lub Xamarin lub online. Szybko przetestuj darmowy konwerter online CSV na DOC przed integracją kodu.

family: total
platformtag: net
feature: conversion
informat: CSV
outformat: DOC
otherformats: WORD POWERPOINT PPTX DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konwertuj CSV na DOC za pomocą C# lub Aplikacja internetowa" h2="Eksportuj Excel&reg; CSV do DOC na platformach .NET Framework, .NET Core, Mono lub Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konwersja CSV do DOC w .NET" %}}
1. Otwórz plik CSV za pomocą klasy [Książka](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Konwertuj CSV na PDF i ustaw SaveFormat na Auto
3. Załaduj przekonwertowany plik PDF za pomocą klasy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. Zapisz dokument w formacie DOC za pomocą metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) i ustaw Doc jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Kod .NET C# do konwersji CSV na DOC" gistPath="" %}}

```cs
// load the CSV file using Workbook class
var book = new Aspose.Cells.Workbook("input.csv");
// save CSV as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Darmowy konwerter online dla CSV na DOC</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=csv" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}