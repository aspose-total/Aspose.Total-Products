---
title: Konwertuj XPS na EMZ przez Java
description: Eksportuj plik XPS do EMZ w swoich aplikacjach Java bez korzystania z aplikacji innych firm
url_ignore: /pl/java/conversion/xps-to-emz/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: EMZ
otherformats: DXF WMZ WMF PSD EMZ  SVGZ IMAGE JPEG2000 TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj XPS na EMZ przez Java" h2="Eksportuj plik XPS do EMZ w dowolnej aplikacji Java J2SE, J2EE, J2ME bez użycia Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować plik xps na obraz EMZ w Javie w dwóch prostych krokach. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), możesz wyeksportować XPS do JPEG. Następnie za pomocą interfejsu API przetwarzania obrazów [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) możesz renderować JPEG do EMZ. Oba interfejsy API są objęte pakietem [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eksportuj XPS do EMZ przez Javę" %}}
1. Otwórz plik XPS za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Zainicjuj obiekt klasy i wyrenderuj XPS do formatu JPEG przy użyciu [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metoda
3. Załaduj plik JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Zapisz dokument w formacie EMZ za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj XPS na EMZ w jednym pliku za pomocą Javy" %}}
API pozwala również na eksport pliku XPS do EMZ do pojedynczego pliku. Aby przekonwertować wszystkie strony, możesz najpierw wyrenderować dokument XPS do jednego pliku TIFF, a następnie wyeksportować plik TIFF do EMZ. Możesz otworzyć plik wejściowy za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i utworzyć obiekty urządzeń Resolution, TiffSettings i TIFF. Możesz uzyskać pojedynczy obraz TIFF za pomocą [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metoda klasy [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Na koniec możesz załadować plik TIFF za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i zapisać go w formacie EMZ za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj XPS na EMZ za pomocą znaku wodnego za pomocą Javy" %}}
Korzystając z API, możesz również wyeksportować plik XPS do EMZ ze znakiem wodnym w swoim dokumencie EMZ. Aby dodać do niego znak wodny, możesz najpierw przekonwertować XPS na JPEG i dodać do niego znak wodny. Aby dodać znak wodny, załaduj plik obrazu za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), utwórz obiekt klasy [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) i zainicjuj ją obiektem Image, utwórz nowy [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) i ustaw translację i transformację pod żądanym kątem oraz dodaj znak wodny za pomocą [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po dodaniu znaku wodnego do obrazu możesz zapisać plik JPEG w formacie EMZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj i obracaj XPS do pliku EMZ za pomocą Java" %}}
Korzystając z interfejsu API, możesz również obracać wyjściowy obraz EMZ zgodnie z własnymi potrzebami. Metoda Image.rotateFlip może służyć do obracania obrazu o 90/180/270 stopni i odwracania obrazu w poziomie lub w pionie. Biblioteka zapewnia proste metody wykonywania złożonych operacji, jednocześnie hermetyzując wszystkie brzydkie szczegóły. Możesz określić typ obracania i odwracania, który ma być zastosowany do obrazu. Aby obrócić i odwrócić obraz, możesz załadować przekonwertowany obraz JPEG za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i wywołać obraz. metodę rotateFlip z określeniem odpowiedniego [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Konwertowanie plików XPS na **EMZ (skompresowany metaplik Windows)** pozwala na efektywne osadzanie wizualizacji dokumentów w prezentacjach, raportach lub aplikacjach komputerowych, zachowując przy tym klarowność wektorów.



{{% blocks/products/pf/agp/feature-section-col title="Główne przypadki użycia" %}}



* Osadzanie grafik wysokiej jakości w prezentacjach Microsoft Office.

* Udostępnianie diagramów technicznych i architektonicznych.

* Ilustrowanie dokumentacji oprogramowania za pomocą skompresowanych plików.

* Moduły e-learningowe z precyzyjnymi wizualizacjami wektorowymi.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze automatyzacji" %}}



* Konwersja XPS na EMZ wsadowo dla bibliotek zasobów.

* Integracja z automatyzowanymi procesami dokumentacyjnymi.

* Harmonogramowa generacja plików EMZ do cyklicznych raportów technicznych.

* Uproszczone przetwarzanie grafiki dla gotowych do prezentacji wizualizacji.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}