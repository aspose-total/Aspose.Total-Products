---
title: Převést DOT na FODS v C++
description: C++ API pro převod DOT do FODS bez použití Microsoft Word nebo Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOT
outformat: FODS
otherformats: XLTX XLAM XLS EXCEL XLTM SXC XLSM CSV ODS DIF XLT XLSX TSV XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro převod DOT do FODS" h2="Export DOT do FODS přes C++ bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu DOT na FODS můžete snadno zahrnout do svých aplikací C++. Pomocí funkčně bohatého, výkonného a snadno použitelného rozhraní API pro manipulaci a konverzi dokumentů [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete exportovat DOT do HTML. Poté můžete pomocí [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) převést HTML na FODS. Obě rozhraní API jsou součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod DOT do FODS" %}}
1. Otevřete soubor DOT pomocí odkazu třídy [Dotument](https://reference.aspose.com/words/cpp/class/aspose.words.dotument)
2. Převeďte DOT do HTML pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_string_saveformat)
3. Načtěte dokument HTML pomocí odkazu třídy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Uložte dokument do formátu FODS pomocí členské funkce [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Přístup k vlastnostem dokumentu DOT přes C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) vám také umožňuje přístup k vlastnostem dokumentu souboru DOT a umožňuje vám učinit informované rozhodnutí před procesem převodu. Pro přístup k vlastnostem dokumentu můžete použít [BuiltInDotumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_dotument_properties) k získání integrovaných vlastností a [CustomDotumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_dotument_properties), abyste získali uživatelské vlastnosti. Následující příklad kódu ukazuje, jak vytvořit výčet všech vestavěných a vlastních vlastností v dokumentu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-dotument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Uložit soubor FODS do streamu přes C++" %}}
Po převedení DOT do FODS vám [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) umožní uložit dokument ke streamování. Chcete-li uložit soubory do streamu, vytvořte objekt MemoryStream nebo FileStream a uložte soubor do tohoto objektu streamu voláním [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metodu objektu [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). Zadejte požadovaný formát souboru pomocí výčtu [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) při volání funkce [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-xltx/" name="DOT Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-xlam/" name="DOT Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-xls/" name="DOT Na XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-excel/" name="DOT Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-xltm/" name="DOT Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-sxc/" name="DOT Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-xlsm/" name="DOT Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-fods/" name="DOT Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-ods/" name="DOT Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-dif/" name="DOT Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-xlt/" name="DOT Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-xlsx/" name="DOT Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-tsv/" name="DOT Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/dot-to-xlsb/" name="DOT Na XLSB" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}