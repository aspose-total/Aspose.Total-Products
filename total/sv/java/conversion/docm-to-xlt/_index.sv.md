---
title: Java API för att konvertera DOCM till XLT
description: Konvertera DOCM till XLT via Java utan att använda Microsoft Word eller Microsoft Excel
url: /sv/java/conversion/docm-to-xlt/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: XLT
otherformats: XLTM XLT XLAM ODS EXCEL XLT XLSX FODS XLTX SXC XLSB TSV XLSM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera DOCM till XLT via Java" h2="On Premise Java API för att konvertera DOCM till XLT utan att använda Microsoft<sup>&reg;</sup> Word eller Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Att konvertera DOCM till XLT via [Aspose.Total for Java](https://products.aspose.com/total/java/) är en enkel process i två steg. Genom att använda funktionsrika, dokumentmanipulerings- och konverterings-API [Aspose.Words for Java](https://products.aspose.com/words/java/), kan du exportera DOCM till HTML. Efter det, genom att använda [Aspose.Cells for Java](https://products.aspose.com/cells/java/), kan du konvertera HTML till XLT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera DOCM till XLT" %}}
1. Öppna DOCM-filen med klassen [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Konvertera DOCM till HTML genom att använda [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metod
3. Ladda HTML-dokument genom att använda klassen [Arbetsbok](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i XLT-format med [Spara](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera [Aspose.Words for Java](https://docms.aspose.com/words/java/installation/) och [Aspose.Cells for Java](https://docms.aspose.com/cells/java/ installation/) i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}DocumentDocument
Innan du konverterar DOCM till XLT kan du ta bort oanvänd information från DOCM Docmument via [Aspose.Words for Java](https://products.aspose.com/words/java/). Ibland kan du behöva ta bort oanvänd eller dubblerad information för att minska storleken på utdatadokumentet och bearbetningstiden. Klassen [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) låter dig ange alternativ för dokumentrensning. För att ta bort dubbletter av stilar eller bara oanvända stilar eller listor från dokumentet kan du använda metoden [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Docmument#cleanup()). Du kan använda [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) och [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) egenskaper för att upptäcka och ta bort stilar som är markerade som "oanvända".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ta bort oanvänd information från ett DOCM-dokument via Java" %}}
Efter att ha konverterat DOCM till XLT, gör [Aspose.Cells for Java](https://products.aspose.com/cells/java/) det möjligt för dig att spara ditt dokument för att streama. Om du behöver spara filer i en Stream ska du skapa ett FileOutputStream-objekt och sedan [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) filen till det Stream-objektet genom att anropa sparametoden för [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-xlsm/" name="DOCM Till XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-xlt/" name="DOCM Till XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-ods/" name="DOCM Till ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-tsv/" name="DOCM Till TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-xls/" name="DOCM Till XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-xlsb/" name="DOCM Till XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-fods/" name="DOCM Till FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-dif/" name="DOCM Till DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-xltx/" name="DOCM Till XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-xlam/" name="DOCM Till XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-xlsx/" name="DOCM Till XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-xltm/" name="DOCM Till XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-sxc/" name="DOCM Till SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docm-to-excel/" name="DOCM Till EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}