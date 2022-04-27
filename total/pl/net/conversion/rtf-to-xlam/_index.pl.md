---
title: .NET API do konwersji RTF na XLAM
description: C# API do konwersji RTF na XLAM bez użycia Microsoft Excel lub Adobe Reader
url: /pl/net/conversion/rtf-to-xlam/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: XLAM
otherformats: XLT XLTX XLSX XLS EXCEL SXC FODS ODS XLSM TSV XLTM XLAM XLSB DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API do konwersji RTF na XLAM" h2="Eksportuj RTF do XLAM za pomocą C# bez użycia Microsoft<sup>&reg;</sup> Word lub Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz dołączyć funkcję konwersji RTF do XLAM w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET w dwa proste kroki. Po pierwsze, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz wyeksportować RTF do HTML. Następnie, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, możesz przekonwertować HTML na XLAM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji RTF na XLAM" %}}
1. Otwórz plik RTF za pomocą klasy [Rtfument](https://apireference.aspose.com/words/net/aspose.words/rtfument)
2. Konwertuj RTF na HTML za pomocą metody [Save](https://apireference.aspose.com/words/net/aspose.words.rtfument/save/methods/4)
3. Załaduj dokument HTML za pomocą klasy [Książka](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Zapisz dokument w formacie XLAM za pomocą metody [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) i ustaw `XLAM` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Załaduj dokument RTF ze strumienia za pomocą C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia również ładowanie dokumentu RTF przez strumień. Aby otworzyć dokument ze strumienia, po prostu przekaż obiekt strumienia, który zawiera dokument, do konstruktora [Rtfument](https://apireference.aspose.com/words/net/aspose.words/rtfument). Poniższy przykład kodu pokazuje, jak otworzyć dokument ze strumienia:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
(https
{{% blocks/products/pf/feature-page-section  h2="Dodaj niestandardowe właściwości w pliku XLAM za pomocą C#" %}}
Podczas konwertowania RTF na XLAM [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) umożliwia dodawanie niestandardowych właściwości w dokumentach XLAM. Aby dodać niestandardową właściwość, możesz użyć metody [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customrtfumentpropertycollection/methods/add/index) dla [CustomRtfumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customrtfumentpropertycollection). Metoda Add dodaje właściwość do pliku Excel i zwraca odwołanie do nowej właściwości dokumentu jako [Aspose.Cells.Properties.RtfumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties /rtfumentproperty). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-dif/" name="RTF W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xlsb/" name="RTF W celu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-tsv/" name="RTF W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-fods/" name="RTF W celu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xlt/" name="RTF W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-excel/" name="RTF W celu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xlsx/" name="RTF W celu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-ods/" name="RTF W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-sxc/" name="RTF W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xlam/" name="RTF W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xltm/" name="RTF W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xlsm/" name="RTF W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xls/" name="RTF W celu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xltx/" name="RTF W celu XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}