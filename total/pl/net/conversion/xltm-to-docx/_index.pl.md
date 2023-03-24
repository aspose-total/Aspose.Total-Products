---
title: Konwertuj XLTM na DOCX za pomocą .NET lub za pomocą bezpłatnego konwertera online
description: Konwertuj XLTM na DOCX na platformach .NET Framework, .NET Core, Mono lub Xamarin lub online. Szybko przetestuj darmowy konwerter online CSV na DOC przed integracją kodu.

family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: DOCX
otherformats: DOC PPTX POWERPOINT WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konwertuj XLTM na DOCX za pomocą C# lub Aplikacja internetowa" h2="Eksportuj Excel&reg; XLTM do DOCX na platformach .NET Framework, .NET Core, Mono lub Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konwersja XLTM do DOCX w .NET" %}}
1. Otwórz plik XLTM za pomocą klasy [Książka](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Konwertuj XLTM na PDF i ustaw SaveFormat na Auto
3. Załaduj przekonwertowany plik PDF za pomocą klasy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. Zapisz dokument w formacie DOCX za pomocą metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) i ustaw Docx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Kod .NET C# do konwersji XLTM na DOCX" gistPath="" %}}
```cs
// load the XLTM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltm");
// save XLTM as PDF
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

<h3>Darmowy konwerter online dla XLTM na DOCX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xltm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}