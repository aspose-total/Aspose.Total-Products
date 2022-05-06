---
title: .NET API do konwersji DOT na FODS
description: C# API do konwersji DOT na FODS bez użycia Microsoft Excel lub Adobe Reader
url_ignore: /pl/net/conversion/dot-to-fods/
family: total
platformtag: net
feature: conversion
informat: DOT
outformat: FODS
otherformats: DIF XLTM XLSX XLAM EXCEL XLTX ODS XLSB XLT XLS FODS TSV XLSM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API do konwersji DOT na FODS" h2="Eksportuj DOT do FODS za pomocą C# bez użycia Microsoft<sup>&reg;</sup> Word lub Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz dołączyć funkcję konwersji DOT do FODS w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET w dwa proste kroki. Po pierwsze, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz wyeksportować DOT do HTML. Następnie, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, możesz przekonwertować HTML na FODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji DOT na FODS" %}}
1. Otwórz plik DOT za pomocą klasy [Document](https://apireference.aspose.com/words/net/aspose.words/Document)
2. Konwertuj DOT na HTML za pomocą metody [Save](https://apireference.aspose.com/words/net/aspose.words.Document/save/methods/4)
3. Załaduj dokument HTML za pomocą klasy [Książka](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Zapisz dokument w formacie FODS za pomocą metody [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) i ustaw `FODS` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Załaduj dokument DOT ze strumienia za pomocą C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia również ładowanie dokumentu DOT przez strumień. Aby otworzyć dokument ze strumienia, po prostu przekaż obiekt strumienia, który zawiera dokument, do konstruktora [Document](https://apireference.aspose.com/words/net/aspose.words/Document). Poniższy przykład kodu pokazuje, jak otworzyć dokument ze strumienia:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Dodaj niestandardowe właściwości w pliku FODS za pomocą C#" %}}
Podczas konwertowania DOT na FODS [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) umożliwia dodawanie niestandardowych właściwości w dokumentach FODS. Aby dodać niestandardową właściwość, możesz użyć metody [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection/methods/add/index) dla [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection). Metoda Add dodaje właściwość do pliku Excel i zwraca odwołanie do nowej właściwości dokumentu jako [Aspose.Cells.Properties.DocumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties /Documentproperty). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-dif/" name="DOT W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-xlsb/" name="DOT W celu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-tsv/" name="DOT W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-fods/" name="DOT W celu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-xlt/" name="DOT W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-excel/" name="DOT W celu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-xlsx/" name="DOT W celu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-ods/" name="DOT W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-sxc/" name="DOT W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-xlam/" name="DOT W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-xltm/" name="DOT W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-xlsm/" name="DOT W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-xls/" name="DOT W celu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dot-to-xltx/" name="DOT W celu XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}