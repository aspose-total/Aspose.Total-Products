---
title: .NET API pro převod DOCX do CSV
description: C# API pro převod DOCX do CSV bez použití Microsoft Excel nebo Adobe Reader
url_ignore: /cs/net/conversion/docx-to-csv/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: CSV
otherformats: TSV SXC XLTX XLS XLSX XLT XLTM DIF XLSB FODS EXCEL XLSM XLAM ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API pro převod DOCX na CSV" h2="Export DOCX do CSV přes C# bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete zahrnout funkci převodu DOCX na CSV v jakékoli aplikaci .NET, C#, ASP.NET a VB.NET v dva jednoduché kroky. Za prvé, pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) můžete exportovat DOCX do HTML. Poté můžete pomocí rozhraní [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API převést HTML na CSV.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod DOCX do CSV" %}}
1. Otevřete soubor DOCX pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. Převeďte DOCX do HTML pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Načtěte dokument HTML pomocí třídy [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Uložte dokument do formátu CSV pomocí metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) a nastavte „CSV“ jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Načíst dokument DOCX ze streamu přes C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) vám také umožňuje načíst dokument DOCX prostřednictvím streamu. Chcete-li otevřít dokument ze streamu, jednoduše předejte objekt streamu, který obsahuje dokument, do konstruktoru [Document](https://reference.aspose.com/words/net/aspose.words/document). Následující příklad kódu ukazuje, jak otevřít dokument ze streamu:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Přidejte uživatelské vlastnosti do souboru CSV přes C#" %}}
Při převodu DOCX na CSV vám [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) umožňuje přidávat do dokumentů CSV vlastní vlastnosti. Chcete-li přidat vlastní vlastnost, můžete použít metodu [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) pro [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) třídy. Metoda Add přidá vlastnost do souboru aplikace Excel a vrátí odkaz na novou vlastnost dokumentu jako [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-dif/" name="DOCX Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-xlsb/" name="DOCX Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-tsv/" name="DOCX Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-fods/" name="DOCX Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-xlt/" name="DOCX Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-excel/" name="DOCX Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-xlsx/" name="DOCX Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-ods/" name="DOCX Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-sxc/" name="DOCX Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-xlam/" name="DOCX Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-xltm/" name="DOCX Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-xlsm/" name="DOCX Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-xls/" name="DOCX Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docx-to-xltx/" name="DOCX Na XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}