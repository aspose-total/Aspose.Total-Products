---
title: C# API do eksportu EPUB do RTF
description: Konwertuj EPUB na RTF bez użycia Microsoft Word
url_ignore: /pl/net/conversion/epub-to-rtf/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: RTF
otherformats: DOTX DOTM OTT WORDML XAMLFLOW PCL FLATOPC PS ODT DOT RTF MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj EPUB do RTF przez .NET" h2=".NET API do eksportu EPUB do RTF w systemach Windows, macOS i Linux bez użycia Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) to zaawansowany interfejs API do dodawania funkcji manipulacji dokumentami i konwersji w Twojej aplikacji .NET. Korzystając z zaawansowanego interfejsu API przetwarzania plików PDF [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/), możesz przekonwertować format pliku EPUB na DOC. Następnie, korzystając z potężnego interfejsu API przetwarzania dokumentów [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować DOC do RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EPUB na RTF" %}}
1. Otwórz plik EPUB za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj EPUB na Doc za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik Doc za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document) Aspose.Words
4. Zapisz dokument w formacie RTF za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Rtf jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Odszyfruj plik EPUB za pomocą hasła właściciela przez .NET" %}}
Przed konwersją EPUB do RTF, jeśli chcesz odszyfrować swój dokument, możesz to zrobić za pomocą interfejsu API. Aby odszyfrować plik PDF, musisz najpierw utworzyć obiekt [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć EPUB przy użyciu hasła właściciela. Następnie musisz wywołać metodę [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) obiektu Document. Na koniec zapisz zaktualizowany plik za pomocą metody Save obiektu Document.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik RTF tylko do odczytu przez .NET" %}}
Aby chronić swój RTF przed edycją i uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie, możesz również ustawić ochronę dokumentu za pomocą interfejsu API. Możesz ograniczyć możliwość edycji dokumentu i zezwolić tylko na określone działania. Można to zrobić za pomocą interfejsu API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Umożliwia kontrolowanie sposobu ograniczania zawartości za pomocą parametru wyliczenia [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EPUB w RTF programowo: przypadki użycia" %}}
Przekształcanie plików EPUB na RTF: Wykorzystanie pełnych możliwości funkcji edycyjnych.

Konwersja plików EPUB na format RTF jest niezbędna do wykorzystania pełnych możliwości funkcji edycyjnych dokumentu. Ta konwersja pozwala na:

**Użycia przypadków:**

- **Przegląd i edycja dokumentu**: Przekształć plik EPUB, aby lepiej współpracować z kolegami i klientami.
- **Poprawa dostępności**: Wykorzystać format RTF do poprawy czytelności dokumentu dzięki konwersji literatury i układu.
- **Zgodność z przestarodowymi programami**: Przekształć plik EPUB na RTF dla zgodności z przestarodowanym oprogramowaniem, aby zapewnić ciągły tok w pracy.
- **Tworzenie e-booków**: Stworzyć własne e-booky dzięki możliwości dodania funkcji takich jak odniki i linki.
- **Publikacja i dystrybucja dokumentu**: Wykorzystać format RTF do publikacji dla szerszego odbioru, w tym osób przyktyczających się na format RTF.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}