---
title: Konwertuj WORD na ODP za pomocą Javy
description: Java API do eksportu WORD do ODP bez użycia Microsoft Word lub PowerPoint
url_ignore: /pl/java/conversion/word-to-odp/
family: total
platformtag: net
feature: conversion
informat: WORDX
outformat: ODP
otherformats: POTX PPTM POT POWERPOINT PPTX PPT PPSX PPS POTM PPSM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj WORD na ODP za pomocą Javy" h2="Konwersja WORD do ODP przy użyciu lokalnego interfejsu API Java w dowolnej aplikacji Java J2SE, J2EE, J2ME bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint lub Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Często programiści muszą programowo przekonwertować plik WORD na ODP. Korzystając z bibliotek Java File Automation Java [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz zautomatyzować proces renderowania w kilku prostych krokach. Możesz wczytać plik WORD, używając [Aspose.Words for Java](https://products.aspose.com/words/java/) i przekonwertować go na HTML. Następnie za pomocą potężnej manipulacji PowerPoint API Java [Aspose.Slides for Java](https://products.aspose.com/slides/java/) możesz utworzyć nową prezentację, napisać w niej treść HTML i zapisać ją jako ODP .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować WORD na ODP za pomocą Javy?" %}}
1. Otwórz plik WORD za pomocą klasy [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Przekonwertuj plik WORD na HTML za pomocą [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions))) metoda
3. Zainicjuj nowy obiekt [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Wyodrębnij zawartość z pliku HTML za pomocą BufferedReader i zapisz zawartość w pliku prezentacji
6. Zapisz dokument w ODP za pomocą metody [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Do konwersji plików WORD na ODP można łatwo użyć Aspose.Total dla Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose /aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-word-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Interfejs API umożliwia również konwersję dokumentów WORD chronionych hasłem na ODP. Jeśli wejściowy dokument WORD jest chroniony hasłem, nie można go przekonwertować do formatu ODP bez użycia hasła. W celu otwarcia zaszyfrowanego dokumentu można ustawić poprawne hasło w obiekcie LoadOptions i przekazać je do konstruktora dokumentu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-word-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-ppsm/" name="WORD W celu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-pot/" name="WORD W celu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-powerpoint/" name="WORD W celu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-pptx/" name="WORD W celu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-potx/" name="WORD W celu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-pptm/" name="WORD W celu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-potm/" name="WORD W celu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-pps/" name="WORD W celu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-ppsx/" name="WORD W celu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-ppt/" name="WORD W celu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-csv/" name="WORD W celu CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-dif/" name="WORD W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-fods/" name="WORD W celu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-ods/" name="WORD W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-sxc/" name="WORD W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-tsv/" name="WORD W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-xlam/" name="WORD W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-xltm/" name="WORD W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-excel/" name="WORD W celu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-xls/" name="WORD W celu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-xlsb/" name="WORD W celu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-xlsm/" name="WORD W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-xlsx/" name="WORD W celu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-xlt/" name="WORD W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-xltm/" name="WORD W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/word-to-xltx/" name="WORD W celu XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}