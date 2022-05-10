---
title: .NET API pro převod RTF do XLSX
description: C# API pro převod RTF do XLSX bez použití Microsoft Excel nebo Adobe Reader
url_ignore: /cs/net/conversion/rtf-to-xlsx/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: XLSX
otherformats: FODS XLTM SXC XLSB EXCEL XLS XLSX XLTX XLT XLAM TSV ODS XLSM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API pro převod RTF na XLSX" h2="Export RTF do XLSX přes C# bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete zahrnout funkci převodu RTF na XLSX v jakékoli aplikaci .NET, C#, ASP.NET a VB.NET v dva jednoduché kroky. Za prvé, pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) můžete exportovat RTF do HTML. Poté můžete pomocí rozhraní [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API převést HTML na XLSX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod RTF do XLSX" %}}
1. Otevřete soubor RTF pomocí třídy [Document](https://apireference.aspose.com/words/net/aspose.words/Document)
2. Převeďte RTF do HTML pomocí metody [Save](https://apireference.aspose.com/words/net/aspose.words.Document/save/methods/4)
3. Načtěte dokument HTML pomocí třídy [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Uložte dokument do formátu XLSX pomocí metody [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) a nastavte „XLSX“ jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Načíst dokument RTF ze streamu přes C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) vám také umožňuje načíst dokument RTF prostřednictvím streamu. Chcete-li otevřít dokument ze streamu, jednoduše předejte objekt streamu, který obsahuje dokument, do konstruktoru [Document](https://apireference.aspose.com/words/net/aspose.words/Document). Následující příklad kódu ukazuje, jak otevřít dokument ze streamu:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Přidejte uživatelské vlastnosti do souboru XLSX přes C#" %}}
Při převodu RTF na XLSX vám [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) umožňuje přidávat do dokumentů XLSX vlastní vlastnosti. Chcete-li přidat vlastní vlastnost, můžete použít metodu [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection/methods/add/index) pro [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection) třídy. Metoda Add přidá vlastnost do souboru aplikace Excel a vrátí odkaz na novou vlastnost dokumentu jako [Aspose.Cells.Properties.DocumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties/Documentproperty) objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-dif/" name="RTF Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xlsb/" name="RTF Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-tsv/" name="RTF Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-fods/" name="RTF Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xlt/" name="RTF Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-excel/" name="RTF Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xlsx/" name="RTF Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-ods/" name="RTF Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-sxc/" name="RTF Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xlam/" name="RTF Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xltm/" name="RTF Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xlsm/" name="RTF Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xls/" name="RTF Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/rtf-to-xltx/" name="RTF Na XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}