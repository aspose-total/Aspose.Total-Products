---
title: Android API för att konvertera DOTM till XLS
description: Konvertera DOTM till XLS i Android via Java utan att använda Microsoft Word eller Microsoft Excel
url: /sv/android-java/conversion/dotm-to-xls/
family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: XLS
otherformats: XLSM XLTX XLSB XLTM CSV FODS ODS SXC DIF XLAM TSV XLSX XLT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera DOTM till XLS i Android-applikationer" h2="Exportera DOTM till XLS i Android via Java utan att använda Microsoft<sup>&reg;</sup> Word eller Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) kan du integrera DOTM till XLS-konverteringsfunktionen i dina Android-applikationer. För det första kan du konvertera DOTM till HTML genom att använda funktionsrika, dokumentmanipulerings- och konverterings-API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Efter det, genom att använda [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), kan du konvertera HTML till XLS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API för att konvertera DOTM till XLS" %}}
1. Öppna DOTM-filen med klassen [Dotmument](https://reference.aspose.com/words/java/com.aspose.words/Dotmument)
2. Konvertera DOTM till HTML genom att använda [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,com.aspose.words.SaveOptions) ) metod
3. Ladda HTML-dokument med hjälp av klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i XLS-format med [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.Cells for Android via Java](https://dotms.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) och [Aspose.Words for Android via Java](https://dotms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ta bort oanvänd information från ett DOTM-dokument i Android via Java" %}}
Innan du konverterar DOTM till XLS kan du ta bort oanvänd information från DOTM Dotmument via [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Ibland kan du behöva ta bort oanvänd eller dubblerad information för att minska storleken på utdatadokumentet och bearbetningstiden. Klassen [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) låter dig ange alternativ för dokumentrensning. För att ta bort dubbletter av stilar eller bara oanvända stilar eller listor från dokumentet kan du använda metoden [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#cleanup()). Du kan använda [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) och [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) egenskaper för att upptäcka och ta bort stilar som är markerade som "oanvända".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotmument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Spara XLS-fil för att streama i Android via Java" %}}
Efter att ha konverterat DOTM till XLS, gör [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) dig att spara ditt dokument för att streama. Om du behöver spara filer i en Stream bör du skapa ett FileOutputStream-objekt och sedan [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) filen till det Stream-objektet genom att anropa sparametoden för [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-xlsm/" name="DOTM Till XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-xltx/" name="DOTM Till XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-xlsb/" name="DOTM Till XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-xltm/" name="DOTM Till XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-xls/" name="DOTM Till XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-fods/" name="DOTM Till FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-ods/" name="DOTM Till ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-sxc/" name="DOTM Till SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-dif/" name="DOTM Till DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-xlam/" name="DOTM Till XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-tsv/" name="DOTM Till TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-xlsx/" name="DOTM Till XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-xlt/" name="DOTM Till XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/dotm-to-excel/" name="DOTM Till EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}