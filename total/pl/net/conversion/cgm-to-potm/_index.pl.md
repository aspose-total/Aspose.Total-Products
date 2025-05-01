---
title: Eksportuj CGM do POTM przez C# API
description: .NET API do konwersji CGM na POTM bez użycia Microsoft Word
url_ignore: /pl/net/conversion/cgm-to-potm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POTM
otherformats: POWERPOINT PPSX SWF POT POTX PPSM PPTM PPS PPT OTP XAML POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj CGM do POTM przez .NET" h2=".NET API do eksportowania CGM do POTM w systemach Windows, macOS i Linux bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Korzystając z pakietu zaawansowanych interfejsów API automatyzacji formatowania plików [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo renderować CGM do POTM w dwóch prostych krokach. Korzystając z interfejsu API przetwarzania plików PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz przekształcić format pliku CGM na PPTX. Następnie, korzystając z interfejsu API do przetwarzania prezentacji [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), możesz przekonwertować PPTX na POTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji CGM na POTM" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj CGM na PPTX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Zapisz dokument w formacie POTM za pomocą metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) i ustaw `Potm` jako SaveFormat
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
Podczas konwersji CGM na POTM możesz potrzebować dodatkowych informacji o metadanych XMP, aby nadać priorytet procesowi konwersji wsadowej. Na przykład możesz pobrać i posortować dokumenty konwersji na podstawie daty utworzenia i potmowiednio je przetworzyć. [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/) umożliwia dostęp do metadanych XMP pliku CGM. Aby uzyskać metadane pliku CGM, możesz utworzyć obiekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć wejściowy plik CGM. Następnie możesz pobrać metadane pliku za pomocą właściwości [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik POTM tylko do odczytu przez .NET" %}}
Korzystając z interfejsu API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) możesz jeszcze bardziej ulepszyć funkcje swojej aplikacji do konwersji. Jedną z funkcji może być utworzenie pliku wyjściowego tylko do odczytu w celu zwiększenia bezpieczeństwa. Interfejs API umożliwia ustawienie pliku POTM w trybie tylko do odczytu, co oznacza, że użytkownicy (po otwarciu prezentacji) widzą zalecenie tylko do odczytu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potm", SaveFormat.Potm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku CGM w POTM programowo: przypadki użycia" %}}
Przekonwertowanie plików CGM na format POTM (pliki szablonów Microsoft Office) pozwala wykorzystać pełną potęgę możliwości projektowania układu i elementów prezentacji.  

**Użycia:**

* **Zgodność wizerunku firmy**: Przekonwertowanie plików CGM na format POTM umożliwia utrzymanie spójności wizualnej firmy w prezentacjach, zapewniając że wszystkie elementy wyświetlają się zgodnie ze świadomością firmy.  
* **Rozwożenie szablonów prezentacji**: Wykorzystanie formatu POTM pozwala tworzyć przykłady do użytku, które są łatwe do zmodyfikowania i wykorzystania podczas tworzenia treści prezentacji.  
* **Efektywność projektowania**: Konwersja plików CGM na format POTM ułatwia proces projektowania prezentacji, pozwaliając skoncentrować się na tworzeniu zawartości niż na monotonnych zadaniach formataowania.  
* **Współpracujące narzędzia**: Wykorzystanie formatu POTM umożliwia tworzenie narzędzi współpracy, które ułatwiają udostępnianie i wprowadzanie zmian w czasie rzeczywistym przez zespół.  
* **Standardaryzacja i przystosowanie do wymagań branżowych**: Konwersja plików CGM na format POTM pozwala utrzymanie standardów i dostosowania do potrzeb branży, zapewniając że wszystkie prezentacje spełniają określone wytyczki.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}