---
title: Eksportuj CGM do OTP przez C# API
description: .NET API do konwersji CGM na OTP bez użycia Microsoft Word
url_ignore: /pl/net/conversion/cgm-to-otp/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: OTP
otherformats: PPSX SWF POTM PPSM PPTM POTX OTP PPT POT XAML POWERPOINT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj CGM do OTP przez .NET" h2=".NET API do eksportowania CGM do OTP w systemach Windows, macOS i Linux bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Korzystając z pakietu zaawansowanych interfejsów API automatyzacji formatowania plików [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo renderować CGM do OTP w dwóch prostych krokach. Korzystając z interfejsu API przetwarzania plików PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz przekształcić format pliku CGM na PPTX. Następnie, korzystając z interfejsu API do przetwarzania prezentacji [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), możesz przekonwertować PPTX na OTP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji CGM na OTP" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj CGM na PPTX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Zapisz dokument w formacie OTP za pomocą metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) i ustaw `Otp` jako SaveFormat
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
Podczas konwersji CGM na OTP możesz potrzebować dodatkowych informacji o metadanych XMP, aby nadać priorytet procesowi konwersji wsadowej. Na przykład możesz pobrać i posortować dokumenty konwersji na podstawie daty utworzenia i otpowiednio je przetworzyć. [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/) umożliwia dostęp do metadanych XMP pliku CGM. Aby uzyskać metadane pliku CGM, możesz utworzyć obiekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć wejściowy plik CGM. Następnie możesz pobrać metadane pliku za pomocą właściwości [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik OTP tylko do odczytu przez .NET" %}}
Korzystając z interfejsu API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) możesz jeszcze bardziej ulepszyć funkcje swojej aplikacji do konwersji. Jedną z funkcji może być utworzenie pliku wyjściowego tylko do odczytu w celu zwiększenia bezpieczeństwa. Interfejs API umożliwia ustawienie pliku OTP w trybie tylko do odczytu, co oznacza, że użytkownicy (po otwarciu prezentacji) widzą zalecenie tylko do odczytu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.otp", SaveFormat.Otp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku CGM w OTP programowo: przypadki użycia" %}}
Plik CGM (Computer Graphics Metafile) jest używany do zapisywania informacji o danych wektorowych grafik, czyniąc go idealnym dla tworzenia statycznych grafik i ilustracji. Jednak przy pracy z dynamickými danymi Excel staje się niezbędne do wizualizacji i analizy danych.

Przekonwertowanie plików CGM na formaty OTP (Object Transfer Protocol) pozwala wykorzystać pełną funkcjonalność swoich możliwości w zakresie wizualizacji i analizy danych. Ta konwersja umożliwia:

**Użytki:**

*   **Dynamiczne renderowanie grafik**: Przekonwertować pliki CGM na potrzeby renderowania dynamických grafik, simulacji czasu rzeczywistego oraz tworzenia interaktywnych doświadczeń.  
*   **Wizualizacja danych w czasie rzeczywistym**: Wykorzystać format OTP do wizualizacji skomplikowanych danych w czasie rzeczywistym, co poprawia świadomość decyzyjną i umożliwia szybką akcję.  
*   **Aplikacje internetowe**: Przekonwertować pliki CGM na potrzeby tworzenia aplikacji internetowych, zapewnejąc bezpośrednią interaktywną przepowiedź dla użytkownika.  
*   **Trening modeli szkolnictwa maszynowego**: Wykorzystać format OTP do szkolenia modeli machine learning na danych wektorowych grafik, poprawiając dokładność i wydajność modeli.  
*   **Systemy opartione na sztucznej inteligencji**: Przekonwertować pliki CGM na potrzeby obsługi systemów opartionych na sztucznej inteligencji, umożliwiając zaawansowaną analizę danych.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}