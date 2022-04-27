---
title: C# API pro export MD do DOT
description: Převeďte MD na DOT bez použití aplikace Microsoft Word
url: /cs/net/conversion/md-to-dot/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOT
otherformats: FLATOPC WORDML PCL DOT DOTM ODT RTF MHTML OTT MARKDOWN XAMLFLOW DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vykreslete MD na DOT přes .NET" h2=".NET API pro export MD do DOT na Windows, macOS a Linux bez použití Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) je výkonné rozhraní API, které do vaší aplikace .NET přidává funkce pro manipulaci a převod dokumentů. Pomocí pokročilého rozhraní API pro zpracování PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete převést formát souboru MD na DOC. Poté můžete pomocí výkonného API pro zpracování dokumentů [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit DOC do DOT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod MD na DOT" %}}
1. Otevřete soubor MD pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte MD na Doc pomocí metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte soubor Doc pomocí třídy [Document](https://apireference.aspose.com/words/net/aspose.words/document) třídy Aspose.Words
4. Uložte dokument do formátu DOT pomocí metody [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Dot jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.md");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dot", SaveFormat.Dot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dešifrovat soubor MD pomocí hesla vlastníka přes .NET" %}}
Před převodem MD na DOT, pokud chcete dešifrovat dokument, můžete to udělat pomocí API. Abyste mohli dešifrovat soubor PDF, musíte nejprve vytvořit objekt [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) a otevřít MD pomocí hesla vlastníka. Poté musíte zavolat metodu [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) objektu Document. Nakonec uložte aktualizovaný soubor pomocí metody Save objektu Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.md", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte soubor DOT pouze pro čtení přes .NET" %}}
Abyste ochránili svůj DOT před úpravami a zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu, můžete také nastavit ochranu dokumentu pomocí API. Můžete omezit možnost upravovat dokument a povolit s ním pouze určité akce. To lze provést pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Umožňuje vám ovládat způsob, jakým omezujete obsah, pomocí parametru výčtu [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-ott/" name="MD Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-mhtml/" name="MD Na MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-wordml/" name="MD Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-dot/" name="MD Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-odt/" name="MD Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-rtf/" name="MD Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-ps/" name="MD Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-flatopc/" name="MD Na FLANaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-pcl/" name="MD Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-markdown/" name="MD Na MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-xamlflow/" name="MD Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/md-to-dotx/" name="MD Na DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}