---
title: Konwertuj TEX na WMZ przez Java
description: Eksportuj plik TEX do WMZ w swoich aplikacjach Java bez korzystania z aplikacji innych firm
url_ignore: /pl/java/conversion/tex-to-wmz/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: WMZ
otherformats: WMZ  TGA WMF IMAGE DXF JPEG2000 PSD EMZ SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj TEX na WMZ przez Java" h2="Eksportuj plik TEX do WMZ w dowolnej aplikacji Java J2SE, J2EE, J2ME bez użycia Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować plik tex na obraz WMZ w Javie w dwóch prostych krokach. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), możesz wyeksportować TEX do JPEG. Następnie za pomocą interfejsu API przetwarzania obrazów [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) możesz renderować JPEG do WMZ. Oba interfejsy API są objęte pakietem [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eksportuj TEX do WMZ przez Javę" %}}
1. Otwórz plik TEX za pomocą klasy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Zainicjuj obiekt klasy i wyrenderuj TEX do formatu JPEG przy użyciu [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metoda
3. Załaduj plik JPEG przy użyciu klasy [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Zapisz dokument w formacie WMZ za pomocą [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj TEX na WMZ w jednym pliku za pomocą Javy" %}}
API pozwala również na eksport pliku TEX do WMZ do pojedynczego pliku. Aby przekonwertować wszystkie strony, możesz najpierw wyrenderować dokument TEX do jednego pliku TIFF, a następnie wyeksportować plik TIFF do WMZ. Możesz otworzyć plik wejściowy za pomocą klasy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) i utworzyć obiekty urządzeń Resolution, TiffSettings i TIFF. Możesz uzyskać pojedynczy obraz TIFF za pomocą [process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metoda klasy [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Na koniec możesz załadować plik TIFF za pomocą klasy [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) i zapisać go w formacie WMZ za pomocą [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj TEX na WMZ za pomocą znaku wodnego za pomocą Javy" %}}
Korzystając z API, możesz również wyeksportować plik TEX do WMZ ze znakiem wodnym w swoim dokumencie WMZ. Aby dodać do niego znak wodny, możesz najpierw przekonwertować TEX na JPEG i dodać do niego znak wodny. Aby dodać znak wodny, załaduj plik obrazu za pomocą klasy [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), utwórz obiekt klasy [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) i zainicjuj ją obiektem Image, utwórz nowy [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) i ustaw translację i transformację pod żądanym kątem oraz dodaj znak wodny za pomocą [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po dodaniu znaku wodnego do obrazu możesz zapisać plik JPEG w formacie WMZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj i obracaj TEX do pliku WMZ za pomocą Java" %}}
Korzystając z interfejsu API, możesz również obracać wyjściowy obraz WMZ zgodnie z własnymi potrzebami. Metoda Image.rotateFlip może służyć do obracania obrazu o 90/180/270 stopni i odwracania obrazu w poziomie lub w pionie. Biblioteka zapewnia proste metody wykonywania złożonych operacji, jednocześnie hermetyzując wszystkie brzydkie szczegóły. Możesz określić typ obracania i odwracania, który ma być zastosowany do obrazu. Aby obrócić i odwrócić obraz, możesz załadować przekonwertowany obraz JPEG za pomocą klasy [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) i wywołać obraz. metodę rotateFlip z określeniem odpowiedniego [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/tex-to-emz/" name="TEX W celu EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/tex-to-tga/" name="TEX W celu TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/tex-to-jpeg2000/" name="TEX W celu JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/tex-to-image/" name="TEX W celu IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/tex-to-psd/" name="TEX W celu PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/tex-to-wmz/" name="TEX W celu WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/tex-to-svgz/" name="TEX W celu SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/tex-to/" name="TEX W celu" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/tex-to-wmf/" name="TEX W celu WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/tex-to-dxf/" name="TEX W celu DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/tex-to-dicom/" name="TEX W celu DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}