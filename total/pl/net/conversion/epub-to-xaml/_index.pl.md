---
title: Eksportuj EPUB do XAML przez C# API
description: .NET API do konwersji EPUB na XAML bez użycia Microsoft Word
url_ignore: /pl/net/conversion/epub-to-xaml/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: XAML
otherformats: PPTM OTP SWF PPSX PPS POWERPOINT XAML POTM PPSM PPT POTX POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj EPUB do XAML przez .NET" h2=".NET API do eksportowania EPUB do XAML w systemach Windows, macOS i Linux bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Korzystając z pakietu zaawansowanych interfejsów API automatyzacji formatowania plików [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo renderować EPUB do XAML w dwóch prostych krokach. Korzystając z interfejsu API przetwarzania plików PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz przekształcić format pliku EPUB na PPTX. Następnie, korzystając z interfejsu API do przetwarzania prezentacji [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), możesz przekonwertować PPTX na XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji EPUB na XAML" %}}
1. Otwórz plik EPUB za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj EPUB na PPTX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Zapisz dokument w formacie XAML za pomocą metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) i ustaw `Xaml` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj metadane XMP z pliku EPUB przez .NET" %}}
Podczas konwersji EPUB na XAML możesz potrzebować dodatkowych informacji o metadanych XMP, aby nadać priorytet procesowi konwersji wsadowej. Na przykład możesz pobrać i posortować dokumenty konwersji na podstawie daty utworzenia i xamlowiednio je przetworzyć. [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/) umożliwia dostęp do metadanych XMP pliku EPUB. Aby uzyskać metadane pliku EPUB, możesz utworzyć obiekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć wejściowy plik EPUB. Następnie możesz pobrać metadane pliku za pomocą właściwości [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik XAML tylko do odczytu przez .NET" %}}
Korzystając z interfejsu API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) możesz jeszcze bardziej ulepszyć funkcje swojej aplikacji do konwersji. Jedną z funkcji może być utworzenie pliku wyjściowego tylko do odczytu w celu zwiększenia bezpieczeństwa. Interfejs API umożliwia ustawienie pliku XAML w trybie tylko do odczytu, co oznacza, że użytkownicy (po otwarciu prezentacji) widzą zalecenie tylko do odczytu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku EPUB w XAML programowo: przypadki użycia" %}}
Przekonwertowanie plików EPUB na formaty XAML jest niezbędne do wykorzystania pełnego potencjalu swoich wizualizacji. Ten proces umożliwia wykorzystanie możliwości analizy i wizualizacji swoich danych.

**Przykłady użycia:**

* **Tworzenie interaktywnych interfejsów użytkowników dla aplikacji mobilnych**: Przekonwertuj pliki EPUB na interaktywne i dynamiczne interfejsy użytkowników dla aplikacji mobilnych, co pozwoli na łatwe nawigowanie i wyjątkowe doznania.

* **Rozwożenie treningu online**: Wykorzystaj format XAML do tworzenia atrakcyjnego treningu online, takiego jak interaktywne symulacje, quizy i oceny, co poprawi przetworzenie wiedzy i rozwój umiejętności.

* **Wizualizacja danych medycznych**: Przekonwertuj pliki EPUB na format XAML aby vizualizować dane z medycznego zobrazienia, takie jak MRI i rezony CT, co ułatwi diagnosis i planowanie leczenia.

* **Wizualizacja geoprzestrznych danych**: Wykorzystaj format XAML do tworzenia interaktywnych wizualizacji geoprzestrznych, takich jak mapy, zdjęcia satelitarna oraz trójwymiarowe modele, co poprawi rozumienie skomplikowanych danych przestrznych.

* **Opowieści oparte na danych**: Przekonwertuj pliki EPUB na format XAML aby stworzyć opowieści oparte na danych z interaktywnymi diagramami, wykresami i informacjami przemienne, co zwiększy zaangażenie i rozumienie przez odbiorcę.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}