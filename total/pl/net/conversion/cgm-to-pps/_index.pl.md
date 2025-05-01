---
title: Eksportuj CGM do PPS przez C# API
description: .NET API do konwersji CGM na PPS bez użycia Microsoft Word
url_ignore: /pl/net/conversion/cgm-to-pps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPS
otherformats: PPSM PPS PPTM POWERPOINT PPT PPSX XAML POTM POTX SWF OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj CGM do PPS przez .NET" h2=".NET API do eksportowania CGM do PPS w systemach Windows, macOS i Linux bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Korzystając z pakietu zaawansowanych interfejsów API automatyzacji formatowania plików [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo renderować CGM do PPS w dwóch prostych krokach. Korzystając z interfejsu API przetwarzania plików PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz przekształcić format pliku CGM na PPTX. Następnie, korzystając z interfejsu API do przetwarzania prezentacji [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), możesz przekonwertować PPTX na PPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji CGM na PPS" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj CGM na PPTX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Zapisz dokument w formacie PPS za pomocą metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) i ustaw `Pps` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj metadane XMP z pliku CGM przez .NET" %}}
Podczas konwersji CGM na PPS możesz potrzebować dodatkowych informacji o metadanych XMP, aby nadać priorytet procesowi konwersji wsadowej. Na przykład możesz pobrać i posortować dokumenty konwersji na podstawie daty utworzenia i ppsowiednio je przetworzyć. [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/) umożliwia dostęp do metadanych XMP pliku CGM. Aby uzyskać metadane pliku CGM, możesz utworzyć obiekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć wejściowy plik CGM. Następnie możesz pobrać metadane pliku za pomocą właściwości [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik PPS tylko do odczytu przez .NET" %}}
Korzystając z interfejsu API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) możesz jeszcze bardziej ulepszyć funkcje swojej aplikacji do konwersji. Jedną z funkcji może być utworzenie pliku wyjściowego tylko do odczytu w celu zwiększenia bezpieczeństwa. Interfejs API umożliwia ustawienie pliku PPS w trybie tylko do odczytu, co oznacza, że użytkownicy (po otwarciu prezentacji) widzą zalecenie tylko do odczytu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pps", SaveFormat.Pps);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku CGM w PPS programowo: przypadki użycia" %}}
Pliki CGM (Computer Graphics Metafile) są używane do przechowania informacji o układach graficznych wektorowych, co czyni je idealnymi dla tworzenia statycznych grafik i ilustracji. Jednak gdy pracujemy z dynamicznymi danymi, takimi jak arkusze Excel, stają się one niezbędne do wizualizacji danych i analizy.

Przekonwertowanie plików CGM na format PPS (Portable Presentation) pozwala wykorzystać pełną potęgę Twoich prezentacji i wizualizacji. Ta konwersja umożliwia:

**Użycia:**

*   **Projektowanie prezentacji**: Przekonwertować pliki CGM na profesjonalnie wyglądające slajdy, animacje oraz przejścię dla przypomnienia widownego publiczności.
*   **Wiedza i nauka**: Wykorzystać PPS do tworzenia interaktywnych materiałów szkoleniowych, symulacji i poradników, które poprawiają efekty uczenia.
*   **Marketing i sprzedaż**: Przekonwertować pliki CGM na przekąsające materiały reklamowe, demaupy produktów oraz materiały marketingowe.
*   **Kommunikacja korporacyjna**: Wykorzystać PPS do tworzenia komunikatów wewnętrznych, raportów i infografik dla lepszego udostępniania informacji.
*   **Wizualizacje wydarzeń i wystaw**: Przekonwertować pliki CGM na wyglądające oczywistych grafiki wydarzeń, projekty ekspozycji oraz panele targowe.

Przekonwertowanie Twoich plików CGM na format PPS pozwala wykorzystać najnowsze funkcje prezentacji software'u, takie jak zaawansowane animacje, przejścię oraz efekty. Ta konwersja zapewni, że Twój zawartość wizualna będzie pokazywana w swoim najlepszym kształcie, czyniącą ją niezbędną krokną dla wszelkich projektów wymagających profesjonalnych prezentacji.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}