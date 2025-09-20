---
title: Konwertuj format JSON na ODP za pomocą Javy
description: Przetwarzaj JSON do ODP w Javie bez użycia programu Microsoft PowerPoint
url_ignore: /pl/java/conversion/json-to-odp/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODP
otherformats: PPS PPT PPTM PPSM POWERPOINT POT POTM OTP PPSX POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj format JSON na ODP za pomocą Javy" h2="Java API do przetwarzania formatu JSON na ODP bez użycia Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/), możesz przekonwertować format JSON na ODP w dowolnej aplikacji Java w dwóch prostych krokach. Po pierwsze, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/), możesz przetworzyć JSON na PPTX. Następnie, używając [Aspose.Slides for Java](https://products.aspose.com/slides/java/), możesz przekonwertować PPTX na ODP.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na ODP za pomocą Javy" %}}
1. Utwórz nowy obiekt [Skoroszyt](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i otwórz plik JSON
2. Zapisz JSON jako PPTX za pomocą [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) metoda
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Zapisz dokument w formacie ODP za pomocą metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
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
Ponadto API umożliwia parsowanie JSON do ODP z określonymi opcjami układu. Aby określić opcje układu, możesz użyć klasy [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Pozwala przetwarzać tablicę jako tabelę, ignorować wartości null, ignorować tytuł tablicy, ignorować tytuł obiektu, konwertować ciąg na liczbę lub datę, ustawić format daty i liczby oraz ustawić styl tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na ODP za pomocą Java" %}}
Korzystając z API, możesz również przekonwertować JSON na ODP ze znakiem wodnym. Aby dodać znak wodny do dokumentu ODP, możesz najpierw przeanalizować JSON do PPTX i dodać do niego znak wodny. Aby dodać znak wodny, wczytaj nowo utworzony plik PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), przejdź przez wszystkie slajdy, dodaj tekst używając addTextFrame, ustaw wszystkie odpowiednie opcje, takie jak kolor, fillType i inne, i zapisz dokument w ODP. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Konwertowanie **JSON na ODP** jest kluczowe dla generowania prezentacji **OpenDocument** bezpośrednio z zestawów danych. ODP, standardowy format używany przez LibreOffice i OpenOffice, zapewnia pełną kompatybilność z pakietami biurowymi typu open-source oraz z przepływami pracy na różnych platformach. Poprzez przekształcenie JSON w ODP, organizacje mogą tworzyć dynamiczne, wielokrotnego użytku i standaryzowane prezentacje bez konieczności manualnego wysiłku.

{{% blocks/products/pf/agp/feature-section-col title="Główne Zastosowania" %}}

- **Prezentacje biznesowe** – Buduj prezentacje korporacyjne oparte na danych bezpośrednio ze źródeł strukturalnych.
- **Slajdy edukacyjne** – Generuj materiały do nauki i wykłady z danych akademickich.
- **Prezentacje oparte na danych** – Automatyzuj prezentacje dla inwestorów lub sprzedażowe, korzystając z danych w czasie rzeczywistym.
- **Przepływy pracy w sektorze publicznym** – Wspieraj transparentność i zgodność z otwartym standardem slajdów ODP.
- **Integracja z pakietami biurowymi typu open-source** – Zapewnij bezproblemową kompatybilność z LibreOffice, Apache OpenOffice i innymi narzędziami zgodnymi z ODF.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze Automatyzacji" %}}

- **Potoki JSON do ODP** – Automatyzuj konwersję danych strukturalnych na prezentacje w otwartym standardzie.
- **Automatyczna generacja slajdów** – Oszczędzaj czas, produkując gotowe do prezentacji slajdy bezpośrednio z danych.
- **Przepływy pracy od danych do prezentacji** – Integruj systemy danych przedsiębiorstwa z generacją ODP do celów raportowania.
- **Standaryzacja prezentacji w przedsiębiorstwie** – Zapewnij jednolitość w projektowaniu, strukturze i zgodności w dużych organizacjach.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}