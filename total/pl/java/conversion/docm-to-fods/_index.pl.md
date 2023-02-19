---
title: Java API do konwersji DOCM na FODS
description: Konwertuj DOCM na FODS za pomocą Javy bez używania Microsoft Word lub Microsoft Excel
url_ignore: /pl/java/conversion/docm-to-fods/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: FODS
otherformats: XLSM SXC ODS FODS XLS EXCEL TSV XLTX XLSB XLTM XLSX XLT XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj DOCM na FODS przez Java" h2="On Premise Java API do konwersji DOCM na FODS bez użycia Microsoft<sup>&reg;</sup> Word lub Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Konwersja DOCM do FODS za pomocą [Aspose.Total for Java](https://products.aspose.com/total/java/) to prosty, dwuetapowy proces. Korzystając z bogatego w funkcje interfejsu API do manipulacji i konwersji dokumentów [Aspose.Words for Java](https://products.aspose.com/words/java/), możesz eksportować DOCM do HTML. Następnie, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/), możesz przekonwertować HTML na FODS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji DOCM na FODS" %}}
1. Otwórz plik DOCM za pomocą klasy [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Przekonwertuj DOCM na HTML za pomocą [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metoda
3. Załaduj dokument HTML za pomocą klasy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Zapisz dokument w formacie FODS, używając [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://releases.aspose.com/total/java/) i dołącz [Aspose.Words for Java](https://docms.aspose.com/words/java/installation/) i [Aspose.Cells for Java](https://docms.aspose.com/cells/java/installation/) w pliku pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Darmowy konwerter online dla DOCM na FODS</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=fods&from=docm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}Document
Przed przekonwertowaniem DOCM na FODS możesz usunąć nieużywane informacje z dokumentu DOCM za pomocą [Aspose.Words for Java](https://products.aspose.com/words/java/). Czasami może być konieczne usunięcie nieużywanych lub zduplikowanych informacji, aby zmniejszyć rozmiar dokumentu wyjściowego i czas przetwarzania. Klasa [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) umożliwia określenie opcji czyszczenia dokumentów. Aby usunąć z dokumentu zduplikowane style lub tylko nieużywane style lub listy, możesz użyć metody [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Możesz użyć [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) i [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) do wykrywania i usuwania stylów oznaczonych jako „nieużywane”.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-documentjava" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Usuń nieużywane informacje z dokumentu DOCM za pomocą Java" %}}
Po przekonwertowaniu DOCM na FODS [Aspose.Cells for Java](https://products.aspose.com/cells/java/) umożliwia zapisanie dokumentu do przesyłania strumieniowego. Jeśli chcesz zapisać pliki w Stream, powinieneś utworzyć obiekt FileOutputStream, a następnie [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) plik do tego obiektu Stream przez wywołanie metody save [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) obiekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-xlsm/" name="DOCM W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-xlt/" name="DOCM W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-ods/" name="DOCM W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-tsv/" name="DOCM W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-xls/" name="DOCM W celu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-xlsb/" name="DOCM W celu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-fods/" name="DOCM W celu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-dif/" name="DOCM W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-xltx/" name="DOCM W celu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-xlam/" name="DOCM W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-xlsx/" name="DOCM W celu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-xltm/" name="DOCM W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-sxc/" name="DOCM W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/docm-to-excel/" name="DOCM W celu EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}