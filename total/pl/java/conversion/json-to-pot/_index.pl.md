---
title: Konwertuj format JSON na POT za pomocą Javy
description: Przetwarzaj JSON do POT w Javie bez użycia programu Microsoft PowerPoint
url_ignore: /pl/java/conversion/json-to-pot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POT
otherformats: POWERPOINT OTP PPTM POTX POTM PPS POT PPSM PPSX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj format JSON na POT za pomocą Javy" h2="Java API do przetwarzania formatu JSON na POT bez użycia Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/), możesz przekonwertować format JSON na POT w dowolnej aplikacji Java w dwóch prostych krokach. Po pierwsze, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/), możesz przetworzyć JSON na PPTX. Następnie, używając [Aspose.Slides for Java](https://products.aspose.com/slides/java/), możesz przekonwertować PPTX na POT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na POT za pomocą Javy" %}}
1. Utwórz nowy obiekt [Skoroszyt](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i otwórz plik JSON
2. Zapisz JSON jako PPTX za pomocą [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) metoda
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Zapisz dokument w formacie POT za pomocą metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
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
Ponadto API umożliwia parsowanie JSON do POT z określonymi opcjami układu. Aby określić opcje układu, możesz użyć klasy [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Pozwala przetwarzać tablicę jako tabelę, ignorować wartości null, ignorować tytuł tablicy, ignorować tytuł obiektu, konwertować ciąg na liczbę lub datę, ustawić format daty i liczby oraz ustawić styl tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na POT za pomocą Java" %}}
Korzystając z API, możesz również przekonwertować JSON na POT ze znakiem wodnym. Aby dodać znak wodny do dokumentu POT, możesz najpierw przeanalizować JSON do PPTX i dodać do niego znak wodny. Aby dodać znak wodny, wczytaj nowo utworzony plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), przejdź przez wszystkie slajdy, dodaj tekst używając addTextFrame, ustaw wszystkie potowiednie opcje, takie jak kolor, fillType i inne, i zapisz dokument w POT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Konwertowanie **JSON na POT** jest niezbędne do generowania **plików szablonów PowerPoint z danych strukturalnych**. Szablony POT umożliwiają organizacjom tworzenie standaryzowanych, wielokrotnego użytku projektów slajdów, które zapewniają spójność w prezentacjach biznesowych, akademickich i rządowych. Poprzez przekształcenie JSON w POT, przedsiębiorstwa mogą usprawnić integrację danych, zachować spójność marki i przyspieszyć pracę nad prezentacjami.

{{% blocks/products/pf/agp/feature-section-col title="Główne Zastosowania" %}}

- **Szablony slajdów korporacyjnych** – Buduj markowe szablony bezpośrednio z strukturalnych źródeł danych.
- **Prezentacje oparte na danych** – Generuj ramy prezentacji zasilane zestawami danych JSON.
- **Moduły szkoleniowe** – Standaryzuj projekt slajdów edukacyjnych i wprowadzających.
- **Prezentacje marketingowe** – Twórz wielokrotnego użytku prezentacje marketingowe zgodne z tożsamością marki.
- **Standaryzowane slajdy raportowe** – Automatyzuj ramy raportowania dla powtarzających się prezentacji.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze Automatyzacji" %}}

- **Potoki JSON do POT** – Automatyzuj tworzenie szablonów z dynamicznych zbiorów danych.
- **Automatyczne generowanie szablonów slajdów** – Wyeliminuj powtarzalne zadania projektowania ręcznego.
- **Standaryzacja prezentacji w całej firmie** – Zapewnij spójność marki we wszystkich zespołach.
- **Strukturalne ramy slajdów zintegrowane z danymi** – Wstaw strukturalne dane JSON do wielokrotnego użytku szablonów prezentacji.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}