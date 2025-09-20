---
title: Konwertuj EPUB na APNG przez Java
description: Eksportuj plik EPUB do APNG w swoich aplikacjach Java bez korzystania z aplikacji innych firm
url_ignore: /pl/java/conversion/epub-to-apng/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: APNG
otherformats: DXF  PSD SVGZ EMZ JPEG2000 TGA WMZ WMF IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj EPUB na APNG przez Java" h2="Eksportuj plik EPUB do APNG w dowolnej aplikacji Java J2SE, J2EE, J2ME bez użycia Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować plik epub na obraz APNG w Javie w dwóch prostych krokach. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), możesz wyeksportować EPUB do JPEG. Następnie za pomocą interfejsu API przetwarzania obrazów [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) możesz renderować JPEG do APNG. Oba interfejsy API są objęte pakietem [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eksportuj EPUB do APNG przez Javę" %}}
1. Otwórz plik EPUB za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Zainicjuj obiekt klasy i wyrenderuj EPUB do formatu JPEG przy użyciu [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metoda
3. Załaduj plik JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Zapisz dokument w formacie APNG za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj EPUB na APNG w jednym pliku za pomocą Javy" %}}
API pozwala również na eksport pliku EPUB do APNG do pojedynczego pliku. Aby przekonwertować wszystkie strony, możesz najpierw wyrenderować dokument EPUB do jednego pliku TIFF, a następnie wyeksportować plik TIFF do APNG. Możesz otworzyć plik wejściowy za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i utworzyć obiekty urządzeń Resolution, TiffSettings i TIFF. Możesz uzyskać pojedynczy obraz TIFF za pomocą [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metoda klasy [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Na koniec możesz załadować plik TIFF za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i zapisać go w formacie APNG za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj EPUB na APNG za pomocą znaku wodnego za pomocą Javy" %}}
Korzystając z API, możesz również wyeksportować plik EPUB do APNG ze znakiem wodnym w swoim dokumencie APNG. Aby dodać do niego znak wodny, możesz najpierw przekonwertować EPUB na JPEG i dodać do niego znak wodny. Aby dodać znak wodny, załaduj plik obrazu za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), utwórz obiekt klasy [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) i zainicjuj ją obiektem Image, utwórz nowy [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) i ustaw translację i transformację pod żądanym kątem oraz dodaj znak wodny za pomocą [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po dodaniu znaku wodnego do obrazu możesz zapisać plik JPEG w formacie APNG. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj i obracaj EPUB do pliku APNG za pomocą Java" %}}
Korzystając z interfejsu API, możesz również obracać wyjściowy obraz APNG zgodnie z własnymi potrzebami. Metoda Image.rotateFlip może służyć do obracania obrazu o 90/180/270 stopni i odwracania obrazu w poziomie lub w pionie. Biblioteka zapewnia proste metody wykonywania złożonych operacji, jednocześnie hermetyzując wszystkie brzydkie szczegóły. Możesz określić typ obracania i odwracania, który ma być zastosowany do obrazu. Aby obrócić i odwrócić obraz, możesz załadować przekonwertowany obraz JPEG za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i wywołać obraz. metodę rotateFlip z określeniem odpowiedniego [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}  
Konwertowanie **EPUB na APNG** odgrywa kluczową rolę w poprawie publikacji cyfrowych poprzez przekształcenie statycznych e-booków w **animowane podglądy obrazów**. Ten proces ożywia publikacje cyfrowe, sprawiając, że są bardziej angażujące, interaktywne i wizualnie atrakcyjne na wielu platformach. Od e-learningu po marketing, podglądy APNG pomagają wydawcom dostarczać dynamiczne doświadczenia, które przyciągają uwagę.

{{% blocks/products/pf/agp/feature-section-col title="Główne przypadki użycia" %}}  
- **Interaktywne podglądy książek** – Prezentuj animowane fragmenty z książek cyfrowych.  
- **Animowane treści e-learningowe** – Dostarczaj wizualne wyjaśnienia dla lepszego zaangażowania studentów.  
- **Publikacje z bogatym materiałem multimedialnym** – Dodaj dynamiczne podglądy, aby wzbogacić narrację i projektowanie.  
- **Kreatywne materiały marketingowe cyfrowe** – Wykorzystaj animowane fragmenty do kampanii promocyjnych.  
- **Opowiadanie wieloplatformowe** – Udostępniaj animacje na różnych urządzeniach i platformach bezproblemowo.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze automatyzacji" %}}  
- **Potoki konwersji EPUB na APNG** – Zoptymalizowane przepływy pracy dla wydawców.  
- **Automatyczna generacja animowanych podglądów** – Twórz podglądy natychmiastowo w dużej skali.  
- **Integracje platform e-learningowych** – Konwertuj lekcje na angażujące fragmenty APNG.  
- **Automatyzacja publikacji w dużym zakresie** – Umożliwia masową konwersję dla bibliotek cyfrowych.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}