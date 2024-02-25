---
title: Převeďte formát JSON na POTM přes Java
description: Analyzujte JSON na POTM v Javě bez použití Microsoft PowerPoint
url_ignore: /cs/java/conversion/json-to-potm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POTM
otherformats: POTM PPT PPSM POWERPOINT OTP POTX POT PPSX PPS PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převeďte formát JSON na POTM přes Java" h2="Java API pro analýzu formátu JSON na POTM bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete převést formát JSON na POTM v jakékoli aplikaci Java ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.Cells for Java](https://products.aspose.com/cells/java/) můžete analyzovat JSON na PPTX. Poté můžete pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/java/) převést PPTX na POTM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte formát JSON na POTM přes Java" %}}
1. Vytvořte nový objekt [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a otevřete soubor JSON
2. Uložte JSON jako PPTX pomocí [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
3. Načtěte dokument PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Uložte dokument do formátu POTM pomocí metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Kromě toho vám API umožňuje analyzovat JSON na POTM se zadanými možnostmi rozvržení. Chcete-li určit možnosti rozložení, můžete použít třídu [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Umožňuje zpracovat pole jako tabulku, ignorovat hodnoty null, ignorovat název pole, ignorovat název objektu, převést řetězec na číslo nebo datum, nastavit datum a formát čísla a nastavit styl nadpisu. Všechny tyto možnosti vám umožňují prezentovat data podle vašich potřeb. Následující fragment kódu ukazuje, jak nastavit možnosti rozvržení.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Nastavte rozvržení a převeďte formát JSON na POTM přes Java" %}}
Pomocí API můžete také převést JSON na POTM s vodoznakem. Chcete-li do dokumentu POTM přidat vodoznak, můžete nejprve analyzovat JSON na PPTX a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte nově vytvořený soubor PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), projděte všechny snímky, přidejte text pomocí addTextFrame nastavte všechny relevantní možnosti, jako je barva, fillType a další, a můžete uložit dokument do POTM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}