---
title: Eksportuj CGM do PPSX przez C# API
description: .NET API do konwersji CGM na PPSX bez użycia Microsoft Word
url_ignore: /pl/net/conversion/cgm-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPSX
otherformats: PPT POWERPOINT POTX POTM PPS SWF PPSM PPTM XAML OTP POT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj CGM do PPSX przez .NET" h2=".NET API do eksportowania CGM do PPSX w systemach Windows, macOS i Linux bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Korzystając z pakietu zaawansowanych interfejsów API automatyzacji formatowania plików [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo renderować CGM do PPSX w dwóch prostych krokach. Korzystając z interfejsu API przetwarzania plików PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz przekształcić format pliku CGM na PPTX. Następnie, korzystając z interfejsu API do przetwarzania prezentacji [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), możesz przekonwertować PPTX na PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji CGM na PPSX" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj CGM na PPTX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Zapisz dokument w formacie PPSX za pomocą metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) i ustaw `Ppsx` jako SaveFormat
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
Podczas konwersji CGM na PPSX możesz potrzebować dodatkowych informacji o metadanych XMP, aby nadać priorytet procesowi konwersji wsadowej. Na przykład możesz pobrać i posortować dokumenty konwersji na podstawie daty utworzenia i ppsxowiednio je przetworzyć. [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/) umożliwia dostęp do metadanych XMP pliku CGM. Aby uzyskać metadane pliku CGM, możesz utworzyć obiekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć wejściowy plik CGM. Następnie możesz pobrać metadane pliku za pomocą właściwości [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku CGM w PPSX programowo: przypadki użycia" %}}
Przekształcenie plików CGM (Computer Graphics Metafile) na format PPSX (Plik XML prezentacji Microsoft PowerPoint) pozwala wykorzystać pełną potęgę możliwości wizualizacji i analiza danych Twoich danych prezentacji. Ten przekształcenie jest konieczne, aby skorzystać z mocnych funkcji interaktywnych PowerPoint, takich jak animacje, przejścia i zawartość multimedialna.

Przekształcenie plików CGM na format PPSX otwiera różne możliwości:

**Użycia:**

*   **Projektowanie i rozwój prezentacji**: Przekształć pliki CGM na format PPSX, aby stworzyć przepiękne prezentacje, symulacje i interaktywne wizualizacje, które przyciągną uwagę widowni.
*   **Opowiadanie opartych na danych**: Skorzystać z PPSX, aby integrować skomplikowane dane w prezentację i efektywnie przekazać swoją wiadomość poprzez opowiadanie i wizualizację.
*   **Korporacyjne komunikacje i raportowanie**: Przekształcić pliki CGM na format PPSX, aby stworzyć profesjonalne raporty, dashboardy i wizualizacje dla interesujących stron, co ułatwi decision-making.
*   **Kampanie marketingowe i reklamowe**: Wykorzystać możliwości multimedialnej zawartości PPSX, aby dopieroć dynamiczny treści, animacje i filmy w prezentację marketingową i reklamową.
*   **Akademia i badania**: Skorzystać z PPSX, aby stworzyć profesjonalne prezentacje badawcze, które zawierają skomplikowane wizualizacje danych, symulacje i elementy multimedialne.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}