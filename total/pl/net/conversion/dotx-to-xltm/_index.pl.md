---
title: .NET API do konwersji DOTX na XLTM
description: C# API do konwersji DOTX na XLTM bez użycia Microsoft Excel lub Adobe Reader
url_ignore: /pl/net/conversion/dotx-to-xltm/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: XLTM
otherformats: XLS XLT XLSX XLAM TSV XLSM EXCEL FODS XLTM SXC ODS DIF XLTX XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API do konwersji DOTX na XLTM" h2="Eksportuj DOTX do XLTM za pomocą C# bez użycia Microsoft<sup>&reg;</sup> Word lub Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz dołączyć funkcję konwersji DOTX do XLTM w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET w dwa proste kroki. Po pierwsze, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz wyeksportować DOTX do HTML. Następnie, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, możesz przekonwertować HTML na XLTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji DOTX na XLTM" %}}
1. Otwórz plik DOTX za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/Document)
2. Konwertuj DOTX na HTML za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.Document/save/methods/4)
3. Załaduj dokument HTML za pomocą klasy [Książka](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Zapisz dokument w formacie XLTM za pomocą metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) i ustaw `XLTM` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Załaduj dokument DOTX ze strumienia za pomocą C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia również ładowanie dokumentu DOTX przez strumień. Aby otworzyć dokument ze strumienia, po prostu przekaż obiekt strumienia, który zawiera dokument, do konstruktora [Document](https://reference.aspose.com/words/net/aspose.words/Document). Poniższy przykład kodu pokazuje, jak otworzyć dokument ze strumienia:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Dodaj niestandardowe właściwości w pliku XLTM za pomocą C#" %}}
Podczas konwertowania DOTX na XLTM [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) umożliwia dodawanie niestandardowych właściwości w dokumentach XLTM. Aby dodać niestandardową właściwość, możesz użyć metody [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection/methods/add/index) dla [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection). Metoda Add dodaje właściwość do pliku Excel i zwraca odwołanie do nowej właściwości dokumentu jako [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/Documentproperty). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-dif/" name="DOTX W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-xlsb/" name="DOTX W celu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-tsv/" name="DOTX W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-fods/" name="DOTX W celu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-xlt/" name="DOTX W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-excel/" name="DOTX W celu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-xlsx/" name="DOTX W celu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-ods/" name="DOTX W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-sxc/" name="DOTX W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-xlam/" name="DOTX W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-xltm/" name="DOTX W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-xlsm/" name="DOTX W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-xls/" name="DOTX W celu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/dotx-to-xltx/" name="DOTX W celu XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}