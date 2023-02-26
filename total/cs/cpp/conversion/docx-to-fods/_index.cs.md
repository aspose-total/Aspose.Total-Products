---
title: Převést DOCX na FODS v C++ nebo pomocí bezplatného online převodníku
description: C++ API pro převod DOCX do FODS nebo online bez použití Microsoft Word nebo Microsoft Excel nebo online. Před integrací kódu rychle otestujte bezplatný online převodník POT na CSV.

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: FODS
otherformats: XLSM XLTM SXC EXCEL CSV XLSB XLTX XLSX XLT DIF XLAM ODS TSV XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API pro převod DOCX do FODS nebo online" h2="Export DOCX do FODS přes C++ bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Funkci převodu DOCX na FODS můžete snadno zahrnout do svých aplikací C++. Pomocí funkčně bohatého, výkonného a snadno použitelného rozhraní API pro manipulaci a konverzi dokumentů [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete exportovat DOCX do HTML. Poté můžete pomocí [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) převést HTML na FODS. Obě rozhraní API jsou součástí balíčku [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod DOCX do FODS nebo online" %}}
1. Otevřete soubor DOCX pomocí odkazu třídy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
2. Převeďte DOCX do HTML pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
3. Načtěte dokument HTML pomocí odkazu třídy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Uložte dokument do formátu FODS pomocí členské funkce [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na konverzi" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Přístup k vlastnostem dokumentu DOCX přes C++" %}}DocumentDocument
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) vám také umožňuje přístup k vlastnostem dokumentu souboru DOCX a umožňuje vám učinit informované rozhodnutí před procesem převodu. Pro přístup k vlastnostem dokumentu můžete použít [BuiltInDocxumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties) k získání integrovaných vlastností a [CustomDocxumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties), abyste získali uživatelské vlastnosti. Následující příklad kódu ukazuje, jak vytvořit výčet všech vestavěných a vlastních vlastností v dokumentu.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Uložit soubor FODS do streamu přes C++" %}}
Po převedení DOCX do FODS vám [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) umožní uložit dokument ke streamování. Chcete-li uložit soubory do streamu, vytvořte objekt MemoryStream nebo FileStream a uložte soubor do tohoto objektu streamu voláním [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metodu objektu [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). Zadejte požadovaný formát souboru pomocí výčtu [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) při volání funkce [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-xlsm/" name="DOCX Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-xltm/" name="DOCX Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-sxc/" name="DOCX Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-excel/" name="DOCX Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-fods/" name="DOCX Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-xlsb/" name="DOCX Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-xltx/" name="DOCX Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-xlsx/" name="DOCX Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-xlt/" name="DOCX Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-dif/" name="DOCX Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-xlam/" name="DOCX Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-ods/" name="DOCX Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-tsv/" name="DOCX Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/docx-to-xls/" name="DOCX Na XLS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}