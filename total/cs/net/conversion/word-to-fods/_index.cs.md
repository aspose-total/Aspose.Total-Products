---
title: .NET API pro převod WORD do FODS
description: C# API pro převod WORD do FODS bez použití Microsoft Excel nebo Adobe Reader
url_ignore: /cs/net/conversion/word-to-fods/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: FODS
otherformats: EXCEL XLTX SXC XLTM TSV XLAM XLSX XLT XLSM XLSB FODS ODS DIF XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API pro převod WORD na FODS" h2="Export WORD do FODS přes C# bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete zahrnout funkci převodu WORD na FODS v jakékoli aplikaci .NET, C#, ASP.NET a VB.NET v dva jednoduché kroky. Za prvé, pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) můžete exportovat WORD do HTML. Poté můžete pomocí rozhraní [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API převést HTML na FODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod WORD do FODS" %}}
1. Otevřete soubor WORD pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. Převeďte WORD do HTML pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Načtěte dokument HTML pomocí třídy [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Uložte dokument do formátu FODS pomocí metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) a nastavte „FODS“ jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Načíst dokument WORD ze streamu přes C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) vám také umožňuje načíst dokument WORD prostřednictvím streamu. Chcete-li otevřít dokument ze streamu, jednoduše předejte objekt streamu, který obsahuje dokument, do konstruktoru [Document](https://reference.aspose.com/words/net/aspose.words/document). Následující příklad kódu ukazuje, jak otevřít dokument ze streamu:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Přidejte uživatelské vlastnosti do souboru FODS přes C#" %}}
Při převodu WORD na FODS vám [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) umožňuje přidávat do dokumentů FODS vlastní vlastnosti. Chcete-li přidat vlastní vlastnost, můžete použít metodu [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) pro [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) třídy. Metoda Add přidá vlastnost do souboru aplikace Excel a vrátí odkaz na novou vlastnost dokumentu jako [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties /documentproperty) objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-dif/" name="WORD Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-xlsb/" name="WORD Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-tsv/" name="WORD Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-fods/" name="WORD Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-xlt/" name="WORD Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-excel/" name="WORD Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-xlsx/" name="WORD Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-ods/" name="WORD Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-sxc/" name="WORD Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-xlam/" name="WORD Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-xltm/" name="WORD Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-xlsm/" name="WORD Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-xls/" name="WORD Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/word-to-xltx/" name="WORD Na XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}