---
title: Konwertuj CGM na WMF przez C# API
description: Eksportuj CGM do WMF w swoich aplikacjach .NET bez korzystania z aplikacji innych firm
url_ignore: /pl/net/conversion/cgm-to-wmf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: WMF
otherformats: EMZ SVGZ WMF TGA JPEG2000 DXF  PSD WMZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj plik CGM na WMF za pomocą C#" h2="Eksportuj CGM do WMF w aplikacjach .NET bez użycia programu Adobe<sup>&reg;</sup> Acrobat Reader lub innych aplikacji innych firm" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo wyeksportować CGM do obrazu WMF w dowolnej aplikacji .NET w dwóch prostych krokach. Po pierwsze, używając [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz wyeksportować CGM do JPEG. Następnie za pomocą interfejsu API przetwarzania obrazów [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) możesz przekonwertować JPEG na WMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj plik CGM na WMF przez .NET" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Zainicjuj obiekt klasy [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) i wyrenderuj CGM do JPEG przy użyciu [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metoda
3. Załaduj plik JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Zapisz dokument w formacie WMF metodą [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj plik CGM na WMF w jednym pliku za pomocą C#" %}}
Korzystając z API, możesz również przekonwertować plik CGM na WMF do pojedynczego pliku obrazu. Aby przekonwertować wszystkie strony, możesz najpierw wyrenderować swój dokument CGM do jednego pliku TIFF, a następnie wyeksportować plik TIFF do WMF. Możesz otworzyć plik wejściowy za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i utworzyć obiekty urządzeń Resolution, TiffSettings i TIFF. Możesz uzyskać pojedynczy obraz TIFF za pomocą metody [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Na koniec możesz załadować plik TIFF przy użyciu klasy [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
i zapisz go w formacie WMF za pomocą metody [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj i obróć plik CGM do WMF za pomocą C#" %}}
Korzystając z interfejsu API, możesz również obracać wyjściowy obraz WMF zgodnie z własnymi potrzebami. Metoda Image.RotateFlip może służyć do obracania obrazu o 90/180/270 stopni i odwracania obrazu w poziomie lub w pionie. Możesz określić typ obracania i odwracania, który ma być zastosowany do obrazu. Aby obrócić i odwrócić obraz, możesz załadować przekonwertowany obraz JPEG przy użyciu metody fabrycznej ujawnionej przez klasę [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) i wywołać Image Metoda .RotateFlip z określeniem odpowiedniego [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku CGM w WMF programowo: przypadki użycia" %}}
Przekonwertowanie plików CGM na formaty WMF jest niezbędne dla wykorzystania pełnego potencjału swoich projektów graficznych i wizualizacji.

Ten proces umożliwia:

**Użytki:**

*   **Projekty graficzne i ilustracje**: Przekonwertowanie plików CGM na format WMF pozwala tworzyć skomplikowane i szczególne grafiki, ilustracje oraz logotypy, które są idealnie nadają się do użytku w różnych mediach.
*   **Wizualizacje architektoniczne**: Wykorzystanie formatu WMF umożliwia wizualizację tridimensionsalnych modeli, projektów budowlowych oraz planów architektonicznych, co ułatwia współpracę i komunikację z klientami i interesariuszami.
*   **Rysunki techniczne i CAD**: Przekonwertowanie plików CGM na format WMF pozwala tworzyć techniczne rysunki, blueprints oraz projekty CAD, które są istotne dla rozwoju produktów, produkcji oraz inżynierii.
*   **Wyrażenia artystyczne**: Wykorzystanie formatu WMF umożliwia tworzenie skomplikowanych i szczególnych wyrażeń artystycznych, takich jak grafiki, ikony oraz logotypy, co pokazuje Twój talent i kreatywność.
*   **Widzę cyfrową i ekranów**: Przekonwertowanie plików CGM na format WMF pozwala tworzyć dynamiczne i interaktywne wyświetlania na ekranach cyfrowych, które przyciągają uwagę widzów i skutecznie przekazują komunikaty.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}