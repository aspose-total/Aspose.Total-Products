---
title: Java API do konwersji DOC na XLSM
description: Konwertuj DOC na XLSM za pomocą Javy bez używania Microsoft Word lub Microsoft Excel
url: /pl/java/conversion/doc-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: XLSM
otherformats: XLSM SXC DIF XLTX XLSX TSV XLAM XLTM FODS ODS XLT XLSM EXCEL XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj DOC na XLSM przez Java" h2="On Premise Java API do konwersji DOC na XLSM bez użycia Microsoft<sup>&reg;</sup> Word lub Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Konwersja DOC do XLSM za pomocą [Aspose.Total for Java](https://products.aspose.com/total/java/) to prosty, dwuetapowy proces. Korzystając z bogatego w funkcje interfejsu API do manipulacji i konwersji dokumentów [Aspose.Words for Java](https://products.aspose.com/words/java/), możesz eksportować DOC do HTML. Następnie, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/), możesz przekonwertować HTML na XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji DOC na XLSM" %}}
1. Otwórz plik DOC za pomocą klasy [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Przekonwertuj DOC na HTML za pomocą [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metoda
3. Załaduj dokument HTML za pomocą klasy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Zapisz dokument w formacie XLSM, używając [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) i [Aspose.Cells for Java](https://docs.aspose.com/cells/java/ instalacja/) w pliku pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Przed przekonwertowaniem DOC na XLSM możesz usunąć nieużywane informacje z dokumentu DOC za pomocą [Aspose.Words for Java](https://products.aspose.com/words/java/). Czasami może być konieczne usunięcie nieużywanych lub zduplikowanych informacji, aby zmniejszyć rozmiar dokumentu wyjściowego i czas przetwarzania. Klasa [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) umożliwia określenie opcji czyszczenia dokumentów. Aby usunąć z dokumentu zduplikowane style lub tylko nieużywane style lub listy, możesz użyć metody [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Możesz użyć [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) i [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) do wykrywania i usuwania stylów oznaczonych jako „nieużywane”.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}(https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions))
{{% blocks/products/pf/feature-page-section  h2="Usuń nieużywane informacje z dokumentu DOC za pomocą Java" %}}
Po przekonwertowaniu DOC na XLSM [Aspose.Cells for Java](https://products.aspose.com/cells/java/) umożliwia zapisanie dokumentu do przesyłania strumieniowego. Jeśli chcesz zapisać pliki w Stream, powinieneś utworzyć obiekt FileOutputStream, a następnie [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) plik do tego obiektu Stream przez wywołanie metody save [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) obiekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xlsm/" name="DOC W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xlt/" name="DOC W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-ods/" name="DOC W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-tsv/" name="DOC W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xls/" name="DOC W celu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xlsb/" name="DOC W celu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-fods/" name="DOC W celu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-dif/" name="DOC W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xltx/" name="DOC W celu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xlam/" name="DOC W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xlsx/" name="DOC W celu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-xltm/" name="DOC W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-sxc/" name="DOC W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/doc-to-excel/" name="DOC W celu EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}