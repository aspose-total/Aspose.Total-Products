---
title: Export PS do SWF přes C# API
description: .NET API pro převod PS na SWF bez použití aplikace Microsoft Word
url_ignore: /cs/net/conversion/ps-to-swf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SWF
otherformats: PPSM POTM OTP POWERPOINT PPS PPTM POT POTX XAML SWF PPSX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vykreslit PS na SWF přes .NET" h2=".NET API pro export PS do SWF na Windows, macOS a Linux bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí balíčku výkonných rozhraní API pro automatizaci formátů souborů [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno vykreslit PS na SWF ve dvou jednoduchých krocích. Pomocí rozhraní API pro zpracování PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete převést formát souboru PS na PPTX. Poté můžete pomocí rozhraní Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) převést PPTX na SWF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod PS na SWF" %}}
1. Otevřete soubor PS pomocí třídy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte PS na PPTX pomocí metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte soubor PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Uložte dokument do formátu SWF pomocí metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) a nastavte `Swf` jako SaveFormat
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
Při převodu PS na SWF možná budete potřebovat další informace o metadatech XMP, abyste upřednostnili proces dávkové konverze. Můžete například získat a seřadit své převodní dokumenty podle data vytvoření a podle toho je zpracovat. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) umožňuje přístup k metadatům XMP souboru PS. Chcete-li získat metadata souboru PS, můžete vytvořit objekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) a otevřít vstupní soubor PS. Poté můžete získat metadata souboru pomocí vlastnosti [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte soubor SWF pouze pro čtení přes .NET" %}}
Pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API můžete dále vylepšit funkce své konverzní aplikace. Jednou z funkcí může být vytvoření výstupního souboru pouze pro čtení pro zvýšení bezpečnosti. Rozhraní API vám umožňuje nastavit soubor SWF pouze pro čtení, což znamená, že uživatelé (po otevření prezentace) uvidí doporučení pouze pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.swf", SaveFormat.Swf);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru PS do SWF: Případy použití" %}}
**PS (Portrétní skribový soubor) soubory jsou určeny pro ukládání informací o dokumentech, čímž se stávají ideálem pro tvorbu statických dokumentů a grafiky. Nicméně při práci s interaktivní multimediální content, SWF (Small Web Format - Malý webový formát) soubory získávají klíčovou roli pro zahrání a zobrazování.

Výkon konverze PS souborů na SWF formáty je nezbytný pro uvolnění plného potenciálu vaší interaktivní multimediální content. Tato konverze vám umožňuje:

**Užití:**

*   **Interaktivní E-Learning obsah**: Zkonvertovat PS soubory do SWF formátu pro tvorbu osvědčených online kursov, tutoriálů a vzdělávacích materiálů, které lze zahrát na různých zařízeních.  
*   **Animační filmy a TV show klipy**: Použít SWF soubory k přidání interaktivity ke filmům a TV show klipům, čímž je budou více přívětivými pro diváky.  
*   **Videoherní aktiva a efekty**: Zkonvertovat PS soubory do SWF formátu pro tvorbu interaktivních videoherních aktива, efektů a animací, které zvýší zážitky z hraní.  
*   **Web-based aplikace a simulace**: Použít SWF soubory pro vytvoření interaktivních webových aplikací, simulací a obsahu, který nabízí imerzní zážitky.  
*   **Obsah mobilních aplikací a reklamy**: Zkonvertovat PS soubory pro tvorbu osvědčených mobilních aplikacích, reklamních spotů a her, které budou chytat uživatele na cestách.**
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}