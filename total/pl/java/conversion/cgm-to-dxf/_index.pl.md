---
title: Konwertuj CGM na DXF przez Java
description: Eksportuj plik CGM do DXF w swoich aplikacjach Java bez korzystania z aplikacji innych firm
url_ignore: /pl/java/conversion/cgm-to-dxf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DXF
otherformats: WMF PSD DXF  JPEG2000 SVGZ EMZ WMZ IMAGE TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj CGM na DXF przez Java" h2="Eksportuj plik CGM do DXF w dowolnej aplikacji Java J2SE, J2EE, J2ME bez użycia Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować plik cgm na obraz DXF w Javie w dwóch prostych krokach. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), możesz wyeksportować CGM do JPEG. Następnie za pomocą interfejsu API przetwarzania obrazów [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) możesz renderować JPEG do DXF. Oba interfejsy API są objęte pakietem [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Eksportuj CGM do DXF przez Javę" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Zainicjuj obiekt klasy i wyrenderuj CGM do formatu JPEG przy użyciu [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metoda
3. Załaduj plik JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Zapisz dokument w formacie DXF za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj CGM na DXF w jednym pliku za pomocą Javy" %}}
API pozwala również na eksport pliku CGM do DXF do pojedynczego pliku. Aby przekonwertować wszystkie strony, możesz najpierw wyrenderować dokument CGM do jednego pliku TIFF, a następnie wyeksportować plik TIFF do DXF. Możesz otworzyć plik wejściowy za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) i utworzyć obiekty urządzeń Resolution, TiffSettings i TIFF. Możesz uzyskać pojedynczy obraz TIFF za pomocą [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metoda klasy [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Na koniec możesz załadować plik TIFF za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i zapisać go w formacie DXF za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj CGM na DXF za pomocą znaku wodnego za pomocą Javy" %}}
Korzystając z API, możesz również wyeksportować plik CGM do DXF ze znakiem wodnym w swoim dokumencie DXF. Aby dodać do niego znak wodny, możesz najpierw przekonwertować CGM na JPEG i dodać do niego znak wodny. Aby dodać znak wodny, załaduj plik obrazu za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), utwórz obiekt klasy [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) i zainicjuj ją obiektem Image, utwórz nowy [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) i ustaw translację i transformację pod żądanym kątem oraz dodaj znak wodny za pomocą [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po dodaniu znaku wodnego do obrazu możesz zapisać plik JPEG w formacie DXF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj i obracaj CGM do pliku DXF za pomocą Java" %}}
Korzystając z interfejsu API, możesz również obracać wyjściowy obraz DXF zgodnie z własnymi potrzebami. Metoda Image.rotateFlip może służyć do obracania obrazu o 90/180/270 stopni i odwracania obrazu w poziomie lub w pionie. Biblioteka zapewnia proste metody wykonywania złożonych operacji, jednocześnie hermetyzując wszystkie brzydkie szczegóły. Możesz określić typ obracania i odwracania, który ma być zastosowany do obrazu. Aby obrócić i odwrócić obraz, możesz załadować przekonwertowany obraz JPEG za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) i wywołać obraz. metodę rotateFlip z określeniem odpowiedniego [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Konwertowanie plików **Computer Graphics Metafile (CGM)** na **DXF (Drawing Exchange Format)** jest niezbędne w przepływach pracy **CAD (Computer-Aided Design)**, aby zapewnić bezproblemową interoperacyjność między systemami inżynieryjnymi, architektonicznymi i produkcyjnymi. W aplikacjach opartych na **Java**, ta konwersja pozwala na przekształcenie wektorowych diagramów technicznych z CGM na powszechnie obsługiwany format CAD, umożliwiając ich edycję, udostępnianie i kompatybilność z narzędziami do projektowania standardowymi w branży. Jest to kluczowe dla projektowania współpracującego, precyzyjnej produkcji i archiwizacji rysunków technicznych.


## ✅ Kluczowe przypadki użycia

- **Interoperacyjność projektowania inżynieryjnego**  
  Udostępnianie i edycja projektów opartych na CGM w narzędziach CAD obsługujących DXF dla współpracy między platformami.

- **Wymiana planów produkcyjnych**  
  Dostarczanie zespołom produkcyjnym plików DXF pochodzących z diagramów CGM do obróbki CNC i produkcji.

- **Edycja grafiki wektorowej**  
  Przekształcanie diagramów CGM na DXF do bezpośredniej modyfikacji w oprogramowaniu CAD bez utraty wierności wektorowej.


## ⚙️ Scenariusze automatyzacji

- **Narzędzia CAD oparte na Java**  
  Zintegruj konwersję CGM na DXF bezpośrednio w aplikacje do edycji i wizualizacji CAD zasilane przez Javę.

- **Konwertery rysunków inżynieryjnych**  
  Użyj interfejsów API Javy do automatyzacji wsadowych konwersji CGM na DXF dla przepływów pracy z wieloma projektami.

- **Zautomatyzowane systemy archiwizacji CAD**  
  Przechowuj projekty CGM jako pliki DXF w długoterminowych archiwach inżynieryjnych do przyszłego ponownego wykorzystania i zgodności.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}