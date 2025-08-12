---
title: Konwertuj CGM na DICOM przez Java
description: Eksportuj plik CGM do DICOM w swoich aplikacjach Java bez korzystania z aplikacji innych firm
url_ignore: /pl/java/conversion/cgm-to-dicom/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DICOM
otherformats: EMZ PSD WMF WMZ TGA DICOM DXF SVGZ IMAGE JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj CGM na DICOM przez Java" h2="Eksportuj plik CGM do DICOM w dowolnej aplikacji Java J2SE, J2EE, J2ME bez użycia Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować plik cgm na obraz DICOM w Javie w dwóch prostych krokach. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), możesz wyeksportować CGM do JPEG. Następnie za pomocą interfejsu API przetwarzania obrazów [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) możesz renderować JPEG do DICOM. Oba interfejsy API są objęte pakietem [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eksportuj CGM do DICOM przez Javę" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Zainicjuj obiekt klasy i wyrenderuj CGM do formatu JPEG przy użyciu [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metoda
3. Załaduj plik JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Zapisz dokument w formacie DICOM za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj CGM na DICOM w jednym pliku za pomocą Javy" %}}
API pozwala również na eksport pliku CGM do DICOM do pojedynczego pliku. Aby przekonwertować wszystkie strony, możesz najpierw wyrenderować dokument CGM do jednego pliku TIFF, a następnie wyeksportować plik TIFF do DICOM. Możesz otworzyć plik wejściowy za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i utworzyć obiekty urządzeń Resolution, TiffSettings i TIFF. Możesz uzyskać pojedynczy obraz TIFF za pomocą [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metoda klasy [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Na koniec możesz załadować plik TIFF za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i zapisać go w formacie DICOM za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj CGM na DICOM za pomocą znaku wodnego za pomocą Javy" %}}
Korzystając z API, możesz również wyeksportować plik CGM do DICOM ze znakiem wodnym w swoim dokumencie DICOM. Aby dodać do niego znak wodny, możesz najpierw przekonwertować CGM na JPEG i dodać do niego znak wodny. Aby dodać znak wodny, załaduj plik obrazu za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), utwórz obiekt klasy [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) i zainicjuj ją obiektem Image, utwórz nowy [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) i ustaw translację i transformację pod żądanym kątem oraz dodaj znak wodny za pomocą [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po dodaniu znaku wodnego do obrazu możesz zapisać plik JPEG w formacie DICOM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj i obracaj CGM do pliku DICOM za pomocą Java" %}}
Korzystając z interfejsu API, możesz również obracać wyjściowy obraz DICOM zgodnie z własnymi potrzebami. Metoda Image.rotateFlip może służyć do obracania obrazu o 90/180/270 stopni i odwracania obrazu w poziomie lub w pionie. Biblioteka zapewnia proste metody wykonywania złożonych operacji, jednocześnie hermetyzując wszystkie brzydkie szczegóły. Możesz określić typ obracania i odwracania, który ma być zastosowany do obrazu. Aby obrócić i odwrócić obraz, możesz załadować przekonwertowany obraz JPEG za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i wywołać obraz. metodę rotateFlip z określeniem odpowiedniego [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Przekształcanie plików **Computer Graphics Metafile (CGM)** na format **DICOM (Digital Imaging and Communications in Medicine)** jest kluczowe dla zapewnienia kompatybilności z nowoczesnymi przepływami pracy w dziedzinie obrazowania medycznego. W systemach obrazowania medycznego opartych na **Java**, ta konwersja umożliwia bezproblemową integrację z infrastrukturą danych szpitalnych, wspiera standaryzowaną wymianę obrazów i zwiększa możliwości wizualizacji diagnostycznej. Poprzez przekształcenie rysunków lub diagramów CGM na format DICOM, organizacje medyczne mogą unifikować różnorodne formaty obrazów, umożliwiając dostęp do nich w ramach **PACS**, przeglądarek radiologicznych i narzędzi diagnostycznych opartych na sztucznej inteligencji.

## ✅ Kluczowe przypadki użycia

- **Przeglądarki radiologiczne zintegrowane z Javą**  
  Wyświetlaj medyczne ilustracje oparte na CGM bezpośrednio w przeglądarkach DICOM zasilanych przez Javę, dla usprawnionej interpretacji diagnostycznej.

- **Systemy Informacji Szpitalnej (HIS)**  
  Konwertuj CGM na DICOM w celu uzyskania standaryzowanych rekordów obrazowych dostępnych w sieciach szpitalnych.

- **Wymiana Danych Radiologicznych**  
  Umożliwiaj płynny transfer przekonwertowanych plików obrazowych między placówkami medycznymi przy użyciu globalnego standardu DICOM.

- **Wizualizacja Diagnostyczna**  
  Poprawiaj przepływy pracy klinicznej poprzez osadzanie przekonwertowanych danych CGM w badaniach obrazowania wielomodalnego.

## ⚙️ Scenariusze automatyzacji

- **API Javy do Obsługi DICOM**  
  Automatyzuj potoki konwersji CGM na DICOM przy użyciu bibliotek Javy do przetwarzania obrazów i zarządzania metadanymi DICOM.

- **Integracja z Systemem PACS**  
  Wprowadzaj przekonwertowane obrazy DICOM bezpośrednio do Systemów Archiwizacji i Komunikacji Obrazów dla natychmiastowego pobierania i przechowywania.

- **Potoki ETL oparte na Javie**  
  Zintegruj automatyczną konwersję w potoki Extract-Transform-Load do zarządzania danymi obrazowymi na szczeblu szpitalnym.

- **Przepływy Pracy Diagnostycznej z Wykorzystaniem SI**  
  Wykorzystaj zintegrowane modele SI w Javie do analizy przekonwertowanych obrazów DICOM w celu rozpoznawania wzorców, wykrywania anomalii i diagnostyki predykcyjnej.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}