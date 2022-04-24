---
title: Java API do renderowania XSLFO do XLTM
description: Eksportuj XSLFO do XLTM przez Java API bez użycia Microsoft Excel lub Adobe Reader
url: /pl/java/conversion/xslfo-to-xltm/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: XLTM
otherformats: TSV FODS SXC XLT XLTM EXCEL ODS MD DIF XLTX XLAM XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj XSLFO do XLTM przez Javę" h2="Konwertuj plik XSLFO na XLTM, używając lokalnego interfejsu API Java w dowolnej aplikacji Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz zintegrować funkcję konwersji XSLFO na XLTM w swoich aplikacjach Java w dwuetapowym procesie. Po pierwsze, używając [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) możesz renderować XSLFO do XLSX. W drugim kroku możesz przekonwertować XLSX na XLTM, korzystając z interfejsu API do programowania arkuszy kalkulacyjnych [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj plik XSLFO na XLTM za pomocą Java" %}}
1. Otwórz plik XSLFO za pomocą klasy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konwertuj XSLFO na XLSX, używając [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metoda
3. Załaduj dokument XLSX za pomocą klasy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Zapisz dokument w formacie XLTM, używając [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) i [Aspose.Cells for Java](https://docs.aspose.com/cells/java/ instalacja/) w pliku pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Jeśli dokument XSLFO jest chroniony hasłem, nie można go przekonwertować na XLTM bez hasła. Korzystając z interfejsu API, możesz najpierw otworzyć chroniony dokument przy użyciu prawidłowego hasła, a następnie przekonwertować go. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie [Dokumentu](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- java.lang.String-) i przekaż nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony plik XSLFO na XLTM za pomocą Javy" %}}
Konwertując plik XSLFO na XLTM, możesz także dodać znak wodny do wyjściowego formatu pliku XLTM. Aby dodać znak wodny, utwórz nowy skoroszyt, aby otworzyć przekonwertowany plik XLSX. Wybierz arkusz roboczy za pomocą jego indeksu, utwórz kształt i użyj jego funkcji addTextEffect, ustaw kolory, przezroczystość i nie tylko. Następnie możesz zapisać dokument XLSX jako XLTM ze znakiem wodnym. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-dif/" name="XSLFO W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-xltx/" name="XSLFO W celu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-md/" name="XSLFO W celu MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-fods/" name="XSLFO W celu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-xltm/" name="XSLFO W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-excel/" name="XSLFO W celu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-xlsm/" name="XSLFO W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-xlam/" name="XSLFO W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-xlt/" name="XSLFO W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-xlsb/" name="XSLFO W celu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-ods/" name="XSLFO W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/xslfo-to-sxc/" name="XSLFO W celu SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}