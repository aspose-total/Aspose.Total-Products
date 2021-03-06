---
title: C# API do eksportu SVG do DOT
description: Konwertuj SVG na DOT bez użycia Microsoft Word
url_ignore: /pl/net/conversion/svg-to-dot/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: DOT
otherformats: RTF PS WORDML FLATOPC DOTX PCL MARKDOWN DOTM XAMLFLOW ODT OTT MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj SVG do DOT przez .NET" h2=".NET API do eksportu SVG do DOT w systemach Windows, macOS i Linux bez użycia Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) to zaawansowany interfejs API do dodawania funkcji manipulacji dokumentami i konwersji w Twojej aplikacji .NET. Korzystając z zaawansowanego interfejsu API przetwarzania plików PDF [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/), możesz przekonwertować format pliku SVG na DOC. Następnie, korzystając z potężnego interfejsu API przetwarzania dokumentów [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować DOC do DOT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji SVG na DOT" %}}
1. Otwórz plik SVG za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj SVG na Doc za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik Doc za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document) Aspose.Words
4. Zapisz dokument w formacie DOT za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Dot jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.svg");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dot", SaveFormat.Dot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Odszyfruj plik SVG za pomocą hasła właściciela przez .NET" %}}
Przed konwersją SVG do DOT, jeśli chcesz odszyfrować swój dokument, możesz to zrobić za pomocą interfejsu API. Aby odszyfrować plik PDF, musisz najpierw utworzyć obiekt [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć SVG przy użyciu hasła właściciela. Następnie musisz wywołać metodę [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) obiektu Document. Na koniec zapisz zaktualizowany plik za pomocą metody Save obiektu Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.svg", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik DOT tylko do odczytu przez .NET" %}}
Aby chronić swój DOT przed edycją i uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie, możesz również ustawić ochronę dokumentu za pomocą interfejsu API. Możesz ograniczyć możliwość edycji dokumentu i zezwolić tylko na określone działania. Można to zrobić za pomocą interfejsu API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Umożliwia kontrolowanie sposobu ograniczania zawartości za pomocą parametru wyliczenia [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-ott/" name="SVG W celu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-mhtml/" name="SVG W celu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-wordml/" name="SVG W celu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-dot/" name="SVG W celu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-odt/" name="SVG W celu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-rtf/" name="SVG W celu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-ps/" name="SVG W celu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-flatopc/" name="SVG W celu FLAW celuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-pcl/" name="SVG W celu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-markdown/" name="SVG W celu MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-xamlflow/" name="SVG W celu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/svg-to-dotx/" name="SVG W celu DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}