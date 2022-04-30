---
title: Konwertuj RTF na POTM za pomocą Javy
description: Java API do eksportu RTF do POTM bez użycia Microsoft Word lub PowerPoint
url: /pl/java/conversion/rtf-to-potm/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: POTM
otherformats: POTX PPSX POTM PPSM POT PPTX PPT POWERPOINT PPTM PPS CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj RTF na POTM za pomocą Javy" h2="Konwersja RTF do POTM przy użyciu lokalnego interfejsu API Java w dowolnej aplikacji Java J2SE, J2EE, J2ME bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint lub Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Często programiści muszą programowo przekonwertować plik RTF na POTM. Korzystając z bibliotek Java File Automation Java [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz zautomatyzować proces renderowania w kilku prostych krokach. Możesz wczytać plik RTF, używając [Aspose.Words for Java](https://products.aspose.com/words/java/) i przekonwertować go na HTML. Następnie za pomocą potężnej manipulacji PowerPoint API Java [Aspose.Slides for Java](https://products.aspose.com/slides/java/) możesz utworzyć nową prezentację, napisać w niej treść HTML i zapisać ją jako POTM .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować RTF na POTM za pomocą Javy?" %}}
1. Otwórz plik RTF za pomocą klasy [Rtfument](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument)
2. Przekonwertuj plik RTF na HTML za pomocą [save](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,com.aspose.words.SaveOptions))) metoda
3. Zainicjuj nowy obiekt [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Wyodrębnij zawartość z pliku HTML za pomocą BufferedReader i zapisz zawartość w pliku prezentacji
6. Zapisz dokument w POTM za pomocą metody [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Do konwersji plików RTF na POTM można łatwo użyć Aspose.Total dla Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose /aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-rtf-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Interfejs API umożliwia również konwersję dokumentów RTF chronionych hasłem na POTM. Jeśli wejściowy dokument RTF jest chroniony hasłem, nie można go przekonwertować do formatu POTM bez użycia hasła. W celu otwarcia zaszyfrowanego dokumentu można ustawić poprawne hasło w obiekcie LoadOptions i przekazać je do konstruktora dokumentu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-rtf-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-ppsm/" name="RTF W celu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-pot/" name="RTF W celu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-powerpoint/" name="RTF W celu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-pptx/" name="RTF W celu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-potx/" name="RTF W celu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-pptm/" name="RTF W celu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-potm/" name="RTF W celu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-pps/" name="RTF W celu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-ppsx/" name="RTF W celu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-ppt/" name="RTF W celu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-csv/" name="RTF W celu CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-dif/" name="RTF W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-fods/" name="RTF W celu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-ods/" name="RTF W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-sxc/" name="RTF W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-tsv/" name="RTF W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xlam/" name="RTF W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xltm/" name="RTF W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-excel/" name="RTF W celu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xls/" name="RTF W celu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xlsb/" name="RTF W celu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xlsm/" name="RTF W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xlsx/" name="RTF W celu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xlt/" name="RTF W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xltm/" name="RTF W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/rtf-to-xltx/" name="RTF W celu XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}