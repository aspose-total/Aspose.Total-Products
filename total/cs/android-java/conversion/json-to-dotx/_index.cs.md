---
title: Převeďte formát JSON na DOTX v systému Android přes Java
description: Analyzujte JSON na DOTX v Javě bez použití Microsoft Word
url: /cs/android-java/conversion/json-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOTX
otherformats: ODT DOCM DOT RTF PCL FLATOPC CHM OTT WORDML WORD DOC EPUB MOBI PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převeďte formát JSON na DOTX v aplikacích pro Android" h2="Analyzujte JSON na DOTX v aplikacích pro Android bez použití Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
JSON můžete převést na DOTX ve svých aplikacích pro Android ve dvou krocích. Za prvé, pomocí Powerful Spreadsheet Processing API [Aspose.Cells pro Android přes Java](https://products.aspose.com/cells/android-java/) můžete analyzovat JSON do PDF. Ve druhém kroku můžete převést PDF do DOTX pomocí rozhraní API pro zpracování textu [Aspose.Words pro Android přes Java](https://products.aspose.com/words/android-java/). Obě rozhraní API spadají do rodiny produktů [Aspose.Total pro Android přes Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte formát JSON na DOTX v systému Android přes Java" %}}
1. Vytvořte nový objekt [Sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a načtěte platná data JSON ze souboru
2. Importujte soubor JSON do listu pomocí třídy [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) a [Uložit](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) to jako PDF
3. Načtěte dokument PDF pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Uložte dokument do formátu DOTX pomocí [Uložit](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Android můžete snadno používat prostřednictvím Javy přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a nainstalovat knihovny do vaší aplikace.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nastavte Layout & Convert JSON Format to DOTX v Androidu přes Java" %}}
Kromě toho vám API umožňuje nastavit možnosti rozvržení pro váš formát JSON při analýze JSON do DOTX pomocí [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Umožňuje zpracovat pole jako tabulku, ignorovat hodnoty null, ignorovat název pole, ignorovat název objektu, převést řetězec na číslo nebo datum, nastavit formát data a čísla a nastavit styl nadpisu. Všechny tyto možnosti vám umožní prezentovat vaše data podle vašich potřeb. Následující fragment kódu ukazuje, jak nastavit možnosti rozvržení.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte formát JSON na DOTX s vodoznakem v systému Android přes Java" %}}
Pomocí API můžete také převést JSON na DOTX s vodoznakem. Chcete-li do dokumentu DOTX přidat vodoznak, můžete nejprve analyzovat soubor JSON do PDF a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte nově vytvořený soubor PDF pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), vytvořte instanci TextWatermarkOptions a nastavte jeho vlastnosti, zavolejte metodu Watermark.setText a předejte text vodoznaku a objekt TextWatermarkOptions. Po přidání vodoznaku můžete dokument uložit do DOTX.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-odt/" name="JSON Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-docm/" name="JSON Na DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-dot/" name="JSON Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-rtf/" name="JSON Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-pcl/" name="JSON Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-flatopc/" name="JSON Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-dotx/" name="JSON Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-ott/" name="JSON Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-wordml/" name="JSON Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-word/" name="JSON Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-doc/" name="JSON Na DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-epub/" name="JSON Na EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-mobi/" name="JSON Na MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/android-java/conversion/json-to-ps/" name="JSON Na PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}