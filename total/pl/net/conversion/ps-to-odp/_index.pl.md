---
title: Eksportuj PS do ODP przez C# API
description: .NET API do konwersji PS na ODP bez użycia Microsoft Word
url_ignore: /pl/net/conversion/ps-to-odp/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: ODP
otherformats: POTM XAML POTX PPSM PPSX POWERPOINT PPT POT PPTM OTP PPS SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj PS do ODP przez .NET" h2=".NET API do eksportowania PS do ODP w systemach Windows, macOS i Linux bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Korzystając z pakietu zaawansowanych interfejsów API automatyzacji formatowania plików [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo renderować PS do ODP w dwóch prostych krokach. Korzystając z interfejsu API przetwarzania plików PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz przekształcić format pliku PS na PPTX. Następnie, korzystając z interfejsu API do przetwarzania prezentacji [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), możesz przekonwertować PPTX na ODP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji PS na ODP" %}}
1. Otwórz plik PS za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj PS na PPTX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Zapisz dokument w formacie ODP za pomocą metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) i ustaw `Odp` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj metadane XMP z pliku PS przez .NET" %}}
Podczas konwersji PS na ODP możesz potrzebować dodatkowych informacji o metadanych XMP, aby nadać priorytet procesowi konwersji wsadowej. Na przykład możesz pobrać i posortować dokumenty konwersji na podstawie daty utworzenia i odpowiednio je przetworzyć. [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/) umożliwia dostęp do metadanych XMP pliku PS. Aby uzyskać metadane pliku PS, możesz utworzyć obiekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć wejściowy plik PS. Następnie możesz pobrać metadane pliku za pomocą właściwości [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik ODP tylko do odczytu przez .NET" %}}
Korzystając z interfejsu API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) możesz jeszcze bardziej ulepszyć funkcje swojej aplikacji do konwersji. Jedną z funkcji może być utworzenie pliku wyjściowego tylko do odczytu w celu zwiększenia bezpieczeństwa. Interfejs API umożliwia ustawienie pliku ODP w trybie tylko do odczytu, co oznacza, że użytkownicy (po otwarciu prezentacji) widzą zalecenie tylko do odczytu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.odp", SaveFormat.Odp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku PS w ODP programowo: przypadki użycia" %}}
Plików PDF (Portable Document Format) używają do zapisywania dokumentów o stałej konwencji, czyniąc ich idealnymi dla tworzenia publikacji i prezentacji. Jednak przy pracach z interaktywnymi wizualizacjami danych, takie tabelary jako Excel stają się niezbędne do analizy i raportowania.

Przekształcenie plików PDF na format Excel jest konieczne, aby wykorzystać pełną możliwość swoich umiejętności w zakresie wizualizacji danych i analizy. To przekształcenie pozwala Ci:

**Przypisy się do użytku:**

* **Analiza wyników sprzedaży**: Przekształć pliki PDF, aby analizować wyniki sprzedaży, śledzić kluczowe metryki i rozpoznawać trendy w danych.
* **Analiza badań rynkowych**: Wykorzystać Excel do wizualizacji danych badawczych z rynku, analizowania zachowania konsumentów i wyłapywania informacji o preferencjach klientów.
* **Dokumentacja produktu i obsługa**: Przekształć pliki PDF do tworzenia interaktywnych poradników produktowych, śledzenia historii obsługi i aktualizowania dokumentacji w sposób szybki.
* **Tworzenie treści edukacyjnych**: Wykorzystać Excel do tworzenia atrakcyjnej treści edukacyjnej, takiej jak interaktywne symulacje, quizy i oceny.
* **Podjęcie decyzji opartych na danych**: Przekształć pliki PDF do tworzenia interaktywnych raportów, dashboardów i wizualizacji dla interesantów, co umożliwi lepsze podejmowanie decyzji.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}