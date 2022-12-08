---
title: Převeďte formát JSON na ODT přes C++
description: C++ API t0 analyzovat JSON do ODT bez použití aplikace Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: ODT
otherformats: MOBI DOCM FLATOPC CHM WORD DOTX WORDML PCL EPUB OTT PS RTF DOC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte formát JSON na ODT přes C++" h2="Analyzujte JSON na ODT v aplikacích C++ bez použití Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for C++](https://products.aspose.com/total/cpp/) můžete analyzovat JSON na ODT ve svých aplikacích C++ ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) můžete exportovat JSON do PDF. Poté můžete pomocí [Aspose.Words for C++](https://products.aspose.com/words/cppp/) převést PDF do ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte formát JSON na ODT v C++" %}}
1. Vytvořte nový objekt [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) a načtěte platná data JSON ze souboru
2. Uložte JSON jako PDF pomocí metody [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Načtěte dokument PDF pomocí třídy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Uložte dokument do formátu ODT pomocí metody [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Nainstalujte pomocí konzoly Package Manager Console sady Visual Studio pomocí ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nastavte rozložení a převeďte formát JSON na ODT v C++" %}}
Při analýze JSON na ODT můžete také nastavit velikost řádků a sloupců načtením JSON s třídou [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Pokud potřebujete nastavit stejnou výšku řádku pro všechny řádky v listu, můžete to udělat pomocí [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) metoda sbírky [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Podobně, chcete-li nastavit stejnou šířku sloupce pro všechny sloupce v listu, použijte [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) kolekce ICells
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte formát JSON na ODT s vodoznakem v C++" %}}
Pomocí API můžete také analyzovat JSON na ODT s vodoznakem. Chcete-li do dokumentu ODT přidat vodoznak, můžete nejprve převést JSON do PDF a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte nově vytvořený soubor PDF pomocí třídy [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), nastavte různé vlastnosti pro textový vodoznak,
zavolejte metodu SetText a předejte text vodoznaku a objekt TextWatermarkOptions. Po přidání vodoznaku můžete dokument uložit do ODT.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-mobi/" name="JSON Na MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-docm/" name="JSON Na DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-flatopc/" name="JSON Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-odt/" name="JSON Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-word/" name="JSON Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-dotx/" name="JSON Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-wordml/" name="JSON Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-pcl/" name="JSON Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-epub/" name="JSON Na EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-ott/" name="JSON Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-ps/" name="JSON Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-rtf/" name="JSON Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-doc/" name="JSON Na DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/json-to-dot/" name="JSON Na DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}