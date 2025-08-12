---
title: Java API do renderowania CGM do FODS
description: Eksportuj CGM do FODS przez Java API bez użycia Microsoft Excel lub Adobe Reader
url_ignore: /pl/java/conversion/cgm-to-fods/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: FODS
otherformats: ODS TSV XLTX EXCEL XLSB TXT SXC XLSM XLTM MD XLT DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj CGM do FODS przez Javę" h2="Konwertuj plik CGM na FODS, używając lokalnego interfejsu API Java w dowolnej aplikacji Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz zintegrować funkcję konwersji CGM na FODS w swoich aplikacjach Java w dwuetapowym procesie. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) możesz renderować CGM do XLSX. W drugim kroku możesz przekonwertować XLSX na FODS, korzystając z interfejsu API do programowania arkuszy kalkulacyjnych [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj plik CGM na FODS za pomocą Java" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj CGM na XLSX, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Załaduj dokument XLSX za pomocą klasy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Zapisz dokument w formacie FODS, używając [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) w pliku pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Jeśli dokument CGM jest chroniony hasłem, nie można go przekonwertować na FODS bez hasła. Korzystając z interfejsu API, możesz najpierw otworzyć chroniony dokument przy użyciu prawidłowego hasła, a następnie przekonwertować go. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie [Dokumentu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) i przekaż nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony plik CGM na FODS za pomocą Javy" %}}
Konwertując plik CGM na FODS, możesz także dodać znak wodny do wyjściowego formatu pliku FODS. Aby dodać znak wodny, utwórz nowy skoroszyt, aby otworzyć przekonwertowany plik XLSX. Wybierz arkusz roboczy za pomocą jego indeksu, utwórz kształt i użyj jego funkcji addTextEffect, ustaw kolory, przezroczystość i nie tylko. Następnie możesz zapisać dokument XLSX jako FODS ze znakiem wodnym. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Przekształcanie plików **Computer Graphics Metafile (CGM)** na format **FODS (Flat OpenDocument Spreadsheet)** jest skutecznym sposobem przekształcania graficznych danych technicznych w strukturalne, otwarte arkusze kalkulacyjne. W **aplikacjach open-source opartych na Java**, ta konwersja umożliwia inżynierom, badaczom i analitykom danych wyodrębnienie wartości pomiarowych, specyfikacji i szczegółów opartych na wektorach z diagramów CGM do edytowalnych arkuszy FODS. Jako format XML zgodny z ODF, FODS zapewnia kompatybilność z narzędziami takimi jak OpenOffice, ułatwiając udostępnianie i współpracę bez ograniczeń własnościowych.


## ✅ Kluczowe przypadki użycia

- **Konwersja Graficznych Danych Technicznych na Arkusze Kalkulacyjne**  
  Wyodrębnij dane graficzne wektorów z plików CGM do strukturalnych wierszy i kolumn do analizy.

- **Dokumentowanie Wartości Pomiarowych**  
  Przechowuj i zarządzaj pomiarami inżynieryjnymi lub wynikami eksperymentów w przenośnym formacie arkusza kalkulacyjnego.

- **Udostępnianie za pomocą narzędzi ODF**  
  Dystrybuuj dane arkusza kalkulacyjnego pochodzące z CGM za pomocą aplikacji zgodnych z ODF.


## ⚙️ Scenariusze automatyzacji

- **Biblioteki Java takie jak JOpenDocument**  
  Zautomatyzuj konwersję CGM na FODS w przepływach pracy w Java, korzystając z bibliotek obsługi arkuszy kalkulacyjnych typu open-source.

- **Integracja Headless LibreOffice**  
  Uruchamiaj LibreOffice w trybie bezinterfejsowym z aplikacji Java, aby wsadowo konwertować grafiki CGM na arkusze FODS.

- **Generowanie Masowych FODS**  
  Włącz analizę CGM i tworzenie FODS do potoków ETL opartych na Java do ekstrakcji danych na dużą skalę.

- **Systemy Przetwarzania Danych Open-Source**  
  Używaj FODS jako części platform naukowych lub inżynieryjnych opartych na Java do transparentnego, opartego na standardach zarządzania danymi.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}