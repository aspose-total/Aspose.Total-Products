---
title: Java API do renderowania SVG do TSV
description: Eksportuj SVG do TSV przez Java API bez użycia Microsoft Excel lub Adobe Reader
url_ignore: /pl/java/conversion/svg-to-tsv/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: TSV
otherformats: TSV XLT EXCEL XLTM XLTX SXC MD TXT ODS XLSM DIF FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj SVG do TSV przez Javę" h2="Konwertuj plik SVG na TSV, używając lokalnego interfejsu API Java w dowolnej aplikacji Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz zintegrować funkcję konwersji SVG na TSV w swoich aplikacjach Java w dwuetapowym procesie. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) możesz renderować SVG do XLSX. W drugim kroku możesz przekonwertować XLSX na TSV, korzystając z interfejsu API do programowania arkuszy kalkulacyjnych [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj plik SVG na TSV za pomocą Java" %}}
1. Otwórz plik SVG za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj SVG na XLSX, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Załaduj dokument XLSX za pomocą klasy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Zapisz dokument w formacie TSV, używając [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) w pliku pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Jeśli dokument SVG jest chroniony hasłem, nie można go przekonwertować na TSV bez hasła. Korzystając z interfejsu API, możesz najpierw otworzyć chroniony dokument przy użyciu prawidłowego hasła, a następnie przekonwertować go. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie [Dokumentu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) i przekaż nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony plik SVG na TSV za pomocą Javy" %}}
Konwertując plik SVG na TSV, możesz także dodać znak wodny do wyjściowego formatu pliku TSV. Aby dodać znak wodny, utwórz nowy skoroszyt, aby otworzyć przekonwertowany plik XLSX. Wybierz arkusz roboczy za pomocą jego indeksu, utwórz kształt i użyj jego funkcji addTextEffect, ustaw kolory, przezroczystość i nie tylko. Następnie możesz zapisać dokument XLSX jako TSV ze znakiem wodnym. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

Konwertowanie plików SVG na TSV (wartości oddzielone tabulatorem) umożliwia eksportowanie diagramów wektorowych do formatu zoptymalizowanego dla arkuszy kalkulacyjnych, analizy statystycznej i dużych zbiorów danych. TSV zapewnia, że dane pozostają zorganizowane i łatwe do analizy.

{{% blocks/products/pf/agp/feature-section-col title="Główne przypadki użycia" %}}

* Przekształcanie interaktywnych wykresów SVG w TSV do analizy statystycznej.
* Eksportowanie diagramów inżynieryjnych do wspólnej edycji arkuszy kalkulacyjnych.
* Udostępnianie grafik edukacyjnych opartych na SVG w formacie TSV dla zespołów badawczych.
* Konwertowanie wizualizacji wydajności produktu na strukturalne dane tabelaryczne.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Scenariusze automatyzacji" %}}

* Zautomatyzowane procesy konwertujące wykresy SVG na TSV dla platform analitycznych.
* Zaplanowane eksporty TSV diagramów wektorowych do pulpitów raportowych.
* Integracja z oprogramowaniem statystycznym wymagającym danych wejściowych w formacie TSV.
* Wywoływana konwersja dla dynamicznie aktualizowanych wizualizacji opartych na wektorach.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}