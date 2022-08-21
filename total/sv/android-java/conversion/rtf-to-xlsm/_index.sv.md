---
title: Android API för att konvertera RTF till XLSM
description: Konvertera RTF till XLSM i Android via Java utan att använda Microsoft Word eller Microsoft Excel
url: /sv/android-java/conversion/rtf-to-xlsm/
family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: XLSM
otherformats: XLAM TSV XLT XLTX EXCEL XLTM XLSB XLS CSV ODS FODS SXC DIF XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera RTF till XLSM i Android-applikationer" h2="Exportera RTF till XLSM i Android via Java utan att använda Microsoft<sup>&reg;</sup> Word eller Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) kan du integrera RTF till XLSM-konverteringsfunktionen i dina Android-applikationer. För det första kan du konvertera RTF till HTML genom att använda funktionsrika, dokumentmanipulerings- och konverterings-API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Efter det, genom att använda [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), kan du konvertera HTML till XLSM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API för att konvertera RTF till XLSM" %}}
1. Öppna RTF-filen med klassen [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)
2. Konvertera RTF till HTML genom att använda [Save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,com.aspose.words.SaveOptions) ) metod
3. Ladda HTML-dokument med hjälp av klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i XLSM-format med [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.Cells for Android via Java](https://rtfs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) och [Aspose.Words for Android via Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ta bort oanvänd information från ett RTF-dokument i Android via Java" %}}
Innan du konverterar RTF till XLSM kan du ta bort oanvänd information från RTF Rtfument via [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Ibland kan du behöva ta bort oanvänd eller dubblerad information för att minska storleken på utdatadokumentet och bearbetningstiden. Klassen [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) låter dig ange alternativ för dokumentrensning. För att ta bort dubbletter av stilar eller bara oanvända stilar eller listor från dokumentet kan du använda metoden [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#cleanup()). Du kan använda [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) och [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) egenskaper för att upptäcka och ta bort stilar som är markerade som "oanvända".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-rtfument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Spara XLSM-fil för att streama i Android via Java" %}}
Efter att ha konverterat RTF till XLSM, gör [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) dig att spara ditt dokument för att streama. Om du behöver spara filer i en Stream bör du skapa ett FileOutputStream-objekt och sedan [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) filen till det Stream-objektet genom att anropa sparametoden för [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-xlam/" name="RTF Till XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-tsv/" name="RTF Till TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-xlt/" name="RTF Till XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-xltx/" name="RTF Till XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-excel/" name="RTF Till EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-xltm/" name="RTF Till XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-xlsb/" name="RTF Till XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-xls/" name="RTF Till XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-xlsm/" name="RTF Till XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-ods/" name="RTF Till ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-fods/" name="RTF Till FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-sxc/" name="RTF Till SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-dif/" name="RTF Till DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/rtf-to-xlsx/" name="RTF Till XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}