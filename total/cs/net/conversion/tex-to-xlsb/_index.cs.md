---
title: Převeďte TEX na XLSB přes C# API
description: C# API pro převod souboru TEX do XLSB bez použití Microsoft Excel nebo Adobe Reader
url_ignore: /cs/net/conversion/tex-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: XLSB
otherformats: XLTX ODS XLSM EXCEL FODS XLTM TXT SXC XLSB TSV MD DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API pro vykreslení TEX do XLSB" h2="Export souboru TEX do XLSB přes C# bez použití Microsoft<sup>&reg;</sup> Excel nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno převést soubor TEX na XLSB v jakékoli aplikaci .NET, C#, ASP.NET a VB.NET. Za prvé, pomocí [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete exportovat TEX do XLSX. Poté můžete pomocí rozhraní [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API převést XLSX na XLSB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod TEX na XLSB" %}}
1. Otevřete soubor TEX pomocí třídy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte TEX na XLSX pomocí metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte dokument XLSX pomocí třídy [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Uložte dokument do formátu XLSB pomocí metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) a nastavte `Xlsb` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Převést chráněné TEX na XLSB přes C#" %}}
Pokud je váš dokument TEX chráněn heslem, nemůžete jej bez hesla převést na XLSB. Pomocí API můžete nejprve otevřít chráněný dokument pomocí platného hesla a poté jej převést. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci třídy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) a předat název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převést soubor TEX na XLSB s vodoznakem přes C#" %}}
Při převodu souboru TEX na XLSB můžete také přidat vodoznak do výstupního formátu souboru XLSB. Chcete-li přidat vodoznak, můžete vytvořit nový objekt Workbook a otevřít převedený dokument XLSX, vybrat Worksheet přes jeho index, vytvořit Shape a použít jeho funkci AddTextEffect. Poté můžete uložit dokument XLSX jako XLSB s vodoznakem. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}