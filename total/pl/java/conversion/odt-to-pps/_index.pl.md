---
title: Konwertuj ODT na PPS za pomocą Javy
description: Java API do eksportu ODT do PPS bez użycia Microsoft Word lub PowerPoint
url_ignore: /pl/java/conversion/odt-to-pps/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: PPS
otherformats: POTX POTM PPT POT PPTM PPTX PPSX PPS PPSM POWERPOINT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj ODT na PPS za pomocą Javy" h2="Konwersja ODT do PPS przy użyciu lokalnego interfejsu API Java w dowolnej aplikacji Java J2SE, J2EE, J2ME bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint lub Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Często programiści muszą programowo przekonwertować plik ODT na PPS. Korzystając z bibliotek Java File Automation Java [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz zautomatyzować proces renderowania w kilku prostych krokach. Możesz wczytać plik ODT, używając [Aspose.Words for Java](https://products.aspose.com/words/java/) i przekonwertować go na HTML. Następnie za pomocą potężnej manipulacji PowerPoint API Java [Aspose.Slides for Java](https://products.aspose.com/slides/java/) możesz utworzyć nową prezentację, napisać w niej treść HTML i zapisać ją jako PPS .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować ODT na PPS za pomocą Javy?" %}}
1. Otwórz plik ODT za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Przekonwertuj plik ODT na HTML za pomocą [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metoda
3. Zainicjuj nowy obiekt [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Wyodrębnij zawartość z pliku HTML za pomocą BufferedReader i zapisz zawartość w pliku prezentacji
6. Zapisz dokument w PPS za pomocą metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Do konwersji plików ODT na PPS można łatwo użyć Aspose.Total dla Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Interfejs API umożliwia również konwersję dokumentów ODT chronionych hasłem na PPS. Jeśli wejściowy dokument ODT jest chroniony hasłem, nie można go przekonwertować do formatu PPS bez użycia hasła. W celu otwarcia zaszyfrowanego dokumentu można ustawić poprawne hasło w obiekcie LoadOptions i przekazać je do konstruktora dokumentu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-ppsm/" name="ODT W celu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-pot/" name="ODT W celu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-powerpoint/" name="ODT W celu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-pptx/" name="ODT W celu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-potx/" name="ODT W celu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-pptm/" name="ODT W celu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-potm/" name="ODT W celu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-pps/" name="ODT W celu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-ppsx/" name="ODT W celu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-ppt/" name="ODT W celu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-csv/" name="ODT W celu CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-dif/" name="ODT W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-fods/" name="ODT W celu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-ods/" name="ODT W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-sxc/" name="ODT W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-tsv/" name="ODT W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-xlam/" name="ODT W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-xltm/" name="ODT W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-excel/" name="ODT W celu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-xls/" name="ODT W celu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-xlsb/" name="ODT W celu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-xlsm/" name="ODT W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-xlsx/" name="ODT W celu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-xlt/" name="ODT W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-xltm/" name="ODT W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/odt-to-xltx/" name="ODT W celu XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}