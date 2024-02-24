---
title: Převeďte formát JSON na ODT přes .NET
description: Analyzujte JSON na ODT v C# bez použití Microsoft Word
url_ignore: /cs/net/conversion/json-to-odt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODT
otherformats: DOTX WORD DOT RTF DOC DOCM MOBI OTT WORDML PCL ODT PS FLATOPC EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést formát JSON na ODT přes C#" h2="C# API pro analýzu JSON do ODT bez použití Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete analyzovat JSON na ODT v rámci libovolné aplikace .NET, C#, ASP.NET a VB.NET ve dvou jednoduchých kroky. Za prvé, pomocí [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) můžete exportovat JSON do PDF. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) převést PDF do ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převést formát JSON na ODT přes C#" %}}
1. Vytvořte nový objekt [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) a načtěte platná data JSON ze souboru
2. Importujte soubor JSON do listu pomocí třídy [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) a [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) jej jako PDF
3. Načtěte dokument PDF pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu ODT pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nastavte rozvržení a převeďte formát JSON na ODT přes C#" %}}
Při analýze JSON na ODT můžete také nastavit možnosti rozvržení pro JSON pomocí [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Umožňuje zpracovat pole jako tabulku, ignorovat hodnoty null, ignorovat název pole, ignorovat název objektu, převést řetězec na číslo nebo datum, nastavit formát data a čísla a nastavit styl nadpisu. Všechny tyto možnosti vám umožňují prezentovat data podle vašich potřeb. Následující fragment kódu ukazuje, jak nastavit možnosti rozvržení.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte formát JSON do ODT s vodoznakem" %}}
Pomocí API můžete také převést JSON na ODT s vodoznakem. Chcete-li do dokumentu ODT přidat vodoznak, můžete nejprve analyzovat soubor JSON do PDF a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte nově vytvořený soubor PDF pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document), vytvořte instanci TextWatermarkOptions a nastavte její vlastnosti, Zavolejte metodu Watermark.SetText a předejte text vodoznaku a objekt TextWatermarkOptions. Po přidání vodoznaku můžete dokument uložit do ODT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}