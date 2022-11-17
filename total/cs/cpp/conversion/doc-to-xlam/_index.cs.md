---
title: Převést DOC na XLAM v C++
description: C++ API pro převod DOC do XLAM bez použití Microsoft Word nebo Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: XLAM
otherformats: XLTX XLT XLSM SXC TSV XLSX XLTM EXCEL CSV XLSB DIF ODS FODS XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro převod DOC do XLAM" h2="Export DOC do XLAM přes C++ bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu DOC na XLAM můžete snadno zahrnout do svých aplikací C++. Pomocí funkčně bohatého, výkonného a snadno použitelného rozhraní API pro manipulaci a konverzi dokumentů [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete exportovat DOC do HTML. Poté můžete pomocí [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) převést HTML na XLAM. Obě rozhraní API jsou součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod DOC do XLAM" %}}
1. Otevřete soubor DOC pomocí odkazu třídy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
2. Převeďte DOC do HTML pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
3. Načtěte dokument HTML pomocí odkazu třídy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Uložte dokument do formátu XLAM pomocí členské funkce [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Přístup k vlastnostem dokumentu DOC přes C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) vám také umožňuje přístup k vlastnostem dokumentu souboru DOC a umožňuje vám učinit informované rozhodnutí před procesem převodu. Pro přístup k vlastnostem dokumentu můžete použít [BuiltInDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties) k získání integrovaných vlastností a [CustomDocumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties), abyste získali uživatelské vlastnosti. Následující příklad kódu ukazuje, jak vytvořit výčet všech vestavěných a vlastních vlastností v dokumentu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Uložit soubor XLAM do streamu přes C++" %}}
Po převedení DOC do XLAM vám [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) umožní uložit dokument ke streamování. Chcete-li uložit soubory do streamu, vytvořte objekt MemoryStream nebo FileStream a uložte soubor do tohoto objektu streamu voláním [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metodu objektu [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). Zadejte požadovaný formát souboru pomocí výčtu [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) při volání funkce [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-xltx/" name="DOC Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-xlt/" name="DOC Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-xlsm/" name="DOC Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-sxc/" name="DOC Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-tsv/" name="DOC Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-xlsx/" name="DOC Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-xltm/" name="DOC Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-excel/" name="DOC Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-xlam/" name="DOC Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-xlsb/" name="DOC Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-dif/" name="DOC Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-ods/" name="DOC Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-fods/" name="DOC Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/doc-to-xls/" name="DOC Na XLS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}