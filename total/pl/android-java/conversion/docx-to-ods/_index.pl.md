---
title: Android API do konwersji DOCX na ODS
description: Konwertuj DOCX na ODS w Androidzie przez Javę bez używania Microsoft Word lub Microsoft Excel
url: /pl/android-java/conversion/docx-to-ods/
family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: ODS
otherformats: XLAM XLTM SXC XLSM XLS XLT XLSX TSV CSV XLTX XLSB FODS EXCEL DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwertuj DOCX na ODS w aplikacjach na Androida" h2="Eksportuj DOCX do ODS w Androidzie przez Javę bez użycia Microsoft<sup>&reg;</sup> Word lub Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total na Androida przez Javę](https://products.aspose.com/total/android-java/) możesz zintegrować funkcję konwersji DOCX na ODS w swoich aplikacjach na Androida. Po pierwsze, możesz przekonwertować DOCX na HTML, korzystając z bogatego w funkcje interfejsu API do manipulacji dokumentami i konwersji [Aspose.Words na Androida przez Javę](https://products.aspose.com/words/android-java/). Następnie, używając [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), możesz przekonwertować HTML na ODS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API do konwersji DOCX na ODS" %}}
1. Otwórz plik DOCX za pomocą klasy [Docxument](https://reference.aspose.com/words/java/com.aspose.words/Docxument)
2. Przekonwertuj DOCX na HTML za pomocą [Save](https://reference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,com.aspose.words.SaveOptions) ) metoda
3. Załaduj dokument HTML za pomocą klasy [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Zapisz dokument w formacie ODS, używając [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metoda
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Możesz łatwo używać Aspose.Total dla Androida przez Javę bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) i zainstaluj [Aspose.Cells dla Androida przez Javę](https://docxs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) i [Aspose.Words dla Androida przez Javę](https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) w swoich aplikacjach.

Możesz też pobrać plik ZIP ze strony [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Usuń nieużywane informacje z dokumentu DOCX w Androidzie za pomocą Java" %}}
Przed przekonwertowaniem DOCX na ODS możesz usunąć nieużywane informacje z dokumentu DOCX za pomocą [Aspose.Words na Androida przez Javę](https://products.aspose.com/words/android-java/). Czasami może być konieczne usunięcie nieużywanych lub zduplikowanych informacji, aby zmniejszyć rozmiar dokumentu wyjściowego i czas przetwarzania. Klasa [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) umożliwia określenie opcji czyszczenia dokumentów. Aby usunąć z dokumentu zduplikowane style lub tylko nieużywane style lub listy, możesz użyć metody [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Docxument#cleanup()). Możesz użyć [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) i [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) do wykrywania i usuwania stylów oznaczonych jako „nieużywane”.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docxument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Zapisz plik ODS, aby przesyłać strumieniowo w systemie Android przez Java" %}}
Po przekonwertowaniu DOCX na ODS [Aspose.Cells na Androida przez Javę](https://products.aspose.com/cells/android-java/) umożliwia zapisanie dokumentu do przesyłania strumieniowego. Jeśli chcesz zapisać pliki w Stream, powinieneś utworzyć obiekt FileOutputStream, a następnie [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) plik do tego obiektu Stream przez wywołanie metody save [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) obiekt.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-xlam/" name="DOCX Do XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-xltm/" name="DOCX Do XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-sxc/" name="DOCX Do SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-xlsm/" name="DOCX Do XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-xls/" name="DOCX Do XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-xlt/" name="DOCX Do XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-xlsx/" name="DOCX Do XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-tsv/" name="DOCX Do TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-ods/" name="DOCX Do ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-xltx/" name="DOCX Do XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-xlsb/" name="DOCX Do XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-fods/" name="DOCX Do FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-excel/" name="DOCX Do EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/android-java/conversion/docx-to-dif/" name="DOCX Do DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}