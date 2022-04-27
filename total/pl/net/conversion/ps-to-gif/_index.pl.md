---
title: C# API do eksportu PS do GIF
description: Konwertuj PS na GIF bez użycia Microsoft Word
url: /pl/net/conversion/ps-to-gif/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: GIF
otherformats: RTF MHTML XAMLFLOW GIF DOT MARKDOWN OTT ODT FLATOPC DOTX PCL WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj PS do GIF przez .NET" h2=".NET API do eksportu PS do GIF w systemach Windows, macOS i Linux bez użycia Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) to zaawansowany interfejs API do dodawania funkcji manipulacji dokumentami i konwersji w Twojej aplikacji .NET. Korzystając z zaawansowanego interfejsu API przetwarzania plików PDF [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/), możesz przekonwertować format pliku PS na DOC. Następnie, korzystając z potężnego interfejsu API przetwarzania dokumentów [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować DOC do GIF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji PS na GIF" %}}
1. Otwórz plik PS za pomocą klasy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj PS na Doc za pomocą metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik Doc za pomocą klasy [Document](https://apireference.aspose.com/words/net/aspose.words/document) Aspose.Words
4. Zapisz dokument w formacie GIF za pomocą metody [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Gif jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.ps");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.gif", SaveFormat.Gif);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Odszyfruj plik PS za pomocą hasła właściciela przez .NET" %}}
Przed konwersją PS do GIF, jeśli chcesz odszyfrować swój dokument, możesz to zrobić za pomocą interfejsu API. Aby odszyfrować plik PDF, musisz najpierw utworzyć obiekt [Dokument](https://apireference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć PS przy użyciu hasła właściciela. Następnie musisz wywołać metodę [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) obiektu Document. Na koniec zapisz zaktualizowany plik za pomocą metody Save obiektu Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.ps", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik GIF tylko do odczytu przez .NET" %}}
Aby chronić swój GIF przed edycją i uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie, możesz również ustawić ochronę dokumentu za pomocą interfejsu API. Możesz ograniczyć możliwość edycji dokumentu i zezwolić tylko na określone działania. Można to zrobić za pomocą interfejsu API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Umożliwia kontrolowanie sposobu ograniczania zawartości za pomocą parametru wyliczenia [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.gif", SaveFormat.Gif);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-ott/" name="PS W celu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-mhtml/" name="PS W celu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-wordml/" name="PS W celu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-dot/" name="PS W celu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-odt/" name="PS W celu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-rtf/" name="PS W celu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-ps/" name="PS W celu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-flatopc/" name="PS W celu FLAW celuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-pcl/" name="PS W celu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-markdown/" name="PS W celu MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-xamlflow/" name="PS W celu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ps-to-dotx/" name="PS W celu DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}