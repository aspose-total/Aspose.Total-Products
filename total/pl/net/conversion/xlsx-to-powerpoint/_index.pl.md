---
title: Konwertuj XLSX na POWERPOINT za pomocą .NET 
description: Konwertuj XLSX na POWERPOINT na platformach .NET Framework, .NET Core, Mono lub Xamarin
url: /pl/net/conversion/xlsx-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: PPTX DOC WORD DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konwertuj XLSX na POWERPOINT za pomocą C#" h2="Eksportuj Excel&reg; XLSX do POWERPOINT na platformach .NET Framework, .NET Core, Mono lub Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konwersja XLSX do POWERPOINT w .NET" %}}
1. Otwórz plik XLSX za pomocą klasy [Książka](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Konwertuj XLSX na PDF i ustaw SaveFormat na Auto
3. Załaduj przekonwertowany plik PDF za pomocą klasy [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. Zapisz dokument w formacie POWERPOINT za pomocą metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) i ustaw Powerpoint jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Kod .NET C# do konwersji XLSX na POWERPOINT" gistPath="" %}}
```cs
// load the XLSX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsx");
// save XLSX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/csv-to-word/" name="CSV Do WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/csv-to-powerpoint/" name="CSV Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/csv-to-pptx/" name="CSV Do PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/csv-to-docx/" name="CSV Do DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}