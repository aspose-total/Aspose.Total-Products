---
title: Převeďte formát JSON na CHM přes .NET
description: Analyzujte JSON na CHM v C# bez použití Microsoft Word
url: /cs/net/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: OTT FLATOPC PS DOTX RTF WORDML ODT WORD EPUB DOC DOT PCL MOBI DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést formát JSON na CHM přes C#" h2="C# API pro analýzu JSON do CHM bez použití Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete analyzovat JSON na CHM v rámci libovolné aplikace .NET, C#, ASP.NET a VB.NET ve dvou jednoduchých kroky. Za prvé, pomocí [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) můžete exportovat JSON do PDF. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) převést PDF do CHM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převést formát JSON na CHM přes C#" %}}
1. Vytvořte nový objekt [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) a načtěte platná data JSON ze souboru
2. Importujte soubor JSON do listu pomocí třídy [JsonUtility](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility) a [Save](https://apireference.aspose.com/ cells/net/aspose.cells.workbook/save/methods/4) jej jako PDF
3. Načtěte dokument PDF pomocí třídy [Document](https://apireference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu CHM pomocí metody [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nastavte rozvržení a převeďte formát JSON na CHM přes C#" %}}
Při analýze JSON na CHM můžete také nastavit možnosti rozvržení pro JSON pomocí [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Umožňuje zpracovat pole jako tabulku, ignorovat hodnoty null, ignorovat název pole, ignorovat název objektu, převést řetězec na číslo nebo datum, nastavit formát data a čísla a nastavit styl nadpisu. Všechny tyto možnosti vám umožňují prezentovat data podle vašich potřeb. Následující fragment kódu ukazuje, jak nastavit možnosti rozvržení.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte formát JSON do CHM s vodoznakem" %}}
Pomocí API můžete také převést JSON na CHM s vodoznakem. Chcete-li do dokumentu CHM přidat vodoznak, můžete nejprve analyzovat soubor JSON do PDF a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte nově vytvořený soubor PDF pomocí třídy [Document](https://apireference.aspose.com/words/net/aspose.words/document), vytvořte instanci TextWatermarkOptions a nastavte její vlastnosti , Zavolejte metodu Watermark.SetText a předejte text vodoznaku a objekt TextWatermarkOptions. Po přidání vodoznaku můžete dokument uložit do CHM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-ott/" name="JSON Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-flatopc/" name="JSON Na FLANaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-ps/" name="JSON Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-dotx/" name="JSON Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-rtf/" name="JSON Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-wordml/" name="JSON Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-odt/" name="JSON Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-word/" name="JSON Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-epub/" name="JSON Na EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-doc/" name="JSON Na DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-dot/" name="JSON Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-pcl/" name="JSON Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-mobi/" name="JSON Na MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-docm/" name="JSON Na DOCM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}