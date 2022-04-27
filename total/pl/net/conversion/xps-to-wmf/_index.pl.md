---
title: Konwertuj XPS na WMF przez C# API
description: Eksportuj XPS do WMF w swoich aplikacjach .NET bez korzystania z aplikacji innych firm
url: /pl/net/conversion/xps-to-wmf/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: WMF
otherformats: TGA EMZ PSD SVGZ JPEG2000 WMZ  WMF IMAGE DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj plik XPS na WMF za pomocą C#" h2="Eksportuj XPS do WMF w aplikacjach .NET bez użycia programu Adobe<sup>&reg;</sup> Acrobat Reader lub innych aplikacji innych firm" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo wyeksportować XPS do obrazu WMF w dowolnej aplikacji .NET w dwóch prostych krokach. Po pierwsze, używając [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz wyeksportować XPS do JPEG. Następnie za pomocą interfejsu API przetwarzania obrazów [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) możesz przekonwertować JPEG na WMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj plik XPS na WMF przez .NET" %}}
1. Otwórz plik XPS za pomocą klasy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Zainicjuj obiekt klasy [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) i wyrenderuj XPS do JPEG przy użyciu [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metoda
3. Załaduj plik JPEG przy użyciu klasy [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Zapisz dokument w formacie WMF metodą [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj plik XPS na WMF w jednym pliku za pomocą C#" %}}
Korzystając z API, możesz również przekonwertować plik XPS na WMF do pojedynczego pliku obrazu. Aby przekonwertować wszystkie strony, możesz najpierw wyrenderować swój dokument XPS do jednego pliku TIFF, a następnie wyeksportować plik TIFF do WMF. Możesz otworzyć plik wejściowy za pomocą klasy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) i utworzyć obiekty urządzeń Resolution, TiffSettings i TIFF. Możesz uzyskać pojedynczy obraz TIFF za pomocą metody [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) [TiffDevice](https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Na koniec możesz załadować plik TIFF przy użyciu klasy [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
i zapisz go w formacie WMF za pomocą metody [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj i obróć plik XPS do WMF za pomocą C#" %}}
Korzystając z interfejsu API, możesz również obracać wyjściowy obraz WMF zgodnie z własnymi potrzebami. Metoda Image.RotateFlip może służyć do obracania obrazu o 90/180/270 stopni i odwracania obrazu w poziomie lub w pionie. Możesz określić typ obracania i odwracania, który ma być zastosowany do obrazu. Aby obrócić i odwrócić obraz, możesz załadować przekonwertowany obraz JPEG przy użyciu metody fabrycznej ujawnionej przez klasę [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) i wywołać Image Metoda .RotateFlip z określeniem odpowiedniego [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-emz/" name="XPS W celu EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-tga/" name="XPS W celu TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-jpeg2000/" name="XPS W celu JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-image/" name="XPS W celu IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-psd/" name="XPS W celu PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-wmz/" name="XPS W celu WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-svgz/" name="XPS W celu SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to/" name="XPS W celu" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-wmf/" name="XPS W celu WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-dxf/" name="XPS W celu DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xps-to-dicom/" name="XPS W celu DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}