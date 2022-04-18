---
title: Převeďte PCL na XLSB přes C# API
description: C# API pro převod souboru PCL do XLSB bez použití Microsoft Excel nebo Adobe Reader
url: /cs/net/conversion/pcl-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: XLSB
otherformats: TXT SXC FODS XLAM DIF XLSM MD TSV XLT XLTX XLTM EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API pro vykreslení PCL do XLSB" h2="Export souboru PCL do XLSB přes C# bez použití Microsoft<sup>&reg;</sup> Excel nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno převést soubor PCL na XLSB v jakékoli aplikaci .NET, C#, ASP.NET a VB.NET. Za prvé, pomocí [Aspose.PDF pro .NET] (https://products.aspose.com/pdf/net/) můžete exportovat PCL do XLSX. Poté můžete pomocí rozhraní [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API převést XLSX na XLSB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod PCL na XLSB" %}}
1. Otevřete soubor PCL pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte PCL na XLSX pomocí metody [Uložit](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte dokument XLSX pomocí třídy [Sešit](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Uložte dokument do formátu XLSB pomocí metody [Uložit](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) a nastavte `Xlsb` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Převést chráněné PCL na XLSB přes C#" %}}
Pokud je váš dokument PCL chráněn heslem, nemůžete jej bez hesla převést na XLSB. Pomocí API můžete nejprve otevřít chráněný dokument pomocí platného hesla a poté jej převést. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) a předat název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převést soubor PCL na XLSB s vodoznakem přes C#" %}}
Při převodu souboru PCL na XLSB můžete také přidat vodoznak do výstupního formátu souboru XLSB. Chcete-li přidat vodoznak, můžete vytvořit nový objekt Workbook a otevřít převedený dokument XLSX, vybrat Worksheet přes jeho index, vytvořit Shape a použít jeho funkci AddTextEffect. Poté můžete uložit dokument XLSX jako XLSB s vodoznakem. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-sxc/" name="PCL Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-xltx/" name="PCL Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-md/" name="PCL Na MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-tsv/" name="PCL Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-txt/" name="PCL Na TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-ods/" name="PCL Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-xlt/" name="PCL Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-xlsm/" name="PCL Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-xlam/" name="PCL Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-xltm/" name="PCL Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-dif/" name="PCL Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pcl-to-xlsb/" name="PCL Na XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}