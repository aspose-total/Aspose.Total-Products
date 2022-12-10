---
title: Převeďte formát JSON na DOT přes Java
description: Analyzujte JSON na DOT v Javě bez použití Microsoft Word
url_ignore: /cs/java/conversion/json-to-dot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOT
otherformats: RTF FLATOPC ODT DOTX WORDML PCL DOC EPUB OTT WORD PS MOBI DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převeďte formát JSON na DOT přes Java" h2="On premise Java API pro analýzu JSON do DOT bez použití Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete převést JSON na DOT ve svých aplikacích Java ve dvou krocích. Za prvé, pomocí [Aspose.Cells for Java](https://products.aspose.com/cells/java/) můžete analyzovat JSON do PDF. Ve druhém kroku můžete převést PDF do DOT pomocí rozhraní API pro zpracování textu [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte formát JSON na DOT přes Java" %}}
1. Vytvořte nový objekt [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a načtěte platná data JSON ze souboru
2. Importujte soubor JSON do listu pomocí třídy [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) a [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) to jako PDF
3. Načtěte dokument PDF pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Uložte dokument do formátu DOT pomocí [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Kromě toho vám API umožňuje nastavit možnosti rozvržení pro váš JSON při analýze JSON do DOT pomocí [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Umožňuje zpracovat pole jako tabulku, ignorovat hodnoty null, ignorovat název pole, ignorovat název objektu, převést řetězec na číslo nebo datum, nastavit formát data a čísla a nastavit styl nadpisu. Všechny tyto možnosti vám umožňují prezentovat data podle vašich potřeb. Následující fragment kódu ukazuje, jak nastavit možnosti rozvržení.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Nastavte Layout & Convert JSON Format to DOT přes Java" %}}
Pomocí API můžete také analyzovat JSON na DOT s vodoznakem. Chcete-li do dokumentu DOT přidat vodoznak, můžete nejprve převést soubor JSON do formátu PDF a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte nově vytvořený soubor PDF pomocí třídy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), vytvořte instanci TextWatermarkOptions a nastavte jeho vlastnosti, zavolejte metodu Watermark.setText a předejte text vodoznaku a objekt TextWatermarkOptions. Po přidání vodoznaku můžete dokument uložit do DOT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-flatopc/" name="JSON Na FLANaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-docm/" name="JSON Na DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-word/" name="JSON Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-wordml/" name="JSON Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-odt/" name="JSON Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-rtf/" name="JSON Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-doc/" name="JSON Na DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-mobi/" name="JSON Na MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-ott/" name="JSON Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-dotx/" name="JSON Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-pcl/" name="JSON Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-dot/" name="JSON Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-epub/" name="JSON Na EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-ps/" name="JSON Na PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}