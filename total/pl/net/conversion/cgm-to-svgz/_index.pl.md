---
title: Konwertuj CGM na SVGZ przez C# API
description: Eksportuj CGM do SVGZ w swoich aplikacjach .NET bez korzystania z aplikacji innych firm
url_ignore: /pl/net/conversion/cgm-to-svgz/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SVGZ
otherformats: TGA JPEG2000 IMAGE SVGZ WMF  WMZ PSD EMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj plik CGM na SVGZ za pomocą C#" h2="Eksportuj CGM do SVGZ w aplikacjach .NET bez użycia programu Adobe<sup>&reg;</sup> Acrobat Reader lub innych aplikacji innych firm" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo wyeksportować CGM do obrazu SVGZ w dowolnej aplikacji .NET w dwóch prostych krokach. Po pierwsze, używając [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz wyeksportować CGM do JPEG. Następnie za pomocą interfejsu API przetwarzania obrazów [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) możesz przekonwertować JPEG na SVGZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj plik CGM na SVGZ przez .NET" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Zainicjuj obiekt klasy [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) i wyrenderuj CGM do JPEG przy użyciu [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metoda
3. Załaduj plik JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Zapisz dokument w formacie SVGZ metodą [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj plik CGM na SVGZ w jednym pliku za pomocą C#" %}}
Korzystając z API, możesz również przekonwertować plik CGM na SVGZ do pojedynczego pliku obrazu. Aby przekonwertować wszystkie strony, możesz najpierw wyrenderować swój dokument CGM do jednego pliku TIFF, a następnie wyeksportować plik TIFF do SVGZ. Możesz otworzyć plik wejściowy za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i utworzyć obiekty urządzeń Resolution, TiffSettings i TIFF. Możesz uzyskać pojedynczy obraz TIFF za pomocą metody [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Na koniec możesz załadować plik TIFF przy użyciu klasy [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
i zapisz go w formacie SVGZ za pomocą metody [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj i obróć plik CGM do SVGZ za pomocą C#" %}}
Korzystając z interfejsu API, możesz również obracać wyjściowy obraz SVGZ zgodnie z własnymi potrzebami. Metoda Image.RotateFlip może służyć do obracania obrazu o 90/180/270 stopni i odwracania obrazu w poziomie lub w pionie. Możesz określić typ obracania i odwracania, który ma być zastosowany do obrazu. Aby obrócić i odwrócić obraz, możesz załadować przekonwertowany obraz JPEG przy użyciu metody fabrycznej ujawnionej przez klasę [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) i wywołać Image Metoda .RotateFlip z określeniem odpowiedniego [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku CGM w SVGZ programowo: przypadki użycia" %}}
Pliki CGM (Computer Graphics Metafile) są używane do przechowania informacji o wektorowych grafikach, czyniąc je idealnymi dla tworzenia statycznych grafik i ilustracji. Jednak przy pracowaniu z dynamicznymi danymi, takimi jak arkusze Excel, staje się niezbędne do wizualizacji i analizy danych.

Przekonwertowanie plików CGM na format SVGZ pozwala wykorzystać pełną możliwość swoich umiejętności w zakresie tworzenia wektorowych grafik i ilustracji. To przekonwertowanie umożliwia:

**Użycia:**

* **Tworzenie statycznych grafik**: Przekonwertować pliki CGM na wysokiej jakości statyczne grafiki, ilustracje oraz logi przeznaczone dla druku lub wykorzystania w Internecie.  
* **Projektowanie marki i identyfikacji**: Wykorzystać SVGZ do tworzenia identyfikacji marek, ikon i grafik skalowalnych, które zachowują swoją jakość przy zmianie rozmiaru.  
* **Projektowanie etykietek i opakowania**: Przekonwertować pliki CGM na wyglądnące atrakcyjnie etykietki i projekty opakowania, które wyróżniają się na płyktach sklepu.  
* **Zarządzanie cyfrowymi zasobami**: Przechowywać pliki CGM w formacie SVGZ dla wygodnego zarządzania cyfrowymi zasobami i łatwego udostępniania i przekazywania między zespołami.  
* **Optymalizacja grafik dla przeglądarków i urządzeń mobilnych**: Wykorzystać SVGZ do optymalizacji plików CGM dla przeglądarków i urządzeń mobilnych, zapewnejąc szybkie ładowanie i wysokiej jakości wygląd.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}