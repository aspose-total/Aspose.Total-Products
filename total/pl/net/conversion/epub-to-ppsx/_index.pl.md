---
title: Eksportuj EPUB do PPSX przez C# API
description: .NET API do konwersji EPUB na PPSX bez użycia Microsoft Word
url_ignore: /pl/net/conversion/epub-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPSX
otherformats: PPSM POTX PPT PPS XAML OTP PPTM PPSX POTM POT SWF POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj EPUB do PPSX przez .NET" h2=".NET API do eksportowania EPUB do PPSX w systemach Windows, macOS i Linux bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Korzystając z pakietu zaawansowanych interfejsów API automatyzacji formatowania plików [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo renderować EPUB do PPSX w dwóch prostych krokach. Korzystając z interfejsu API przetwarzania plików PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz przekształcić format pliku EPUB na PPTX. Następnie, korzystając z interfejsu API do przetwarzania prezentacji [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), możesz przekonwertować PPTX na PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji EPUB na PPSX" %}}
1. Otwórz plik EPUB za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj EPUB na PPTX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Zapisz dokument w formacie PPSX za pomocą metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) i ustaw `Ppsx` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj metadane XMP z pliku EPUB przez .NET" %}}
Podczas konwersji EPUB na PPSX możesz potrzebować dodatkowych informacji o metadanych XMP, aby nadać priorytet procesowi konwersji wsadowej. Na przykład możesz pobrać i posortować dokumenty konwersji na podstawie daty utworzenia i ppsxowiednio je przetworzyć. [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/) umożliwia dostęp do metadanych XMP pliku EPUB. Aby uzyskać metadane pliku EPUB, możesz utworzyć obiekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć wejściowy plik EPUB. Następnie możesz pobrać metadane pliku za pomocą właściwości [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik PPSX tylko do odczytu przez .NET" %}}
Korzystając z interfejsu API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) możesz jeszcze bardziej ulepszyć funkcje swojej aplikacji do konwersji. Jedną z funkcji może być utworzenie pliku wyjściowego tylko do odczytu w celu zwiększenia bezpieczeństwa. Interfejs API umożliwia ustawienie pliku PPSX w trybie tylko do odczytu, co oznacza, że użytkownicy (po otwarciu prezentacji) widzą zalecenie tylko do odczytu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsx", SaveFormat.Ppsx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EPUB w PPSX programowo: przypadki użycia" %}}
Przekształcanie plików EPUB na formaty PPSX jest niezbędne dla wykorzystania pełnego potencjalu swoich prezentacji.

Pliki EPUB są szeroko wykorzystywane do przechowaniu i udostępniania cyfrowych treści, takich jak książki elektroniczne, artykuły oraz inne typy publikacji. Jednak gdy chodzi o prezentacje, takie jak te tworzone za pomocą Microsoft PowerPoint, pliki EPUB stają się mniej idealne ze względu na swoje ograniczenia w prezentacji statycznych grafik i ilustracji.

Dlatego konieczne jest przekształcanie plików EPUB na formaty PPSX, aby wykorzystać pełny potencjal swoich prezentacji i umożliwić tworzenie:

**Wyznania użycia:**

- **Prezentacje w zakresie firmy**: Twórzcie profesjonalne prezentacje PowerPoint z dynamicznymi grafikami i animacjami.
- **Prezentacje akademickie**: Wykorzystujcie PPSX do wizualizacji skomplikowanych danych, takich jak wyniki badań i analiza statystyczna, w sposób interaktywny i przyciągający.
- **Materialy marketingowe i sprzedażowe**: Przekształćcie pliki EPUB do tworzenia atrakcyjnych materiałów na sprzedaż, takich jak filmy demonstracyjne i opinie klientów, które mogą być łatwo udostępniane dla kliencie i przypominanych potencjalnym klientom.
- **Prezentacje edukacyjne**: Wykorzystujcie PPSX do tworzenia interaktywnych prezentacji dla studentów, zawierających multimedię, quizy i oceny.
- **Prezentacje na konferencjach**: Przekształćcie pliki EPUB do tworzenia profesjonalnych prezentacji na konferencjach, zawierających przejściya, animacje i efekty specjalne.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}