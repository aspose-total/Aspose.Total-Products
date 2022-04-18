---
title: C# API pro export CGM do DOTX
description: Převeďte CGM na DOTX bez použití aplikace Microsoft Word
url: /cs/net/conversion/cgm-to-dotx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOTX
otherformats: ODT RTF MHTML MARKDOWN DOTX PS WORDML DOTM XAMLFLOW OTT FLATOPC PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vykreslete CGM na DOTX přes .NET" h2=".NET API pro export CGM do DOTX na Windows, macOS a Linux bez použití Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) je výkonné rozhraní API, které do vaší aplikace .NET přidává funkce pro manipulaci a převod dokumentů. Pomocí pokročilého rozhraní API pro zpracování PDF [Aspose.PDF for .NET] (https://products.aspose.com/pdf/net/) můžete převést formát souboru CGM na DOC. Poté můžete pomocí výkonného API pro zpracování dokumentů [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit DOC do DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod CGM na DOTX" %}}
1. Otevřete soubor CGM pomocí třídy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte CGM na Doc pomocí metody [Uložit](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte soubor Doc pomocí třídy [Document](https://apireference.aspose.com/words/net/aspose.words/document) třídy Aspose.Words
4. Uložte dokument do formátu DOTX pomocí metody [Uložit](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Dotx jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.cgm");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dotx", SaveFormat.Dotx);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dešifrovat soubor CGM pomocí hesla vlastníka přes .NET" %}}
Před převodem CGM na DOTX, pokud chcete dešifrovat dokument, můžete to udělat pomocí API. Abyste mohli dešifrovat soubor PDF, musíte nejprve vytvořit objekt [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) a otevřít CGM pomocí hesla vlastníka. Poté musíte zavolat metodu [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) objektu Document. Nakonec uložte aktualizovaný soubor pomocí metody Save objektu Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.cgm", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte soubor DOTX pouze pro čtení přes .NET" %}}
Abyste ochránili svůj DOTX před úpravami a zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu, můžete také nastavit ochranu dokumentu pomocí API. Můžete omezit možnost upravovat dokument a povolit s ním pouze určité akce. To lze provést pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Umožňuje vám ovládat způsob, jakým omezujete obsah, pomocí parametru výčtu [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-ott/" name="CGM Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-mhtml/" name="CGM Na MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-wordml/" name="CGM Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-dot/" name="CGM Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-odt/" name="CGM Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-rtf/" name="CGM Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-ps/" name="CGM Na PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-flatopc/" name="CGM Na FLANaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-pcl/" name="CGM Na PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-markdown/" name="CGM Na MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-xamlflow/" name="CGM Na XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/cgm-to-dotx/" name="CGM Na DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}