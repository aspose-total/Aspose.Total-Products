---
title: Převeďte XML na XLSM přes C# API
description: C# API pro převod souboru XML do XLSM bez použití Microsoft Excel nebo Adobe Reader
url: /cs/net/conversion/xml-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: XLSM
otherformats: MD XLAM XLSM XLSB TXT EXCEL SXC DIF XLT XLTX TSV FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API pro vykreslení XML do XLSM" h2="Export souboru XML do XLSM přes C# bez použití Microsoft<sup>&reg;</sup> Excel nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno převést soubor XML na XLSM v jakékoli aplikaci .NET, C#, ASP.NET a VB.NET. Za prvé, pomocí [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete exportovat XML do XLSX. Poté můžete pomocí rozhraní [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API převést XLSX na XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod XML na XLSM" %}}
1. Otevřete soubor XML pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte XML na XLSX pomocí metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte dokument XLSX pomocí třídy [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Uložte dokument do formátu XLSM pomocí metody [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) a nastavte `Xlsm` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Převést chráněné XML na XLSM přes C#" %}}
Pokud je váš dokument XML chráněn heslem, nemůžete jej bez hesla převést na XLSM. Pomocí API můžete nejprve otevřít chráněný dokument pomocí platného hesla a poté jej převést. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) a předat název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převést soubor XML na XLSM s vodoznakem přes C#" %}}
Při převodu souboru XML na XLSM můžete také přidat vodoznak do výstupního formátu souboru XLSM. Chcete-li přidat vodoznak, můžete vytvořit nový objekt Workbook a otevřít převedený dokument XLSX, vybrat Worksheet přes jeho index, vytvořit Shape a použít jeho funkci AddTextEffect. Poté můžete uložit dokument XLSX jako XLSM s vodoznakem. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-sxc/" name="XML Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-xltx/" name="XML Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-md/" name="XML Na MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-tsv/" name="XML Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-txt/" name="XML Na TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-ods/" name="XML Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-xlt/" name="XML Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-xlsm/" name="XML Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-xlam/" name="XML Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-xltm/" name="XML Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-dif/" name="XML Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-xlsb/" name="XML Na XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}