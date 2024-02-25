---
title: Převeďte WORD do formátu JSON v C++
description: Export WORD do JSON v C++ bez použití Microsoft Excel nebo Word

family: total
platformtag: cpp
feature: conversion
informat: WORD
outformat: JSON
otherformats: SXC XLSX XLS DIF XLSB XLT XLAM TSV XLTM XLSM EXCEL XLTX FODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte WORD do formátu JSON pomocí C++" h2="Exportujte WORD do JSON přes C++ bez použití Microsoft<sup>&reg;</sup> Word nebo Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for C++](https://products.aspose.com/total/cpp/) můžete převést WORD do formátu JSON ve svých aplikacích C++. Za prvé, pomocí [Aspose.Words for C++](https://products.aspose.com/words/cpp/) můžete exportovat WORD do HTML. Poté můžete pomocí [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) převést HTML do formátu JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte WORD do formátu JSON pomocí C++" %}}
1. Otevřete soubor WORD pomocí odkazu třídy [Wordument](https://reference.aspose.com/words/cpp/class/aspose.words.wordument)
2. Převeďte WORD do HTML pomocí členské funkce [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordument#save_string_saveformat)
3. Načtěte dokument HTML pomocí odkazu třídy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Uložte dokument do formátu JSON pomocí členské funkce [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Nainstalujte pomocí konzoly Package Manager Console sady Visual Studio pomocí ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte chráněný WORD do formátu JSON pomocí C++" %}}
Pomocí rozhraní API můžete také otevřít dokument chráněný heslem. Pokud je váš vstupní dokument WORD chráněn heslem, nemůžete jej převést do formátu JSON bez použití hesla. K tomu použijte speciální přetížení konstruktoru, který přijímá objekt LoadOptions. Tento objekt obsahuje vlastnost Password, která určuje řetězec hesla.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}