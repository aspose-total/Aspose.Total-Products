---
title: C# API do eksportu CGM do MARKDOWN
description: Konwertuj CGM na MARKDOWN bez użycia Microsoft Word
url: /pl/net/conversion/cgm-to-markdown/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MARKDOWN
otherformats: MARKDOWN WORDML DOTX DOT DOTM XAMLFLOW FLATOPC ODT OTT RTF PCL MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj CGM do MARKDOWN przez .NET" h2=".NET API do eksportu CGM do MARKDOWN w systemach Windows, macOS i Linux bez użycia Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) to zaawansowany interfejs API do dodawania funkcji manipulacji dokumentami i konwersji w Twojej aplikacji .NET. Korzystając z zaawansowanego interfejsu API przetwarzania plików PDF [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/), możesz przekonwertować format pliku CGM na DOC. Następnie, korzystając z potężnego interfejsu API przetwarzania dokumentów [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować DOC do MARKDOWN.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji CGM na MARKDOWN" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj CGM na Doc za pomocą metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik Doc za pomocą klasy [Document](https://apireference.aspose.com/words/net/aspose.words/document) Aspose.Words
4. Zapisz dokument w formacie MARKDOWN za pomocą metody [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Markdown jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.cgm");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.markdown", SaveFormat.Markdown);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Odszyfruj plik CGM za pomocą hasła właściciela przez .NET" %}}
Przed konwersją CGM do MARKDOWN, jeśli chcesz odszyfrować swój dokument, możesz to zrobić za pomocą interfejsu API. Aby odszyfrować plik PDF, musisz najpierw utworzyć obiekt [Dokument](https://apireference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć CGM przy użyciu hasła właściciela. Następnie musisz wywołać metodę [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) obiektu Document. Na koniec zapisz zaktualizowany plik za pomocą metody Save obiektu Document.  
{{% blocks/products/pf/feature-page-code %}}
```cs


Document document = new Document("Decrypt.cgm", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik MARKDOWN tylko do odczytu przez .NET" %}}
Aby chronić swój MARKDOWN przed edycją i uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie, możesz również ustawić ochronę dokumentu za pomocą interfejsu API. Możesz ograniczyć możliwość edycji dokumentu i zezwolić tylko na określone działania. Można to zrobić za pomocą interfejsu API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Umożliwia kontrolowanie sposobu ograniczania zawartości za pomocą parametru wyliczenia [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
```cs

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.markdown", SaveFormat.Markdown);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-ott/" name="CGM W celu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-mhtml/" name="CGM W celu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-wordml/" name="CGM W celu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-dot/" name="CGM W celu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-odt/" name="CGM W celu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-rtf/" name="CGM W celu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-ps/" name="CGM W celu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-flatopc/" name="CGM W celu FLAW celuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-pcl/" name="CGM W celu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-markdown/" name="CGM W celu MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-xamlflow/" name="CGM W celu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/cgm-to-dotx/" name="CGM W celu DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}