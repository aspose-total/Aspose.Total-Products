---
title: Export MD do POWERPOINT přes C# API
description: .NET API pro převod MD na POWERPOINT bez použití aplikace Microsoft Word
url_ignore: /cs/net/conversion/md-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: POWERPOINT
otherformats: PPSM POWERPOINT POT PPT SWF PPSX POTX OTP POTM PPTM XAML PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vykreslit MD na POWERPOINT přes .NET" h2=".NET API pro export MD do POWERPOINT na Windows, macOS a Linux bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí balíčku výkonných rozhraní API pro automatizaci formátů souborů [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno vykreslit MD na POWERPOINT ve dvou jednoduchých krocích. Pomocí rozhraní API pro zpracování PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete převést formát souboru MD na PPTX. Poté můžete pomocí rozhraní Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) převést PPTX na POWERPOINT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod MD na POWERPOINT" %}}
1. Otevřete soubor MD pomocí třídy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte MD na PPTX pomocí metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte soubor PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Uložte dokument do formátu POWERPOINT pomocí metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) a nastavte `Powerpoint` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Získejte metadata XMP ze souboru MD přes .NET" %}}
Při převodu MD na POWERPOINT možná budete potřebovat další informace o metadatech XMP, abyste upřednostnili proces dávkové konverze. Můžete například získat a seřadit své převodní dokumenty podle data vytvoření a podle toho je zpracovat. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) umožňuje přístup k metadatům XMP souboru MD. Chcete-li získat metadata souboru MD, můžete vytvořit objekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) a otevřít vstupní soubor MD. Poté můžete získat metadata souboru pomocí vlastnosti [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte soubor POWERPOINT pouze pro čtení přes .NET" %}}
Pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API můžete dále vylepšit funkce své konverzní aplikace. Jednou z funkcí může být vytvoření výstupního souboru pouze pro čtení pro zvýšení bezpečnosti. Rozhraní API vám umožňuje nastavit soubor POWERPOINT pouze pro čtení, což znamená, že uživatelé (po otevření prezentace) uvidí doporučení pouze pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru MD do POWERPOINT: Případy použití" %}}
Výkladem Markdownových souborů do formátu PowerPoint je nezbytné, aby bylo možné uvolnit plnou potenciálku vašeho návrhu designu prezentací. Toto převést umožňuje:

**Užití:**

*   **Obchodní prezentace**: Převést Markdownovy soubory a vytvořit angažující obchodní prezentace, infografiky a shlédnutí pro vrchovní management, zákazníky a klienty.
*   **Vzdělání**: Použít PowerPoint pro prezentaci složitých pojetí, lektury a kurzy v jednoduchém formátu, čímž se učítí snáze.
*   **Osobní projekty a portréty**: Převést Markdownovy soubory a vytvořit krásné osobní projekty, portréty a blogy, které znázorňují vaše dovednosti a úspěchy.
*   **Technická dokumentace a průvodce**: Použít PowerPoint pro vytvoření interaktivní technické dokumentace, tutoriálů a průvodců pro programování, inženýrství a jiné technické obory.
*   **Marketingové a prodejní materiály**: Převést Markdownovy soubory a vytvořit přesvědčivé prodejní materiály, demo aplikace a marketingové prezentace, které ucháží pozornost diváků.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}