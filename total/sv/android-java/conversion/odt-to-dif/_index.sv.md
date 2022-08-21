---
title: Android API för att konvertera ODT till DIF
description: Konvertera ODT till DIF i Android via Java utan att använda Microsoft Word eller Microsoft Excel
url: /sv/android-java/conversion/odt-to-dif/
family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: DIF
otherformats: XLSM XLAM XLSB SXC EXCEL CSV XLS FODS ODS TSV XLTX XLTM XLSX XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera ODT till DIF i Android-applikationer" h2="Exportera ODT till DIF i Android via Java utan att använda Microsoft<sup>&reg;</sup> Word eller Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) kan du integrera ODT till DIF-konverteringsfunktionen i dina Android-applikationer. För det första kan du konvertera ODT till HTML genom att använda funktionsrika, dokumentmanipulerings- och konverterings-API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Efter det, genom att använda [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), kan du konvertera HTML till DIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API för att konvertera ODT till DIF" %}}
1. Öppna ODT-filen med klassen [Odtument](https://reference.aspose.com/words/java/com.aspose.words/Odtument)
2. Konvertera ODT till HTML genom att använda [Save](https://reference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,com.aspose.words.SaveOptions) ) metod
3. Ladda HTML-dokument med hjälp av klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i DIF-format med [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.Cells for Android via Java](https://odts.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) och [Aspose.Words for Android via Java](https://odts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ta bort oanvänd information från ett ODT-dokument i Android via Java" %}}
Innan du konverterar ODT till DIF kan du ta bort oanvänd information från ODT Odtument via [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Ibland kan du behöva ta bort oanvänd eller dubblerad information för att minska storleken på utdatadokumentet och bearbetningstiden. Klassen [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) låter dig ange alternativ för dokumentrensning. För att ta bort dubbletter av stilar eller bara oanvända stilar eller listor från dokumentet kan du använda metoden [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Odtument#cleanup()). Du kan använda [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) och [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) egenskaper för att upptäcka och ta bort stilar som är markerade som "oanvända".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-odtument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Spara DIF-fil för att streama i Android via Java" %}}
Efter att ha konverterat ODT till DIF, gör [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) dig att spara ditt dokument för att streama. Om du behöver spara filer i en Stream bör du skapa ett FileOutputStream-objekt och sedan [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) filen till det Stream-objektet genom att anropa sparametoden för [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-xlsm/" name="ODT Till XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-xlam/" name="ODT Till XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-xlsb/" name="ODT Till XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-sxc/" name="ODT Till SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-excel/" name="ODT Till EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-dif/" name="ODT Till DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-xls/" name="ODT Till XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-fods/" name="ODT Till FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-ods/" name="ODT Till ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-tsv/" name="ODT Till TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-xltx/" name="ODT Till XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-xltm/" name="ODT Till XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-xlsx/" name="ODT Till XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/odt-to-xlt/" name="ODT Till XLT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}