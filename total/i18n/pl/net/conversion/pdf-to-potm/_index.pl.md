---
title: Eksportuj PDF do POTM przez C# API
description: .NET API do konwersji PDF na POTM bez użycia Microsoft Word
url: /pl/net/conversion/pdf-to-potm/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: POTM
otherformats: OTP POWERPOINT POTM PPT PPSM PPSX POTX XAML SWF POT PPTM PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj PDF do POTM przez .NET" h2=".NET API do eksportowania PDF do POTM w systemach Windows, macOS i Linux bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Korzystając z pakietu zaawansowanych interfejsów API automatyzacji formatowania plików [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo renderować PDF do POTM w dwóch prostych krokach. Korzystając z interfejsu API przetwarzania plików PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz przekształcić format pliku PDF na PPTX. Następnie, korzystając z interfejsu API do przetwarzania prezentacji [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), możesz przekonwertować PPTX na POTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji PDF na POTM" %}}
1. Otwórz plik PDF za pomocą klasy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj PDF na PPTX za pomocą metody [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik PPTX za pomocą klasy [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Zapisz dokument w formacie POTM za pomocą metody [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) i ustaw `Potm` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.pdf");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.potm", SaveFormat.Potm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Uzyskaj metadane XMP z pliku PDF przez .NET" %}}
Podczas konwersji PDF na POTM możesz potrzebować dodatkowych informacji o metadanych XMP, aby nadać priorytet procesowi konwersji wsadowej. Na przykład możesz pobrać i posortować dokumenty konwersji na podstawie daty utworzenia i potmowiednio je przetworzyć. [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/) umożliwia dostęp do metadanych XMP pliku PDF. Aby uzyskać metadane pliku PDF, możesz utworzyć obiekt [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć wejściowy plik PDF. Następnie możesz pobrać metadane pliku za pomocą właściwości [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
```cs

Document doc = new Document("input.pdf");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik POTM tylko do odczytu przez .NET" %}}
Korzystając z interfejsu API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) możesz jeszcze bardziej ulepszyć funkcje swojej aplikacji do konwersji. Jedną z funkcji może być utworzenie pliku wyjściowego tylko do odczytu w celu zwiększenia bezpieczeństwa. Interfejs API umożliwia ustawienie pliku POTM w trybie tylko do odczytu, co oznacza, że użytkownicy (po otwarciu prezentacji) widzą zalecenie tylko do odczytu. 
```cs
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potm", SaveFormat.Potm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-pot/" name="PDF W celu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-ppsx/" name="PDF W celu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-swf/" name="PDF W celu SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-powerpoint/" name="PDF W celu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-otp/" name="PDF W celu OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-potm/" name="PDF W celu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-ppt/" name="PDF W celu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-pps/" name="PDF W celu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-potx/" name="PDF W celu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-xaml/" name="PDF W celu XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-ppsm/" name="PDF W celu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pdf-to-pptm/" name="PDF W celu PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}