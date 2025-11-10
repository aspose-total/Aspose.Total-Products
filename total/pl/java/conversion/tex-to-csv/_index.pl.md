---
title: Java API do renderowania TEX do CSV
description: Eksportuj TEX do CSV przez Java API bez użycia Microsoft Excel lub Adobe Reader
url_ignore: /pl/java/conversion/tex-to-csv/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: CSV
otherformats: XLAM SXC MD FODS XLTM TXT EXCEL ODS XLT XLSM XLTX TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj TEX do CSV przez Javę" h2="Konwertuj plik TEX na CSV, używając lokalnego interfejsu API Java w dowolnej aplikacji Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz zintegrować funkcję konwersji TEX na CSV w swoich aplikacjach Java w dwuetapowym procesie. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) możesz renderować TEX do XLSX. W drugim kroku możesz przekonwertować XLSX na CSV, korzystając z interfejsu API do programowania arkuszy kalkulacyjnych [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj plik TEX na CSV za pomocą Java" %}}
1. Otwórz plik TEX za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj TEX na XLSX, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Załaduj dokument XLSX za pomocą klasy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Zapisz dokument w formacie CSV, używając [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) w pliku pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Jeśli dokument TEX jest chroniony hasłem, nie można go przekonwertować na CSV bez hasła. Korzystając z interfejsu API, możesz najpierw otworzyć chroniony dokument przy użyciu prawidłowego hasła, a następnie przekonwertować go. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie [Dokumentu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) i przekaż nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony plik TEX na CSV za pomocą Javy" %}}
Konwertując plik TEX na CSV, możesz także dodać znak wodny do wyjściowego formatu pliku CSV. Aby dodać znak wodny, utwórz nowy skoroszyt, aby otworzyć przekonwertowany plik XLSX. Wybierz arkusz roboczy za pomocą jego indeksu, utwórz kształt i użyj jego funkcji addTextEffect, ustaw kolory, przezroczystość i nie tylko. Następnie możesz zapisać dokument XLSX jako CSV ze znakiem wodnym. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Konwertowanie plików TEX na **CSV (wartości rozdzielone przecinkami)** pozwala przekształcić dokumenty LaTeX w lekkie dane tabelaryczne do arkuszy kalkulacyjnych, baz danych i aplikacji analitycznych. Jest to idealne rozwiązanie dla badaczy i analityków pracujących z zestawami danych numerycznych w LaTeX.



{{% blocks/products/pf/agp/feature-section-col title="Główne przypadki użycia" %}}



* Eksportowanie tabel wygenerowanych w LaTeX do formatu CSV w celu analizy danych.

* Zbiory danych akademickich do oprogramowania statystycznego i przetwarzania w Pythonie/R.

* Raporty finansowe lub inżynieryjne sformatowane w LaTeX przekształcone do przeglądu w arkuszu kalkulacyjnym.

* Udostępnianie danych projektów open-source w uniwersalnym formacie CSV.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenariusze automatyzacji" %}}



* Konwersja wsadowa TEX na CSV w potokach ETL.

* Automatyczne wyodrębnianie tabel z artykułów badawczych.

* Integracja z platformami analityki opartej na sztucznej inteligencji.

* Wywoływanie generowania plików CSV dla zbiorów danych do współpracy.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}