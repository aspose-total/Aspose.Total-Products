---
title: Konwertuj format JSON na DXF przez Java
description: Przetwarzaj JSON do DXF w Javie bez użycia programu Microsoft PowerPoint
url_ignore: /pl/java/conversion/json-to-dxf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DXF
otherformats: DXF WMF WMZ SVGZ TGA JPEG2000 PSD EMZ DICOM IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj format JSON na DXF przez Java" h2="Java API do parsowania formatu JSON do DXF w dowolnych aplikacjach Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/), możesz przekonwertować format JSON na DXF w dowolnej aplikacji Java w dwóch prostych krokach. Po pierwsze, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/), możesz przetworzyć JSON na JPEG. Następnie, używając [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), możesz przekonwertować JPEG na DXF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na DXF przez Java" %}}
1. Utwórz nowy obiekt [Skoroszyt](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i otwórz plik JSON
2. Zapisz JSON jako JPEG za pomocą [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) metoda
3. Załaduj dokument JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Zapisz dokument w formacie DXF za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Ponadto API umożliwia parsowanie JSON do DXF z określonymi opcjami układu. Aby określić opcje układu, możesz użyć klasy [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Pozwala przetwarzać tablicę jako tabelę, ignorować wartości null, ignorować tytuł tablicy, ignorować tytuł obiektu, konwertować ciąg na liczbę lub datę, ustawić format daty i liczby oraz ustawić styl tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na DXF przez Java" %}}
Korzystając z API, możesz również przekonwertować JSON na DXF ze znakiem wodnym w swoim dokumencie DXF. Aby dodać do niego znak wodny, możesz najpierw przekonwertować JSON na JPEG i dodać do niego znak wodny. Aby dodać znak wodny, załaduj plik obrazu za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), utwórz obiekt klasy [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) i zainicjuj ją obiektem Image, utwórz nowy [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) i ustaw translację i transformację pod żądanym kątem oraz dodaj znak wodny za pomocą [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po dodaniu znaku wodnego do obrazu możesz zapisać plik JPEG w formacie DXF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Konwertowanie **JSON na DXF (Drawing Exchange Format)** jest niezbędne do generowania **rysunków CAD** z ustrukturyzowanych zbiorów danych. DXF to powszechnie stosowany format w architekturze, inżynierii, projektowaniu przemysłowym i aplikacjach GIS, co czyni go idealnym do przekształcania danych opartych na JSON w precyzyjne, edytowalne rysunki techniczne. Ta konwersja umożliwia bezproblemowe przepływy danych-do-projektu, poprawiając interoperacyjność między systemami CAD i wspierając automatyzację w nowoczesnych procesach projektowych.

{{% blocks/products/pf/agp/feature-section-col title="Główne Zastosowania" %}}

- **Układy architektoniczne** – Konwertuj dane budynku na edytowalne plany pięter w CAD.
- **Modele inżynieryjne** – Generuj projekty konstrukcyjne i mechaniczne z danych JSON.
- **Automatyzacja CAD oparta na JSON** – Usprawnij przepływy pracy w CAD poprzez przekształcanie ustrukturyzowanych zbiorów danych.
- **Przepływy pracy w projektowaniu przemysłowym** – Twórz dokładne rysunki produktów i komponentów na podstawie danych JSON.
- **Mapowanie GIS** – Konwertuj dane geoprzestrzenne na DXF do planowania urbanistycznego i projektów infrastrukturalnych.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze Automatyzacji" %}}

- **Potoki JSON-do-DXF** – Automatyzuj przekształcanie ustrukturyzowanych danych w rysunki gotowe do użycia w CAD.
- **Automatyczne generowanie rysunków CAD** – Twórz diagramy techniczne bezpośrednio z zestawów danych JSON.
- **Przepływy pracy od danych do projektu** – Umożliwiaj bezproblemową integrację ustrukturyzowanych danych w aplikacjach CAD.
- **Inteligentne modelowanie infrastruktury** – Wspieraj nowoczesne systemy infrastrukturalne i mapowania za pomocą wyników DXF opartych na JSON.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}