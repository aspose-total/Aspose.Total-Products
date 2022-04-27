---
title: Export PS do POTX přes C# API
description: .NET API pro převod PS na POTX bez použití aplikace Microsoft Word
url: /cs/net/conversion/ps-to-potx/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POTX
otherformats: PPS SWF PPTM XAML OTP PPSX POT POWERPOINT PPSM PPT POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vykreslit PS na POTX přes .NET" h2=".NET API pro export PS do POTX na Windows, macOS a Linux bez použití Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí balíčku výkonných rozhraní API pro automatizaci formátů souborů [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete snadno vykreslit PS na POTX ve dvou jednoduchých krocích. Pomocí rozhraní API pro zpracování PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete převést formát souboru PS na PPTX. Poté můžete pomocí rozhraní Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) převést PPTX na POTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API pro převod PS na POTX" %}}
1. Otevřete soubor PS pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte PS na PPTX pomocí metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte soubor PPTX pomocí třídy [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Uložte dokument do formátu POTX pomocí metody [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) a nastavte `Potx` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.ps");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.potx", SaveFormat.Potx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Získejte metadata XMP ze souboru PS přes .NET" %}}
Při převodu PS na POTX možná budete potřebovat další informace o metadatech XMP, abyste upřednostnili proces dávkové konverze. Můžete například získat a seřadit své převodní dokumenty podle data vytvoření a podle toho je zpracovat. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) umožňuje přístup k metadatům XMP souboru PS. Chcete-li získat metadata souboru PS, můžete vytvořit objekt [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) a otevřít vstupní soubor PS. Poté můžete získat metadata souboru pomocí vlastnosti [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.ps");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte soubor POTX pouze pro čtení přes .NET" %}}
Pomocí [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API můžete dále vylepšit funkce své konverzní aplikace. Jednou z funkcí může být vytvoření výstupního souboru pouze pro čtení pro zvýšení bezpečnosti. Rozhraní API vám umožňuje nastavit soubor POTX pouze pro čtení, což znamená, že uživatelé (po otevření prezentace) uvidí doporučení pouze pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potx", SaveFormat.Potx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-pot/" name="PS Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-ppsx/" name="PS Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-swf/" name="PS Na SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-powerpoint/" name="PS Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-otp/" name="PS Na OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-potm/" name="PS Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-ppt/" name="PS Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-pps/" name="PS Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-potx/" name="PS Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-xaml/" name="PS Na XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-ppsm/" name="PS Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-pptm/" name="PS Na PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}