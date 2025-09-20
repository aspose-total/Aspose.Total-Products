---
title: Konwertuj format JSON na DICOM przez Java
description: Przetwarzaj JSON do DICOM w Javie bez użycia programu Microsoft PowerPoint
url_ignore: /pl/java/conversion/json-to-dicom/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DICOM
otherformats: DICOM DXF WMF TGA SVGZ EMZ IMAGE JPEG2000 PSD WMZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj format JSON na DICOM przez Java" h2="Java API do parsowania formatu JSON do DICOM w dowolnych aplikacjach Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/), możesz przekonwertować format JSON na DICOM w dowolnej aplikacji Java w dwóch prostych krokach. Po pierwsze, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/), możesz przetworzyć JSON na JPEG. Następnie, używając [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), możesz przekonwertować JPEG na DICOM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na DICOM przez Java" %}}
1. Utwórz nowy obiekt [Skoroszyt](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i otwórz plik JSON
2. Zapisz JSON jako JPEG za pomocą [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) metoda
3. Załaduj dokument JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Zapisz dokument w formacie DICOM za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
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
Ponadto API umożliwia parsowanie JSON do DICOM z określonymi opcjami układu. Aby określić opcje układu, możesz użyć klasy [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Pozwala przetwarzać tablicę jako tabelę, ignorować wartości null, ignorować tytuł tablicy, ignorować tytuł obiektu, konwertować ciąg na liczbę lub datę, ustawić format daty i liczby oraz ustawić styl tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na DICOM przez Java" %}}
Korzystając z API, możesz również przekonwertować JSON na DICOM ze znakiem wodnym w swoim dokumencie DICOM. Aby dodać do niego znak wodny, możesz najpierw przekonwertować JSON na JPEG i dodać do niego znak wodny. Aby dodać znak wodny, załaduj plik obrazu za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), utwórz obiekt klasy [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) i zainicjuj ją obiektem Image, utwórz nowy [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) i ustaw translację i transformację pod żądanym kątem oraz dodaj znak wodny za pomocą [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po dodaniu znaku wodnego do obrazu możesz zapisać plik JPEG w formacie DICOM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Konwertowanie **JSON na DICOM (Digital Imaging and Communications in Medicine)** jest kluczowe dla przekształcenia **strukturalnych danych zdrowotnych** w standaryzowane formaty obrazowania medycznego. DICOM to globalny standard przechowywania, przesyłania i wizualizacji obrazów medycznych, umożliwiający dostawcom opieki zdrowotnej, badaczom i systemom sztucznej inteligencji pracę z konsekwentnymi, interoperacyjnymi danymi. Poprzez konwersję JSON na DICOM, strukturalne dane pacjentów i kliniczne mogą być bezproblemowo zintegrowane z przepływami obrazowania, wspierając dokładne diagnozy i lepsze wyniki opieki zdrowotnej.

{{% blocks/products/pf/agp/feature-section-col title="Główne Zastosowania" %}}

- **Wizualizacja danych pacjenta** – Konwertuj strukturalne dane zdrowotne na formaty wizualnego obrazowania.
- **Medyczne obrazowanie oparte na AI** – Umożliwiaj systemom uczenia maszynowego przetwarzanie zestawów danych sterowanych przez JSON.
- **Interoperacyjność w opiece zdrowotnej** – Standaryzuj strukturalne dane w globalnie akceptowane formaty DICOM.
- **Przepływy radiologiczne** – Zintegruj raporty oparte na JSON z systemami obrazowania i diagnostycznymi.
- **Integracja danych z badań klinicznych** – Przekształć strukturalne zbiory danych w formaty kompatybilne z obrazowaniem do badań.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze Automatyzacji" %}}

- **Potoki JSON-do-DICOM** – Automatyzuj przekształcanie danych zdrowotnych w gotowe do obrazowania formaty.
- **Automatyczna konwersja raportów medycznych** – Generuj pliki DICOM bezpośrednio z klinicznych raportów opartych na JSON.
- **Obrazowanie oparte na chmurze w opiece zdrowotnej** – Umożliwiaj skalowalną, interoperacyjną wymianę danych obrazowych w chmurze.
- **Systemy diagnostyczne oparte na AI** – Wspieraj zaawansowane narzędzia diagnostyczne konwersją ze strukturalnych na obrazowe.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}