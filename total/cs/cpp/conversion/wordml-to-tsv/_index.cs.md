---
title: Převést WORDML na TSV v C++
description: C++ API pro převod WORDML do TSV bez použití Microsoft Word nebo Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: TSV
otherformats: CSV XLSB ODS XLTX XLTM SXC XLS XLSX XLSM FODS XLAM EXCEL DIF XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro převod WORDML do TSV" h2="Export WORDML do TSV přes C++ bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu WORDML na TSV můžete snadno zahrnout do svých aplikací C++. Pomocí funkčně bohatého, výkonného a snadno použitelného rozhraní API pro manipulaci a konverzi dokumentů [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete exportovat WORDML do HTML. Poté můžete pomocí [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) převést HTML na TSV. Obě rozhraní API jsou součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod WORDML do TSV" %}}
1. Otevřete soubor WORDML pomocí odkazu třídy [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument)
2. Převeďte WORDML do HTML pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string_saveformat)
3. Načtěte dokument HTML pomocí odkazu třídy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Uložte dokument do formátu TSV pomocí členské funkce [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Přístup k vlastnostem dokumentu WORDML přes C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) vám také umožňuje přístup k vlastnostem dokumentu souboru WORDML a umožňuje vám učinit informované rozhodnutí před procesem převodu. Pro přístup k vlastnostem dokumentu můžete použít [BuiltInWordmlumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_wordmlument_properties) k získání integrovaných vlastností a [CustomWordmlumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_wordmlument_properties), abyste získali uživatelské vlastnosti. Následující příklad kódu ukazuje, jak vytvořit výčet všech vestavěných a vlastních vlastností v dokumentu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-wordmlument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Uložit soubor TSV do streamu přes C++" %}}
Po převedení WORDML do TSV vám [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) umožní uložit dokument ke streamování. Chcete-li uložit soubory do streamu, vytvořte objekt MemoryStream nebo FileStream a uložte soubor do tohoto objektu streamu voláním [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metodu objektu [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). Zadejte požadovaný formát souboru pomocí výčtu [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) při volání funkce [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-tsv/" name="WORDML Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-xlsb/" name="WORDML Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-ods/" name="WORDML Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-xltx/" name="WORDML Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-xltm/" name="WORDML Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-sxc/" name="WORDML Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-xls/" name="WORDML Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-xlsx/" name="WORDML Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-xlsm/" name="WORDML Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-fods/" name="WORDML Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-xlam/" name="WORDML Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-excel/" name="WORDML Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-dif/" name="WORDML Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/wordml-to-xlt/" name="WORDML Na XLT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}