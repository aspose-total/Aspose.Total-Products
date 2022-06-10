---
title: Převeďte formát JSON na POTX přes .NET
description: Analyzujte JSON na POTX v C# bez použití Microsoft PowerPoint
url_ignore: /cs/net/conversion/json-to-potx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POTX
otherformats: PPSX OTP POTM PPS POWERPOINT PPTM POTX PPT POT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést formát JSON na POTX přes C#" h2="C# API pro analýzu JSON na POTX bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
JSON můžete převést na POTX v rámci libovolné aplikace .NET, C#, ASP.NET a VB.NET ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) můžete analyzovat JSON na PPTX. Poté můžete pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) převést PPTX na POTX. Obě rozhraní API jsou součástí balíčku [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převést formát JSON na POTX přes C#" %}}
1. Vytvořte nový objekt [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) a načtěte platná data JSON ze souboru
2. Importujte soubor JSON do listu pomocí třídy [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) a [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) to jako PPTX
3. Načtěte dokument PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Uložte dokument do formátu POTX pomocí metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nastavte rozvržení a převeďte formát JSON na POTX přes C#" %}}
Při analýze JSON na POTX můžete také nastavit možnosti rozvržení pro váš formát JSON pomocí [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Umožňuje zpracovat pole jako tabulku, ignorovat hodnoty null, ignorovat název pole, ignorovat název objektu, převést řetězec na číslo nebo datum, nastavit formát data a čísla a nastavit styl nadpisu. Všechny tyto možnosti vám umožňují prezentovat data podle vašich potřeb. Následující fragment kódu ukazuje, jak nastavit možnosti rozvržení.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte formát JSON na POTX s vodoznakem" %}}
Pomocí API můžete také převést JSON na POTX s vodoznakem. Chcete-li do dokumentu POTX přidat vodoznak, můžete nejprve analyzovat JSON na PPTX a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte nově vytvořený soubor PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation), vyberte hlavní prezentaci, přidejte typ tvaru pomocí AddAutoShape a přidejte text vodoznaku pomocí AddTextFrame. Po přidání vodoznaku můžete dokument uložit do POTX. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-ppt/" name="JSON Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-otp/" name="JSON Na OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-ppsx/" name="JSON Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-powerpoint/" name="JSON Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-potm/" name="JSON Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-pot/" name="JSON Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-ppsm/" name="JSON Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-potx/" name="JSON Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-pptm/" name="JSON Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/json-to-pps/" name="JSON Na PPS" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}