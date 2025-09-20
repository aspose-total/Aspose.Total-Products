---
title: Konwertuj format JSON na TGA przez Java
description: Przetwarzaj JSON do TGA w Javie bez użycia programu Microsoft PowerPoint
url_ignore: /pl/java/conversion/json-to-tga/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: TGA
otherformats: IMAGE TGA DXF PSD WMZ JPEG2000 EMZ SVGZ DICOM WMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj format JSON na TGA przez Java" h2="Java API do parsowania formatu JSON do TGA w dowolnych aplikacjach Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/), możesz przekonwertować format JSON na TGA w dowolnej aplikacji Java w dwóch prostych krokach. Po pierwsze, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/), możesz przetworzyć JSON na JPEG. Następnie, używając [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), możesz przekonwertować JPEG na TGA.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na TGA przez Java" %}}
1. Utwórz nowy obiekt [Skoroszyt](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i otwórz plik JSON
2. Zapisz JSON jako JPEG za pomocą [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) metoda
3. Załaduj dokument JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Zapisz dokument w formacie TGA za pomocą [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metoda
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
Ponadto API umożliwia parsowanie JSON do TGA z określonymi opcjami układu. Aby określić opcje układu, możesz użyć klasy [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Pozwala przetwarzać tablicę jako tabelę, ignorować wartości null, ignorować tytuł tablicy, ignorować tytuł obiektu, konwertować ciąg na liczbę lub datę, ustawić format daty i liczby oraz ustawić styl tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na TGA przez Java" %}}
Korzystając z API, możesz również przekonwertować JSON na TGA ze znakiem wodnym w swoim dokumencie TGA. Aby dodać do niego znak wodny, możesz najpierw przekonwertować JSON na JPEG i dodać do niego znak wodny. Aby dodać znak wodny, załaduj plik obrazu za pomocą klasy [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), utwórz obiekt klasy [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) i zainicjuj ją obiektem Image, utwórz nowy [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) i ustaw translację i transformację pod żądanym kątem oraz dodaj znak wodny za pomocą [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Po dodaniu znaku wodnego do obrazu możesz zapisać plik JPEG w formacie TGA. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Konwertowanie **JSON na TGA** jest niezbędne do generowania **plików obrazów Targa ze strukturalnych danych**. Pliki TGA są powszechnie używane w tworzeniu gier, modelowaniu 3D i produkcji wideo ze względu na wysokiej jakości grafikę rastrową i obsługę kanału alfa. Poprzez przekształcenie JSON w TGA, organizacje mogą zautomatyzować tworzenie tekstur, usprawnić przepływy wizualne i efektywnie integrować strukturalne dane w potoki graficzne.

{{% blocks/products/pf/agp/feature-section-col title="Główne Zastosowania" %}}

- **Grafika w tworzeniu gier** – Generowanie tekstur i sprite'ów dla gier bezpośrednio ze strukturalnych zbiorów danych.
- **Modelowanie przemysłowe 3D** – Tworzenie zasobów TGA dla projektów CAD i symulacji 3D.
- **Zasoby do edycji wideo** – Tworzenie wysokiej jakości obrazów do przepływów pracy postprodukcji.
- **Symulacje wirtualne** – Tworzenie realistycznych tekstur i elementów wizualnych dla środowisk symulacyjnych.
- **Przestarzałe przepływy pracy z obrazami** – Utrzymywanie kompatybilności z systemami wymagającymi formatów plików Targa.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze Automatyzacji" %}}

- **Potoki JSON-TGA** – Automatyzacja generowania plików TGA ze strukturalnych danych.
- **Automatyzacja generowania tekstur** – Zmniejszenie ręcznego tworzenia zasobów dla projektów graficznych.
- **Eksport grafiki oparty na danych** – Wypełnianie warstw obrazu bezpośrednio ze strukturalnych zbiorów danych.
- **Zautomatyzowane przepływy pracy wizualnej oparte na JSON** – Integracja zautomatyzowanego generowania TGA w przedsiębiorczych potokach graficznych.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}