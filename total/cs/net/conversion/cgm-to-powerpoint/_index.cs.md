---
title: Export CGM do POWERPOINT přes C# API
description: .NET API pro převod CGM na POWERPOINT bez použití aplikace Microsoft Word
url_ignore: /cs/net/conversion/cgm-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POWERPOINT
otherformats: OTP PPSM PPS XAML PPSX PPT POTX PPTM POWERPOINT POT POTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vykreslit CGM na POWERPOINT přes .NET" h2=".NET API pro export CGM do POWERPOINT na Windows, macOS a Linux bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí balíčku výkonných rozhraní API pro automatizaci formátů souborů [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno vykreslit CGM na POWERPOINT ve dvou jednoduchých krocích. Pomocí rozhraní API pro zpracování PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete převést formát souboru CGM na PPTX. Poté můžete pomocí rozhraní Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) převést PPTX na POWERPOINT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod CGM na POWERPOINT" %}}
1. Otevřete soubor CGM pomocí třídy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte CGM na PPTX pomocí metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte soubor PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Uložte dokument do formátu POWERPOINT pomocí metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) a nastavte `Powerpoint` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Získejte metadata XMP ze souboru CGM přes .NET" %}}
Při převodu CGM na POWERPOINT možná budete potřebovat další informace o metadatech XMP, abyste upřednostnili proces dávkové konverze. Můžete například získat a seřadit své převodní dokumenty podle data vytvoření a podle toho je zpracovat. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) umožňuje přístup k metadatům XMP souboru CGM. Chcete-li získat metadata souboru CGM, můžete vytvořit objekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) a otevřít vstupní soubor CGM. Poté můžete získat metadata souboru pomocí vlastnosti [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru CGM do POWERPOINT: Případy použití" %}}
CGM (Computer Graphics Metafile) soubory jsou určeny pro ukládání informací o vectorových grafech, čímž je činí ideálními pro tvorbu statických grafických ilustrací a obrazců. Nicméně, při práci s dynamickými daty se PowerPoint stává nezbytným pro prezentování zábavných vizualizací a příběhů.

Konverze CGM souborů do formátů PowerPoint je nezbytná pro uvolnění plného potenciálu vašich schopností v prezentacích. Tato konverze vám umožňuje:

**Užití:**  

- **Korporativní prezentace**: Konvertování CGM souborů na tvorbu zábavných korporativních prezentací, sdělení komplexních datových vhledů a sdílení výsledků se zainteresovanými stranami.  
- **Vývoj výučkových materiálů**: Použití PowerPoint pro vizualizaci výučkového obsahu, simulování reálného světa, a poskytání interaktivních učeních.  
- **Vytváření marketingových materiálů**: Konvertování CGM souborů na tvorbu vizually působivých marketingových materiálů, jako jsou letáky, plakáty a posterové billboardy, které chytí pozornost a vyvolají angažmáni.  
- ** Vědecké prezentace**: Použití PowerPoint pro tvorbu interaktivních vědeckých prezentací, vizualizaci komplexních dat a účinnou komunikaci výzkumných výsledků.  
- **Vývoj e-learningových kurzů**: Konvertování CGM souborů na tvorbu imerzních e-learningových kurzů, využití animací a interakcí a zvýšení angažmáni studentů.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}