---
title: Převeďte formát JSON na PPTM přes .NET
description: Analyzujte JSON na PPTM v C# bez použití Microsoft PowerPoint
url_ignore: /cs/net/conversion/json-to-pptm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPTM
otherformats: POWERPOINT POTM OTP POT PPS PPT PPSM POTX PPTM PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést formát JSON na PPTM přes C#" h2="C# API pro analýzu JSON na PPTM bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
JSON můžete převést na PPTM v rámci libovolné aplikace .NET, C#, ASP.NET a VB.NET ve dvou jednoduchých krocích. Za prvé, pomocí [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) můžete analyzovat JSON na PPTX. Poté můžete pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) převést PPTX na PPTM. Obě rozhraní API jsou součástí balíčku [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převést formát JSON na PPTM přes C#" %}}
1. Vytvořte nový objekt [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) a načtěte platná data JSON ze souboru
2. Importujte soubor JSON do listu pomocí třídy [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) a [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) to jako PPTX
3. Načtěte dokument PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Uložte dokument do formátu PPTM pomocí metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nastavte rozvržení a převeďte formát JSON na PPTM přes C#" %}}
Při analýze JSON na PPTM můžete také nastavit možnosti rozvržení pro váš formát JSON pomocí [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Umožňuje zpracovat pole jako tabulku, ignorovat hodnoty null, ignorovat název pole, ignorovat název objektu, převést řetězec na číslo nebo datum, nastavit formát data a čísla a nastavit styl nadpisu. Všechny tyto možnosti vám umožňují prezentovat data podle vašich potřeb. Následující fragment kódu ukazuje, jak nastavit možnosti rozvržení.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Převeďte formát JSON na PPTM s vodoznakem" %}}
Pomocí API můžete také převést JSON na PPTM s vodoznakem. Chcete-li do dokumentu PPTM přidat vodoznak, můžete nejprve analyzovat JSON na PPTX a přidat do něj vodoznak. Chcete-li přidat vodoznak, načtěte nově vytvořený soubor PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation), vyberte hlavní prezentaci, přidejte typ tvaru pomocí AddAutoShape a přidejte text vodoznaku pomocí AddTextFrame. Po přidání vodoznaku můžete dokument uložit do PPTM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}