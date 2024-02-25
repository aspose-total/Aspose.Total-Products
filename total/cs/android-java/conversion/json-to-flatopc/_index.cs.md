---
title: Převeďte formát JSON na FLATOPC v systému Android přes Java
description: Analyzujte JSON na FLATOPC v Javě bez použití Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: FLATOPC
otherformats: DOC PS CHM DOTX MOBI WORDML PCL OTT ODT DOT DOCM WORD EPUB RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte formát JSON na FLATOPC v aplikacích pro Android" h2="Analyzujte JSON na FLATOPC v aplikacích pro Android bez použití Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
JSON můžete převést na FLATOPC ve svých aplikacích pro Android ve dvou krocích. Za prvé, pomocí Powerful Spreadsheet Processing API [Aspose.Cells pro Android přes Java](https://products.aspose.com/cells/android-java/) můžete analyzovat JSON do PDF. Ve druhém kroku můžete převést PDF do FLATOPC pomocí rozhraní API pro zpracování textu [Aspose.Words pro Android přes Java](https://products.aspose.com/words/android-java/). Obě rozhraní API spadají do rodiny produktů [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte formát JSON na FLATOPC v systému Android přes Java" %}}
1. Vytvořte nový objekt [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a načtěte platná data JSON ze souboru
2. Importujte soubor JSON do listu pomocí třídy [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) a [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) to jako PDF
3. Načtěte dokument PDF pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Uložte dokument do formátu FLATOPC pomocí [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat prostřednictvím Javy přímo z [Maven](https://releases.aspose.com/total/java/) a nainstalovat knihovny do vaší aplikace.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nastavte Layout & Convert JSON Format to FLATOPC v Androidu přes Java" %}}
Kromě toho vám API umožňuje nastavit možnosti rozvržení pro váš formát JSON při analýze JSON do FLATOPC pomocí [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Umožňuje zpracovat pole jako tabulku, ignorovat hodnoty null, ignorovat název pole, ignorovat název objektu, převést řetězec na číslo nebo datum, nastavit formát data a čísla a nastavit styl nadpisu. Všechny tyto možnosti vám umožní prezentovat vaše data podle vašich potřeb. Následující fragment kódu ukazuje, jak nastavit možnosti rozvržení.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte formát JSON na FLATOPC s vodoznakem v systému Android přes Java" %}}
Pomocí API můžete také převést JSON na FLATOPC s vodoznakem. Chcete-li do dokumentu FLATOPC přidat vodoznak, můžete nejprve analyzovat soubor JSON do PDF a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte nově vytvořený soubor PDF pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), vytvořte instanci TextWatermarkOptions a nastavte jeho vlastnosti, zavolejte metodu Watermark.setText a předejte text vodoznaku a objekt TextWatermarkOptions. Po přidání vodoznaku můžete dokument uložit do FLATOPC.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}