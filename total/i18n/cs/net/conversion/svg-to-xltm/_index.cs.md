---
title: Převeďte SVG na XLTM přes C# API
description: C# API pro převod souboru SVG do XLTM bez použití Microsoft Excel nebo Adobe Reader
url: /cs/net/conversion/svg-to-xltm/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: XLTM
otherformats: XLT MD TXT XLTX XLTM FODS XLSB XLSM XLAM SXC ODS TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API pro vykreslení SVG do XLTM" h2="Export souboru SVG do XLTM přes C# bez použití Microsoft<sup>&reg;</sup> Excel nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno převést soubor SVG na XLTM v jakékoli aplikaci .NET, C#, ASP.NET a VB.NET. Za prvé, pomocí [Aspose.PDF pro .NET] (https://products.aspose.com/pdf/net/) můžete exportovat SVG do XLSX. Poté můžete pomocí rozhraní [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API převést XLSX na XLTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod SVG na XLTM" %}}
1. Otevřete soubor SVG pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte SVG na XLSX pomocí metody [Uložit](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte dokument XLSX pomocí třídy [Sešit](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Uložte dokument do formátu XLTM pomocí metody [Uložit](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) a nastavte `Xltm` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Převést chráněné SVG na XLTM přes C#" %}}
Pokud je váš dokument SVG chráněn heslem, nemůžete jej bez hesla převést na XLTM. Pomocí API můžete nejprve otevřít chráněný dokument pomocí platného hesla a poté jej převést. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) a předat název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převést soubor SVG na XLTM s vodoznakem přes C#" %}}
Při převodu souboru SVG na XLTM můžete také přidat vodoznak do výstupního formátu souboru XLTM. Chcete-li přidat vodoznak, můžete vytvořit nový objekt Workbook a otevřít převedený dokument XLSX, vybrat Worksheet přes jeho index, vytvořit Shape a použít jeho funkci AddTextEffect. Poté můžete uložit dokument XLSX jako XLTM s vodoznakem. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-sxc/" name="SVG Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xltx/" name="SVG Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-md/" name="SVG Na MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-tsv/" name="SVG Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-txt/" name="SVG Na TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-ods/" name="SVG Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xlt/" name="SVG Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xlsm/" name="SVG Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xlam/" name="SVG Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xltm/" name="SVG Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-dif/" name="SVG Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/svg-to-xlsb/" name="SVG Na XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}