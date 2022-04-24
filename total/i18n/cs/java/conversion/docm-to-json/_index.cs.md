---
title: Převeďte DOCM do formátu JSON přes Java
description: Převeďte DOCM do formátu JSON přes Java bez použití Microsoft Word nebo Microsoft Excel
url: /cs/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převeďte DOCM do formátu JSON přes Java" h2="On Premise Java API pro převod DOCM na JSON bez použití Microsoft<sup>&reg;</sup> Word nebo Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Převod DOCM do formátu JSON prostřednictvím [Aspose.Total for Java](https://products.aspose.com/total/java/) je jednoduchý dvoukrokový proces. Pomocí rozhraní API pro manipulaci s dokumenty a konverzi [Aspose.Words for Java] (https://products.aspose.com/words/java/) můžete exportovat DOCM do HTML. Poté můžete pomocí [Aspose.Cells for Java](https://products.aspose.com/cells/java/) převést HTML na JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převeďte DOCM do formátu JSON přes Java" %}}
1. Otevřete soubor DOCM pomocí třídy [Docmument](https://apireference.aspose.com/words/java/com.aspose.words/Docmument)
2. Převeďte DOCM do HTML pomocí [Uložit](https://apireference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,com.aspose.words.SaveOptions) ) metoda
3. Načtěte dokument HTML pomocí třídy [Sešit](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Uložte dokument do formátu JSON pomocí [Uložit](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrňte knihovny do vašeho pom.xml.

Případně můžete získat soubor ZIP z [stažení] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Pomocí rozhraní API můžete také otevřít dokument chráněný heslem. Pokud je váš vstupní dokument DOCM chráněn heslem, nemůžete jej převést do formátu JSON bez použití hesla. Rozhraní API vám umožňuje otevřít zašifrovaný dokument předáním správného hesla v objektu LoadOptions. Následující příklad kódu ukazuje, jak se pokusit otevřít šifrovaný dokument pomocí hesla:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Převeďte chráněný DOCM do formátu JSON přes Java" %}}
Zatímco převádíte DOCM na JSON, můžete také nastavit rozsah výstupního formátu JSON. Chcete-li nastavit rozsah, můžete otevřít převedený HTML pomocí třídy Workbook, vytvořit rozsah dat k exportu pomocí metody Cells.createRange, zavolat metodu JsonUtility.exportRangeToJson s odkazy na Range & ExportRangeToJsonOptions a zapsat řetězec JSON dat do souboru přes Metoda BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xlam/" name="DOCM Na XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xlt/" name="DOCM Na XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-csv/" name="DOCM Na CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xlsx/" name="DOCM Na XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-fods/" name="DOCM Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xltm/" name="DOCM Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xlsm/" name="DOCM Na XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xltx/" name="DOCM Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-ods/" name="DOCM Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-xlsb/" name="DOCM Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-excel/" name="DOCM Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-sxc/" name="DOCM Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-tsv/" name="DOCM Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/docm-to-dif/" name="DOCM Na DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}