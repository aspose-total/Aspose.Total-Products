---
title: Eksportuj MD do ODP przez C# API
description: .NET API do konwersji MD na ODP bez użycia Microsoft Word
url_ignore: /pl/net/conversion/md-to-odp/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: ODP
otherformats: XAML SWF POT PPTM PPSX POTM PPS PPT POTX OTP POWERPOINT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj MD do ODP przez .NET" h2=".NET API do eksportowania MD do ODP w systemach Windows, macOS i Linux bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Korzystając z pakietu zaawansowanych interfejsów API automatyzacji formatowania plików [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo renderować MD do ODP w dwóch prostych krokach. Korzystając z interfejsu API przetwarzania plików PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz przekształcić format pliku MD na PPTX. Następnie, korzystając z interfejsu API do przetwarzania prezentacji [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), możesz przekonwertować PPTX na ODP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji MD na ODP" %}}
1. Otwórz plik MD za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj MD na PPTX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Zapisz dokument w formacie ODP za pomocą metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) i ustaw `Odp` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj metadane XMP z pliku MD przez .NET" %}}
Podczas konwersji MD na ODP możesz potrzebować dodatkowych informacji o metadanych XMP, aby nadać priorytet procesowi konwersji wsadowej. Na przykład możesz pobrać i posortować dokumenty konwersji na podstawie daty utworzenia i odpowiednio je przetworzyć. [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/) umożliwia dostęp do metadanych XMP pliku MD. Aby uzyskać metadane pliku MD, możesz utworzyć obiekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć wejściowy plik MD. Następnie możesz pobrać metadane pliku za pomocą właściwości [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku MD w ODP programowo: przypadki użycia" %}}
Plików Markdown (MD) używają do zapisywania treści, czyniąc ich idealnymi dla tworzenia dokumentacji i zawartości. Jednak podczas pracy z wymiennymi i wymaganiami w zakresie układu i prezentacji ODP (OpenDocument Presentation) formaty stają się niezbędne do tworzenia atrakcyjnych pokazów i prezentacji wizualnych.

Przekształcenie plików MD na formaty ODP jest konieczne, aby wykorzystać pełną możliwość Twoich umiejętności projektowania wizualnego. To przekształcenie pozwala Ci:

**Użycia przypadków:**

* **Prezentacje na konferencje**: Przekształć plik MD do formatu ODP, aby stworzyć zaangażujące prezentacje na konferencje z uwzględnieniem treści, zdjęć i multimediowych zawartości.
* **Materiały szkoleniowe**: Wykorzystać format ODP do wizualizacji materiałów szkoleniowych, takich jak skorowce kursów, przykłady lekcji i podręczniki.
* **Kommunikacja korporacyjna**: Przekształć plik MD na format ODP, aby stworzyć profesjonalnie wyglądające komunikaty wewnętrzne firmy, takie jak aktualności, dokumenty polityczne i książki pracownicze.
* **Źródła edukacyjne**: Wykorzystać format ODP do tworzenia atrakcyjnych źródeł edukacyjnych, takich jak podręczniki, książki pracy i materiały do kursów online.
* **Materiały marketingowe**: Przekształć plik MD na format ODP, aby stworzyć uwrażające oceniające materiały marketingowe, takie jak ulotki, plakaty i kartony sprzedaży.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}