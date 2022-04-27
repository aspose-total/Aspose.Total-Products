---
title: Konwertuj XPS na FODS za pomocą C# API
description: C# API do konwersji pliku XPS na FODS bez użycia Microsoft Excel lub Adobe Reader
url: /pl/net/conversion/xps-to-fods/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: FODS
otherformats: ODS TSV SXC MD XLSB XLT XLSM XLTM DIF XLAM FODS TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API do renderowania XPS do FODS" h2="Eksportuj plik XPS do FODS za pomocą C# bez użycia Microsoft<sup>&reg;</sup> Excel lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo przekonwertować plik XPS na FODS w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET. Po pierwsze, używając [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz wyeksportować XPS do XLSX. Następnie, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, możesz przekonwertować XLSX na FODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji XPS na FODS" %}}
1. Otwórz plik XPS za pomocą klasy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj XPS na XLSX za pomocą metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj dokument XLSX za pomocą klasy [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Zapisz dokument w formacie FODS za pomocą metody [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) i ustaw `Fods` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony plik XPS na FODS za pomocą C#" %}}
Jeśli dokument XPS jest chroniony hasłem, nie można go przekonwertować na FODS bez hasła. Korzystając z interfejsu API, możesz najpierw otworzyć chroniony dokument przy użyciu prawidłowego hasła, a następnie przekonwertować go. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie klasy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) i przekazać nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj plik XPS na FODS za pomocą znaku wodnego za pomocą C#" %}}
Konwertując plik XPS na FODS, możesz także dodać znak wodny do wyjściowego formatu pliku FODS. Aby dodać znak wodny, możesz utworzyć nowy obiekt Workbook i otworzyć przekonwertowany dokument XLSX, wybrać Arkusz roboczy poprzez jego indeks, utworzyć Kształt i użyć jego funkcji AddTextEffect. Następnie możesz zapisać dokument XLSX jako FODS ze znakiem wodnym. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-sxc/" name="XPS W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-xltx/" name="XPS W celu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-md/" name="XPS W celu MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-tsv/" name="XPS W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-txt/" name="XPS W celu TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-ods/" name="XPS W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-xlt/" name="XPS W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-xlsm/" name="XPS W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-xlam/" name="XPS W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-xltm/" name="XPS W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-dif/" name="XPS W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-xlsb/" name="XPS W celu XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}