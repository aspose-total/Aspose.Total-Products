---
title: .NET API pro převod DOC do XLAM nebo pomocí bezplatného online převodníku
description: C# API pro převod DOC do XLAM bez použití Microsoft Excel nebo Adobe Reader nebo online. Před integrací kódu rychle otestujte bezplatný online převodník CSV na DOC. 
url_ignore: /cs/net/conversion/doc-to-xlam/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: XLAM
otherformats: TSV XLTM XLSM EXCEL XLSB XLSX XLS ODS XLT DIF XLTX XLAM FODS SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API pro převod DOC na XLAM nebo online aplikace" h2="Export DOC do XLAM přes C# bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete zahrnout funkci převodu DOC na XLAM v jakékoli aplikaci .NET, C#, ASP.NET a VB.NET v dva jednoduché kroky. Za prvé, pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) můžete exportovat DOC do HTML. Poté můžete pomocí rozhraní [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API převést HTML na XLAM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod DOC do XLAM" %}}
1. Otevřete soubor DOC pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. Převeďte DOC do HTML pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Načtěte dokument HTML pomocí třídy [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Uložte dokument do formátu XLAM pomocí metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) a nastavte „XLAM“ jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Zdarma online převodník DOC na XLAM</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=xlam&from=doc" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Načíst dokument DOC ze streamu přes C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) vám také umožňuje načíst dokument DOC prostřednictvím streamu. Chcete-li otevřít dokument ze streamu, jednoduše předejte objekt streamu, který obsahuje dokument, do konstruktoru [Document](https://reference.aspose.com/words/net/aspose.words/document). Následující příklad kódu ukazuje, jak otevřít dokument ze streamu:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Přidejte uživatelské vlastnosti do souboru XLAM přes C#" %}}
Při převodu DOC na XLAM vám [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) umožňuje přidávat do dokumentů XLAM vlastní vlastnosti. Chcete-li přidat vlastní vlastnost, můžete použít metodu [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) pro [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) třídy. Metoda Add přidá vlastnost do souboru aplikace Excel a vrátí odkaz na novou vlastnost dokumentu jako [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}