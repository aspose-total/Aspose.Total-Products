---
title: Konwertuj MHTML na DICOM przez Java
description: Eksportuj plik MHTML do DICOM w swoich aplikacjach Java bez korzystania z aplikacji innych firm
url_ignore: /pl/java/conversion/mhtml-to-dicom/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: DICOM
otherformats: EMZ TGA WMF IMAGE WMZ DICOM JPEG2000 DXF SVGZ PSD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj MHTML na DICOM przez Java" h2="Eksportuj plik MHTML do DICOM w dowolnej aplikacji Java J2SE, J2EE, J2ME bez użycia Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować plik mhtml na obraz DICOM w Javie w dwóch prostych krokach. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), możesz wyeksportować MHTML do JPEG. Następnie za pomocą interfejsu API przetwarzania obrazów [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) możesz renderować JPEG do DICOM. Oba interfejsy API są objęte pakietem [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eksportuj MHTML do DICOM przez Javę" %}}
1. Otwórz plik MHTML za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Zainicjuj obiekt klasy i wyrenderuj MHTML do formatu JPEG przy użyciu [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metoda
3. Załaduj plik JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Zapisz dokument w formacie DICOM za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj MHTML na DICOM w jednym pliku za pomocą Javy" %}}
API pozwala również na eksport pliku MHTML do DICOM do pojedynczego pliku. Aby przekonwertować wszystkie strony, możesz najpierw wyrenderować dokument MHTML do jednego pliku TIFF, a następnie wyeksportować plik TIFF do DICOM. Możesz otworzyć plik wejściowy za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i utworzyć obiekty urządzeń Resolution, TiffSettings i TIFF. Możesz uzyskać pojedynczy obraz TIFF za pomocą [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metoda klasy [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Na koniec możesz załadować plik TIFF za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i zapisać go w formacie DICOM za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj MHTML na DICOM za pomocą znaku wodnego za pomocą Javy" %}}
Korzystając z API, możesz również wyeksportować plik MHTML do DICOM ze znakiem wodnym w swoim dokumencie DICOM. Aby dodać do niego znak wodny, możesz najpierw przekonwertować MHTML na JPEG i dodać do niego znak wodny. Aby dodać znak wodny, załaduj plik obrazu za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), utwórz obiekt klasy [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) i zainicjuj ją obiektem Image, utwórz nowy [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) i ustaw translację i transformację pod żądanym kątem oraz dodaj znak wodny za pomocą [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po dodaniu znaku wodnego do obrazu możesz zapisać plik JPEG w formacie DICOM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj i obracaj MHTML do pliku DICOM za pomocą Java" %}}
Korzystając z interfejsu API, możesz również obracać wyjściowy obraz DICOM zgodnie z własnymi potrzebami. Metoda Image.rotateFlip może służyć do obracania obrazu o 90/180/270 stopni i odwracania obrazu w poziomie lub w pionie. Biblioteka zapewnia proste metody wykonywania złożonych operacji, jednocześnie hermetyzując wszystkie brzydkie szczegóły. Możesz określić typ obracania i odwracania, który ma być zastosowany do obrazu. Aby obrócić i odwrócić obraz, możesz załadować przekonwertowany obraz JPEG za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i wywołać obraz. metodę rotateFlip z określeniem odpowiedniego [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-emz/" name="MHTML W celu EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-tga/" name="MHTML W celu TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-jpeg2000/" name="MHTML W celu JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-image/" name="MHTML W celu IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-psd/" name="MHTML W celu PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-wmz/" name="MHTML W celu WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-svgz/" name="MHTML W celu SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to/" name="MHTML W celu" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-wmf/" name="MHTML W celu WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-dxf/" name="MHTML W celu DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/mhtml-to-dicom/" name="MHTML W celu DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}