---
title: Export PS do PPT přes C# API
description: .NET API pro převod PS na PPT bez použití aplikace Microsoft Word
url_ignore: /cs/net/conversion/ps-to-ppt/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPT
otherformats: PPT POTX XAML PPS SWF POTM POWERPOINT PPSX PPTM PPSM POT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vykreslit PS na PPT přes .NET" h2=".NET API pro export PS do PPT na Windows, macOS a Linux bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí balíčku výkonných rozhraní API pro automatizaci formátů souborů [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno vykreslit PS na PPT ve dvou jednoduchých krocích. Pomocí rozhraní API pro zpracování PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete převést formát souboru PS na PPTX. Poté můžete pomocí rozhraní Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) převést PPTX na PPT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod PS na PPT" %}}
1. Otevřete soubor PS pomocí třídy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte PS na PPTX pomocí metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte soubor PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Uložte dokument do formátu PPT pomocí metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) a nastavte `Ppt` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Získejte metadata XMP ze souboru PS přes .NET" %}}
Při převodu PS na PPT možná budete potřebovat další informace o metadatech XMP, abyste upřednostnili proces dávkové konverze. Můžete například získat a seřadit své převodní dokumenty podle data vytvoření a podle toho je zpracovat. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) umožňuje přístup k metadatům XMP souboru PS. Chcete-li získat metadata souboru PS, můžete vytvořit objekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) a otevřít vstupní soubor PS. Poté můžete získat metadata souboru pomocí vlastnosti [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte soubor PPT pouze pro čtení přes .NET" %}}
Pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API můžete dále vylepšit funkce své konverzní aplikace. Jednou z funkcí může být vytvoření výstupního souboru pouze pro čtení pro zvýšení bezpečnosti. Rozhraní API vám umožňuje nastavit soubor PPT pouze pro čtení, což znamená, že uživatelé (po otevření prezentace) uvidí doporučení pouze pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru PS do PPT: Případy použití" %}}
PS (Portréfní Dokumentní Formát) soubory jsou využívány pro ukládání informací o layoutu, čímž jsou ideální pro tvorbu statických dokumentů jako jsou prezentace, zprávy a letáky. Nicméně při práci s dynamickými multimediálními obsahy se PowerPoint stává nezbytným pro vizualizaci a interakci.

Konverze PS souborů do formátů PowerPoint je nezbytná, aby jste mohli rozvířit plný potenciál svých schopností tvorby prezentací. Tato konverze vám umožňuje:

**Užití:**

*   **Tvorba a vývoj prezentace**: Konvertujte PS soubory pro vytvoření interaktivních a přitažlivých prezentací, které zahršťují text, obrázky, video a animace.
*   **Optimalizace prezentace**: Používáte PowerPoint pro opracování slайдů, úpravu layoutu a optimalizaci vizuálních prvků pro oštebdělující prezentaci.
*   **Správa obsahu a aktualizace**: Konvertujte PS soubory pro snadnou správu a aktualizaci obsahu na různých zařízeních a platformách, čímž zajistíte konzistenci a přesnost.
*   **Vytvoření příběhů**: Používáte PowerPoint pro tvorbu imerzních prezentací, které kombinují text, obrázky, audio a video pro předávání komplexních informací v přitažlivém způsobu.
*   **Sporadání práce a recenzentury**: Konvertujte PS soubory pro usnadnění spolupráce a zpětné vazby mezi členy týmu nebo zainteresovanými stranami přes sdílení večného času a komentáře.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}