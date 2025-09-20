---
title: Konwertuj format JSON na PPTM za pomocą Javy
description: Przetwarzaj JSON do PPTM w Javie bez użycia programu Microsoft PowerPoint
url_ignore: /pl/java/conversion/json-to-pptm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPTM
otherformats: POT PPSX POTM POWERPOINT PPS OTP PPTM POTX PPSM PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj format JSON na PPTM za pomocą Javy" h2="Java API do przetwarzania formatu JSON na PPTM bez użycia Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/), możesz przekonwertować format JSON na PPTM w dowolnej aplikacji Java w dwóch prostych krokach. Po pierwsze, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/), możesz przetworzyć JSON na PPTX. Następnie, używając [Aspose.Slides for Java](https://products.aspose.com/slides/java/), możesz przekonwertować PPTX na PPTM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na PPTM za pomocą Javy" %}}
1. Utwórz nowy obiekt [Skoroszyt](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i otwórz plik JSON
2. Zapisz JSON jako PPTX za pomocą [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) metoda
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Zapisz dokument w formacie PPTM za pomocą metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Ponadto API umożliwia parsowanie JSON do PPTM z określonymi opcjami układu. Aby określić opcje układu, możesz użyć klasy [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Pozwala przetwarzać tablicę jako tabelę, ignorować wartości null, ignorować tytuł tablicy, ignorować tytuł obiektu, konwertować ciąg na liczbę lub datę, ustawić format daty i liczby oraz ustawić styl tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na PPTM za pomocą Java" %}}
Korzystając z API, możesz również przekonwertować JSON na PPTM ze znakiem wodnym. Aby dodać znak wodny do dokumentu PPTM, możesz najpierw przeanalizować JSON do PPTX i dodać do niego znak wodny. Aby dodać znak wodny, wczytaj nowo utworzony plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), przejdź przez wszystkie slajdy, dodaj tekst używając addTextFrame, ustaw wszystkie pptmowiednie opcje, takie jak kolor, fillType i inne, i zapisz dokument w PPTM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Konwertowanie **JSON na PPTM** jest niezbędne do generowania **prezentacji PowerPoint z makrami z danych strukturalnych**. Pliki PPTM obsługują osadzone makra, umożliwiając zautomatyzowaną interaktywność, dynamiczne treści i zaawansowane funkcje slajdów. Poprzez przekształcenie JSON w PPTM, organizacje mogą efektywnie tworzyć interaktywne pulpity nawigacyjne, standaryzowane zestawy szkoleniowe oraz zautomatyzowane prezentacje raportowe.

{{% blocks/products/pf/agp/feature-section-col title="Główne Zastosowania" %}}

- **Zautomatyzowane pulpity biznesowe** – Tworzenie dynamicznych, makro-włączonych prezentacji dla bieżących informacji przedsiębiorstwa.
- **Interaktywne sesje szkoleniowe** – Standaryzacja modułów edukacyjnych z wbudowaną automatyzacją.
- **Raportowanie finansowe z makrami** – Automatyzacja powtarzalnych zadań raportowych przy użyciu danych strukturalnych i makr.
- **Prezentacje marketingowe oparte na danych** – Tworzenie interaktywnych prezentacji marketingowych zasilanych zestawami danych JSON.
- **Zaawansowane prezentacje akademickie** – Generowanie wykładów i slajdów badawczych z wbudowanymi interaktywnymi funkcjami.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze Automatyzacji" %}}

- **Potoki JSON do PPTM** – Automatyzacja tworzenia makro-włączonych prezentacji z danych strukturalnych.
- **Zautomatyzowane tworzenie prezentacji z makrami** – Zmniejszenie ręcznego projektowania slajdów i kodowania makr.
- **Pulpity nawigacyjne oparte na JSON** – Integracja zestawów danych strukturalnych w interaktywne slajdy prezentacji.
- **Interaktywne raportowanie na poziomie przedsiębiorstwa** – Skalowanie makro-włączonych prezentacji w zespołach i działach efektywnie.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}