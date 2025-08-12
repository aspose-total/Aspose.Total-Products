---
title: Java API do renderowania CGM do TXT
description: Eksportuj CGM do TXT przez Java API bez użycia Microsoft Excel lub Adobe Reader
url_ignore: /pl/java/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLAM FODS XLTM ODS MD DIF EXCEL TXT XLTX XLT SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj CGM do TXT przez Javę" h2="Konwertuj plik CGM na TXT, używając lokalnego interfejsu API Java w dowolnej aplikacji Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz zintegrować funkcję konwersji CGM na TXT w swoich aplikacjach Java w dwuetapowym procesie. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) możesz renderować CGM do XLSX. W drugim kroku możesz przekonwertować XLSX na TXT, korzystając z interfejsu API do programowania arkuszy kalkulacyjnych [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj plik CGM na TXT za pomocą Java" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj CGM na XLSX, używając [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Załaduj dokument XLSX za pomocą klasy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Zapisz dokument w formacie TXT, używając [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) w pliku pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Jeśli dokument CGM jest chroniony hasłem, nie można go przekonwertować na TXT bez hasła. Korzystając z interfejsu API, możesz najpierw otworzyć chroniony dokument przy użyciu prawidłowego hasła, a następnie przekonwertować go. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie [Dokumentu](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) i przekaż nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony plik CGM na TXT za pomocą Javy" %}}
Konwertując plik CGM na TXT, możesz także dodać znak wodny do wyjściowego formatu pliku TXT. Aby dodać znak wodny, utwórz nowy skoroszyt, aby otworzyć przekonwertowany plik XLSX. Wybierz arkusz roboczy za pomocą jego indeksu, utwórz kształt i użyj jego funkcji addTextEffect, ustaw kolory, przezroczystość i nie tylko. Następnie możesz zapisać dokument XLSX jako TXT ze znakiem wodnym. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Konwertowanie plików **Computer Graphics Metafile (CGM)** na format **TXT (Plain Text)** jest wartościowe do wyodrębniania, dokumentowania i przetwarzania informacji grafiki wektorowej w lekkiej, czytelnej dla człowieka formie. W **potokach przetwarzania danych opartych na Java**, ta konwersja umożliwia przekształcenie diagramów CGM w reprezentacje tekstowe do logowania, przechowywania metadanych lub analizy dalszej. Poprzez przechwytywanie elementów opisowych plików CGM w formacie TXT, organizacje mogą upraszczać integrację z innymi systemami, umożliwiać szybkie wyszukiwanie i indeksowanie oraz zachować długoterminową kompatybilność.



## ✅ Kluczowe przypadki użycia

- **Logowanie diagramów opartych na tekście**  
  Przechowuj informacje o diagramach CGM jako zwykły tekst do celów audytowych, debugowania lub archiwizacji.

- **Wyodrębnianie opisów grafiki wektorowej**  
  Konwertuj struktury CGM na format TXT do analizy składniowej, indeksowania wyszukiwania lub integracji z narzędziami analitycznymi.

- **Dokumentacja metadanych inżynieryjnych**  
  Udokumentuj dane inżynieryjne związane z CGM w plikach TXT do szybkiego odwoływania się i lekkiego przechowywania.


## ⚙️ Scenariusze automatyzacji

- **Biblioteki wejścia/wyjścia Javy do konwersji**  
  Użyj standardowych interfejsów obsługi plików Javy wraz z analizatorami CGM do wyodrębniania i zapisywania zawartości w plikach TXT.

- **Usługi monitorowania plików**  
  Zautomatyzuj konwersję CGM na TXT monitorując katalogi za pomocą usługi `WatchService` w Javie dla nowych zdarzeń plikowych.

- **Zadania wsadowe konwersji**  
  Przetwarzaj duże ilości plików CGM w zaplanowanych zadaniach Javy, eksportując reprezentacje tekstowe do celów archiwizacji lub analizy.

- **Eksporterzy tekstu z potoków ETL**  
  Zintegruj analizę CGM i eksport TXT do potoków ETL opartych na Javie do przetwarzania danych strukturalnych.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}