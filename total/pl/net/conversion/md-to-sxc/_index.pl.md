---
title: Konwertuj MD na SXC za pomocą C# API
description: C# API do konwersji pliku MD na SXC bez użycia Microsoft Excel lub Adobe Reader
url_ignore: /pl/net/conversion/md-to-sxc/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: SXC
otherformats: XLTM DIF XLAM XLTX SXC XLSB XLT TSV EXCEL FODS TXT ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API do renderowania MD do SXC" h2="Eksportuj plik MD do SXC za pomocą C# bez użycia Microsoft<sup>&reg;</sup> Excel lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo przekonwertować plik MD na SXC w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET. Po pierwsze, używając [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz wyeksportować MD do XLSX. Następnie, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, możesz przekonwertować XLSX na SXC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji MD na SXC" %}}
1. Otwórz plik MD za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj MD na XLSX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj dokument XLSX za pomocą klasy [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Zapisz dokument w formacie SXC za pomocą metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) i ustaw `Sxc` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony plik MD na SXC za pomocą C#" %}}
Jeśli dokument MD jest chroniony hasłem, nie można go przekonwertować na SXC bez hasła. Korzystając z interfejsu API, możesz najpierw otworzyć chroniony dokument przy użyciu prawidłowego hasła, a następnie przekonwertować go. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i przekazać nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj plik MD na SXC za pomocą znaku wodnego za pomocą C#" %}}
Konwertując plik MD na SXC, możesz także dodać znak wodny do wyjściowego formatu pliku SXC. Aby dodać znak wodny, możesz utworzyć nowy obiekt Workbook i otworzyć przekonwertowany dokument XLSX, wybrać Arkusz roboczy poprzez jego indeks, utworzyć Kształt i użyć jego funkcji AddTextEffect. Następnie możesz zapisać dokument XLSX jako SXC ze znakiem wodnym. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-sxc/" name="MD W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-xltx/" name="MD W celu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-md/" name="MD W celu MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-tsv/" name="MD W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-txt/" name="MD W celu TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-ods/" name="MD W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-xlt/" name="MD W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-xlsm/" name="MD W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-xlam/" name="MD W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-xltm/" name="MD W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-dif/" name="MD W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/md-to-xlsb/" name="MD W celu XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}