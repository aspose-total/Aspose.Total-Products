---
title: Java API do konwersji OTT na XLSM
description: Konwertuj OTT na XLSM za pomocą Javy bez używania Microsoft Word lub Microsoft Excel
url: /pl/java/conversion/ott-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: XLSM
otherformats: EXCEL XLT XLSX TSV XLTX SXC XLSB ODS XLSM XLS XLTM FODS XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj OTT na XLSM przez Java" h2="On Premise Java API do konwersji OTT na XLSM bez użycia Microsoft<sup>&reg;</sup> Word lub Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Konwersja OTT do XLSM za pomocą [Aspose.Total for Java](https://products.aspose.com/total/java/) to prosty, dwuetapowy proces. Korzystając z bogatego w funkcje interfejsu API do manipulacji i konwersji dokumentów [Aspose.Words for Java](https://products.aspose.com/words/java/), możesz eksportować OTT do HTML. Następnie, używając [Aspose.Cells for Java](https://products.aspose.com/cells/java/), możesz przekonwertować HTML na XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji OTT na XLSM" %}}
1. Otwórz plik OTT za pomocą klasy [Ottument](https://apireference.aspose.com/words/java/com.aspose.words/Ottument)
2. Przekonwertuj OTT na HTML za pomocą [Save](https://apireference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,com.aspose.words.SaveOptions) ) metoda
3. Załaduj dokument HTML za pomocą klasy [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Zapisz dokument w formacie XLSM, używając [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo użyć Aspose.Total for Java bezpośrednio z projektu opartego na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i dołącz [Aspose.Words for Java](https://otts.aspose.com/words/java/installation/) i [Aspose.Cells for Java](https://otts.aspose.com/cells/java/ instalacja/) w pliku pom.xml.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Wymagania dotyczące konwersji" %}}
Przed przekonwertowaniem OTT na XLSM możesz usunąć nieużywane informacje z dokumentu OTT za pomocą [Aspose.Words for Java](https://products.aspose.com/words/java/). Czasami może być konieczne usunięcie nieużywanych lub zduplikowanych informacji, aby zmniejszyć rozmiar dokumentu wyjściowego i czas przetwarzania. Klasa [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) umożliwia określenie opcji czyszczenia dokumentów. Aby usunąć z dokumentu zduplikowane style lub tylko nieużywane style lub listy, możesz użyć metody [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Ottument#cleanup()). Możesz użyć [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) i [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) do wykrywania i usuwania stylów oznaczonych jako „nieużywane”.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-ottument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Usuń nieużywane informacje z dokumentu OTT za pomocą Java" %}}
Po przekonwertowaniu OTT na XLSM [Aspose.Cells for Java](https://products.aspose.com/cells/java/) umożliwia zapisanie dokumentu do przesyłania strumieniowego. Jeśli chcesz zapisać pliki w Stream, powinieneś utworzyć obiekt FileOutputStream, a następnie [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) plik do tego obiektu Stream przez wywołanie metody save [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) obiekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-xlsm/" name="OTT W celu XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-xlt/" name="OTT W celu XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-ods/" name="OTT W celu ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-tsv/" name="OTT W celu TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-xls/" name="OTT W celu XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-xlsb/" name="OTT W celu XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-fods/" name="OTT W celu FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-dif/" name="OTT W celu DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-xltx/" name="OTT W celu XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-xlam/" name="OTT W celu XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-xlsx/" name="OTT W celu XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-xltm/" name="OTT W celu XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-sxc/" name="OTT W celu SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/ott-to-excel/" name="OTT W celu EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}