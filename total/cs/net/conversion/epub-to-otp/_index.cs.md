---
title: Export EPUB do OTP přes C# API
description: .NET API pro převod EPUB na OTP bez použití aplikace Microsoft Word
url_ignore: /cs/net/conversion/epub-to-otp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: OTP
otherformats: OTP PPSX PPSM POTM POWERPOINT PPS POTX XAML SWF PPT PPTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vykreslit EPUB na OTP přes .NET" h2=".NET API pro export EPUB do OTP na Windows, macOS a Linux bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí balíčku výkonných rozhraní API pro automatizaci formátů souborů [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno vykreslit EPUB na OTP ve dvou jednoduchých krocích. Pomocí rozhraní API pro zpracování PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete převést formát souboru EPUB na PPTX. Poté můžete pomocí rozhraní Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) převést PPTX na OTP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod EPUB na OTP" %}}
1. Otevřete soubor EPUB pomocí třídy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte EPUB na PPTX pomocí metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte soubor PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Uložte dokument do formátu OTP pomocí metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) a nastavte `Otp` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Získejte metadata XMP ze souboru EPUB přes .NET" %}}
Při převodu EPUB na OTP možná budete potřebovat další informace o metadatech XMP, abyste upřednostnili proces dávkové konverze. Můžete například získat a seřadit své převodní dokumenty podle data vytvoření a podle toho je zpracovat. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) umožňuje přístup k metadatům XMP souboru EPUB. Chcete-li získat metadata souboru EPUB, můžete vytvořit objekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) a otevřít vstupní soubor EPUB. Poté můžete získat metadata souboru pomocí vlastnosti [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte soubor OTP pouze pro čtení přes .NET" %}}
Pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API můžete dále vylepšit funkce své konverzní aplikace. Jednou z funkcí může být vytvoření výstupního souboru pouze pro čtení pro zvýšení bezpečnosti. Rozhraní API vám umožňuje nastavit soubor OTP pouze pro čtení, což znamená, že uživatelé (po otevření prezentace) uvidí doporučení pouze pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.otp", SaveFormat.Otp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EPUB do OTP: Případy použití" %}}
Elektronická kniha (e-book) jsou soubory používané pro ukládání digitálního obsahu, což je ideální pro tvorbu dynamického obsahu a interaktivních zážitků. Nicméně, když pracujeme se offline daty, textové soubory stanou se nezbytnými pro dlouhodobé uložení a archivování.

Konverze e-book souborů na Offline Textové soubory je nezbytná, aby se mohlo využít plné potenciál archivů a knihoven. Tato konverze umožňuje:

**Užití:**

*   **Digitální archivace**: Konvertovat e-book soubory pro vytvoření trvalých archivů, které zajistí, že digitální obsah zůstává přístupný po dlouhou dobu.
*   **Offline čtení a sdílení**: Použít Offline Textové soubory pro distribuci digitálního obsahu bez závislosti na internetovém připojení, což je ideální pro oblasti se omezeným přístupem nebo v situacích, kdy není dostupné Wi-Fi.
*   **Správa knihoven a organizace**: Konvertovat e-book soubory pro vytvoření organizovaného a strukturovaného sboru textových dat, které usnadňují hledání, kategorizaci a extrakci konkrétní informace.
*   **Digitální archivování a obnovlení**: Použít Offline Textové soubory pro uložení digitálních artifactů a obnovlení poškozeného obsahu, aby zůstalo cenné informační zboomkniženo pro budoucí generace.
*   **Offline tvorba a editace obsahu**: Konvertovat e-book soubory pro vytvoření editovaného obsahu bez závislosti na internetovém připojení, což je ideální pro autory, spisovatelé a vydavatele, kteří potřebují pracovat v izolaci nebo se omezeným přístupem k online prostředkům.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}