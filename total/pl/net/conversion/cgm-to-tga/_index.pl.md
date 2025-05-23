---
title: Konwertuj CGM na TGA przez C# API
description: Eksportuj CGM do TGA w swoich aplikacjach .NET bez korzystania z aplikacji innych firm
url_ignore: /pl/net/conversion/cgm-to-tga/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TGA
otherformats: EMZ TGA SVGZ IMAGE WMF  JPEG2000 WMZ DXF PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj plik CGM na TGA za pomocą C#" h2="Eksportuj CGM do TGA w aplikacjach .NET bez użycia programu Adobe<sup>&reg;</sup> Acrobat Reader lub innych aplikacji innych firm" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo wyeksportować CGM do obrazu TGA w dowolnej aplikacji .NET w dwóch prostych krokach. Po pierwsze, używając [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz wyeksportować CGM do JPEG. Następnie za pomocą interfejsu API przetwarzania obrazów [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) możesz przekonwertować JPEG na TGA.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj plik CGM na TGA przez .NET" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Zainicjuj obiekt klasy [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) i wyrenderuj CGM do JPEG przy użyciu [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metoda
3. Załaduj plik JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Zapisz dokument w formacie TGA metodą [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj plik CGM na TGA w jednym pliku za pomocą C#" %}}
Korzystając z API, możesz również przekonwertować plik CGM na TGA do pojedynczego pliku obrazu. Aby przekonwertować wszystkie strony, możesz najpierw wyrenderować swój dokument CGM do jednego pliku TIFF, a następnie wyeksportować plik TIFF do TGA. Możesz otworzyć plik wejściowy za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i utworzyć obiekty urządzeń Resolution, TiffSettings i TIFF. Możesz uzyskać pojedynczy obraz TIFF za pomocą metody [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Na koniec możesz załadować plik TIFF przy użyciu klasy [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
i zapisz go w formacie TGA za pomocą metody [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj i obróć plik CGM do TGA za pomocą C#" %}}
Korzystając z interfejsu API, możesz również obracać wyjściowy obraz TGA zgodnie z własnymi potrzebami. Metoda Image.RotateFlip może służyć do obracania obrazu o 90/180/270 stopni i odwracania obrazu w poziomie lub w pionie. Możesz określić typ obracania i odwracania, który ma być zastosowany do obrazu. Aby obrócić i odwrócić obraz, możesz załadować przekonwertowany obraz JPEG przy użyciu metody fabrycznej ujawnionej przez klasę [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) i wywołać Image Metoda .RotateFlip z określeniem odpowiedniego [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku CGM w TGA programowo: przypadki użycia" %}}
Przekształcanie plików CGM (Plik metafajłowy kompyuteryzacji grafiki) na formaty TGA (Plik obrazu Truevision TGA) otwiera nowe możliwości twórcze, czyniącymi ich idealnymi dla wielu zastosowanie. Jednak przy pracy z dynamickim zawartościem programy do edycji obrazów, takie jak GIMP oraz inne programy do edycji obrazów stają się niezbędne.

Przekształcanie plików CGM na formaty TGA jest niezbędne, aby rozwiązać problem pełnych możliwości Twoich umiejętności edycji. To pozwala Ci:

**Użycia:**

- **Edycja obrazu**: Przekształcanie plików CGM na format TGA pozwala na edycję obrazu, dostosowanie oświetlenia, kontrastu i nasilenia kolorów.
- **Projektowanie grafiki**: Użycie formatu TGA w projekcie graficznym umożliwia tworzenie i manipulację grafikami, logami, ikonami i innymi elementami wizualnymi.
- **Malowanie cyfrowe**: Przekształcanie plików CGM na format TGA pozwala na tworzenie wyjątkowych dzieł sztukowych z szerokim palettem kolorów i efektami specjalnymi.
- **Wizualizacja architektoniczna**: Użycie formatu TGA umożliwia wizualizację tridimensionalną modeł, tworząc prawdziwie realistyczne obrazy dla architektów, projektowników i budowniczych.
- **Analiza obrazu medycznego**: Przekształcanie plików CGM na format TGA pozwala na szczegółowe badania obrazu medycznego, obejmujące podzielenie się na organy, tkanki i komórki.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}