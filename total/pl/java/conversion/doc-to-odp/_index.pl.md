---
title: Konwertuj DOC na ODP za pomocą Javy
description: Java API do eksportu DOC do ODP bez użycia Microsoft Word lub PowerPoint
url_ignore: /pl/java/conversion/doc-to-odp/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: ODP
otherformats: PPSM POT POWERPOINT PPTX POTX PPTM POTM PPS PPSX PPT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj DOC na ODP za pomocą Javy" h2="Konwersja DOC do ODP przy użyciu lokalnego interfejsu API Java w dowolnej aplikacji Java J2SE, J2EE, J2ME bez korzystania z programu Microsoft<sup>&reg;</sup> PowerPoint lub Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Często programiści muszą programowo przekonwertować plik DOC na ODP. Korzystając z bibliotek Java File Automation Java [Aspose.Total for Java](https://products.aspose.com/total/java/) możesz zautomatyzować proces renderowania w kilku prostych krokach. Możesz wczytać plik DOC, używając [Aspose.Words for Java](https://products.aspose.com/words/java/) i przekonwertować go na HTML. Następnie za pomocą potężnej manipulacji PowerPoint API Java [Aspose.Slides for Java](https://products.aspose.com/slides/java/) możesz utworzyć nową prezentację, napisać w niej treść HTML i zapisać ją jako ODP .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak przekonwertować DOC na ODP za pomocą Javy?" %}}
1. Otwórz plik DOC za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Przekonwertuj plik DOC na HTML za pomocą [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metoda
3. Zainicjuj nowy obiekt [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
5. Wyodrębnij zawartość z pliku HTML za pomocą BufferedReader i zapisz zawartość w pliku prezentacji
6. Zapisz dokument w ODP za pomocą metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Do konwersji plików DOC na ODP można łatwo użyć Aspose.Total dla Java bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz biblioteki do swojego pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-doc-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Interfejs API umożliwia również konwersję dokumentów DOC chronionych hasłem na ODP. Jeśli wejściowy dokument DOC jest chroniony hasłem, nie można go przekonwertować do formatu ODP bez użycia hasła. W celu otwarcia zaszyfrowanego dokumentu można ustawić poprawne hasło w obiekcie LoadOptions i przekazać je do konstruktora dokumentu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-doc-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-ppsm/" name="DOC W celu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-pot/" name="DOC W celu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-powerpoint/" name="DOC W celu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-pptx/" name="DOC W celu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-potx/" name="DOC W celu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-pptm/" name="DOC W celu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-potm/" name="DOC W celu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-pps/" name="DOC W celu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-ppsx/" name="DOC W celu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-ppt/" name="DOC W celu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-csv/" name="DOC W celu CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-dif/" name="DOC W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-fods/" name="DOC W celu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-ods/" name="DOC W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-sxc/" name="DOC W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-tsv/" name="DOC W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xlam/" name="DOC W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xltm/" name="DOC W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-excel/" name="DOC W celu EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xls/" name="DOC W celu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xlsb/" name="DOC W celu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xlsm/" name="DOC W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xlsx/" name="DOC W celu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xlt/" name="DOC W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xltm/" name="DOC W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xltx/" name="DOC W celu XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}