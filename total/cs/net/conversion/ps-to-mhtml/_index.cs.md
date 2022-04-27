---
title: C# API pro export PS do MHTML
description: Převeďte PS na MHTML bez použití aplikace Microsoft Word
url: /cs/net/conversion/ps-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: MHTML
otherformats: DOTM OTT RTF DOTX FLATOPC DOT WORDML ODT MARKDOWN PCL MHTML XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vykreslete PS na MHTML přes .NET" h2=".NET API pro export PS do MHTML na Windows, macOS a Linux bez použití Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) je výkonné rozhraní API, které do vaší aplikace .NET přidává funkce pro manipulaci a převod dokumentů. Pomocí pokročilého rozhraní API pro zpracování PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete převést formát souboru PS na DOC. Poté můžete pomocí výkonného API pro zpracování dokumentů [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit DOC do MHTML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod PS na MHTML" %}}
1. Otevřete soubor PS pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte PS na Doc pomocí metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte soubor Doc pomocí třídy [Document](https://apireference.aspose.com/words/net/aspose.words/document) třídy Aspose.Words
4. Uložte dokument do formátu MHTML pomocí metody [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Mhtml jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.ps");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.mhtml", SaveFormat.Mhtml);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dešifrovat soubor PS pomocí hesla vlastníka přes .NET" %}}
Před převodem PS na MHTML, pokud chcete dešifrovat dokument, můžete to udělat pomocí API. Abyste mohli dešifrovat soubor PDF, musíte nejprve vytvořit objekt [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) a otevřít PS pomocí hesla vlastníka. Poté musíte zavolat metodu [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) objektu Document. Nakonec uložte aktualizovaný soubor pomocí metody Save objektu Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.ps", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte soubor MHTML pouze pro čtení přes .NET" %}}
Abyste ochránili svůj MHTML před úpravami a zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu, můžete také nastavit ochranu dokumentu pomocí API. Můžete omezit možnost upravovat dokument a povolit s ním pouze určité akce. To lze provést pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Umožňuje vám ovládat způsob, jakým omezujete obsah, pomocí parametru výčtu [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.mhtml", SaveFormat.Mhtml);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-ott/" name="PS Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-mhtml/" name="PS Na MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-wordml/" name="PS Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-dot/" name="PS Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-odt/" name="PS Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-rtf/" name="PS Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-ps/" name="PS Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-flatopc/" name="PS Na FLANaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-pcl/" name="PS Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-markdown/" name="PS Na MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-xamlflow/" name="PS Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/ps-to-dotx/" name="PS Na DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}