---
title: Konwertuj HTML na SVGZ przez Java
description: Eksportuj plik HTML do SVGZ w swoich aplikacjach Java bez korzystania z aplikacji innych firm
url_ignore: /pl/java/conversion/html-to-svgz/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: SVGZ
otherformats: EMZ JPEG2000 PSD WMF TGA IMAGE WMZ DXF SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj HTML na SVGZ przez Java" h2="Eksportuj plik HTML do SVGZ w dowolnej aplikacji Java J2SE, J2EE, J2ME bez użycia Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować plik html na obraz SVGZ w Javie w dwóch prostych krokach. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), możesz wyeksportować HTML do JPEG. Następnie za pomocą interfejsu API przetwarzania obrazów [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) możesz renderować JPEG do SVGZ. Oba interfejsy API są objęte pakietem [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eksportuj HTML do SVGZ przez Javę" %}}
1. Otwórz plik HTML za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Zainicjuj obiekt klasy i wyrenderuj HTML do formatu JPEG przy użyciu [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metoda
3. Załaduj plik JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Zapisz dokument w formacie SVGZ za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj HTML na SVGZ w jednym pliku za pomocą Javy" %}}
API pozwala również na eksport pliku HTML do SVGZ do pojedynczego pliku. Aby przekonwertować wszystkie strony, możesz najpierw wyrenderować dokument HTML do jednego pliku TIFF, a następnie wyeksportować plik TIFF do SVGZ. Możesz otworzyć plik wejściowy za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i utworzyć obiekty urządzeń Resolution, TiffSettings i TIFF. Możesz uzyskać pojedynczy obraz TIFF za pomocą [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metoda klasy [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Na koniec możesz załadować plik TIFF za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i zapisać go w formacie SVGZ za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj HTML na SVGZ za pomocą znaku wodnego za pomocą Javy" %}}
Korzystając z API, możesz również wyeksportować plik HTML do SVGZ ze znakiem wodnym w swoim dokumencie SVGZ. Aby dodać do niego znak wodny, możesz najpierw przekonwertować HTML na JPEG i dodać do niego znak wodny. Aby dodać znak wodny, załaduj plik obrazu za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), utwórz obiekt klasy [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) i zainicjuj ją obiektem Image, utwórz nowy [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) i ustaw translację i transformację pod żądanym kątem oraz dodaj znak wodny za pomocą [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po dodaniu znaku wodnego do obrazu możesz zapisać plik JPEG w formacie SVGZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj i obracaj HTML do pliku SVGZ za pomocą Java" %}}
Korzystając z interfejsu API, możesz również obracać wyjściowy obraz SVGZ zgodnie z własnymi potrzebami. Metoda Image.rotateFlip może służyć do obracania obrazu o 90/180/270 stopni i odwracania obrazu w poziomie lub w pionie. Biblioteka zapewnia proste metody wykonywania złożonych operacji, jednocześnie hermetyzując wszystkie brzydkie szczegóły. Możesz określić typ obracania i odwracania, który ma być zastosowany do obrazu. Aby obrócić i odwrócić obraz, możesz załadować przekonwertowany obraz JPEG za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i wywołać obraz. metodę rotateFlip z określeniem odpowiedniego [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Konwertowanie **HTML na SVGZ (Skompresowany SVG)** jest niezbędne do generowania **skalowalnej, skompresowanej grafiki wektorowej** ze stron internetowych. SVGZ zachowuje klarowność i skalowalność grafiki wektorowej, jednocześnie znacząco zmniejszając rozmiary plików, co czyni go idealnym do responsywnych projektów, gotowych do publikacji w sieci wizualizacji oraz interaktywnych treści cyfrowych. Poprzez przekształcenie treści HTML w SVGZ, organizacje mogą zoptymalizować wydajność, poprawić czasy ładowania i efektywnie zarządzać zasobami wektorowymi na różnych platformach.

{{% blocks/products/pf/agp/feature-section-col title="Główne Zastosowania" %}}

* **Infografiki** – Tworzenie wizualnie ostrej, kompaktowej grafiki wektorowej do reprezentacji danych.
* **Diagramy gotowe do publikacji w sieci** – Generowanie skalowalnych diagramów, które idealnie integrują się z witrynami internetowymi.
* **Publikacje o niskiej wadze** – Zmniejszenie rozmiarów plików dla szybszego dostarczania w publikacjach cyfrowych.
* **Mobilne zasoby wizualne** – Zapewnienie wyraźnej grafiki na dowolnej rozdzielczości ekranu lub urządzeniu.
* **Projekty interaktywne** – Wsparcie animacji i interaktywności przy zachowaniu małych rozmiarów plików.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze Automatyzacji" %}}

* **Potoki HTML-do-SVGZ** – Automatyzacja konwersji treści internetowych na skompresowaną grafikę wektorową.
* **Automatyczna kompresja wektorów** – Produkcja konsekwentnie zoptymalizowanych plików SVGZ do użytku w sieci i na urządzeniach mobilnych.
* **Przepływy pracy dla dużej liczby diagramów** – Efektywne przetwarzanie wielu zasobów wektorowych dla dużych projektów.
* **Publikacje o niskiej wadze na poziomie przedsiębiorstwa** – Integracja generowania SVGZ w skalowalne przepływy pracy publikacji cyfrowych.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}