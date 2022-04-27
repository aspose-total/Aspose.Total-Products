---
title: Java API för att konvertera OTT till XLSM
description: Konvertera OTT till XLSM via Java utan att använda Microsoft Word eller Microsoft Excel
url: /sv/java/conversion/ott-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: XLSM
otherformats: EXCEL XLT XLSX TSV XLTX SXC XLSB ODS XLSM XLS XLTM FODS XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera OTT till XLSM via Java" h2="On Premise Java API för att konvertera OTT till XLSM utan att använda Microsoft<sup>&reg;</sup> Word eller Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Att konvertera OTT till XLSM via [Aspose.Total for Java](https://products.aspose.com/total/java/) är en enkel process i två steg. Genom att använda funktionsrika, dokumentmanipulerings- och konverterings-API [Aspose.Words for Java](https://products.aspose.com/words/java/), kan du exportera OTT till HTML. Efter det, genom att använda [Aspose.Cells for Java](https://products.aspose.com/cells/java/), kan du konvertera HTML till XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera OTT till XLSM" %}}
1. Öppna OTT-filen med klassen [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Konvertera OTT till HTML genom att använda [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metod
3. Ladda HTML-dokument genom att använda klassen [Arbetsbok](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i XLSM-format med [Spara](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera [Aspose.Words for Java](https://otts.aspose.com/words/java/installation/) och [Aspose.Cells for Java](https://otts.aspose.com/cells/java/ installation/) i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}/Document
Innan du konverterar OTT till XLSM kan du ta bort oanvänd information från OTT Ottument via [Aspose.Words for Java](https://products.aspose.com/words/java/). Ibland kan du behöva ta bort oanvänd eller dubblerad information för att minska storleken på utdatadokumentet och bearbetningstiden. Klassen [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) låter dig ange alternativ för dokumentrensning. För att ta bort dubbletter av stilar eller bara oanvända stilar eller listor från dokumentet kan du använda metoden [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Ottument#cleanup()). Du kan använda [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) och [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) egenskaper för att upptäcka och ta bort stilar som är markerade som "oanvända".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-ottument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ta bort oanvänd information från ett OTT-dokument via Java" %}}
Efter att ha konverterat OTT till XLSM, gör [Aspose.Cells for Java](https://products.aspose.com/cells/java/) det möjligt för dig att spara ditt dokument för att streama. Om du behöver spara filer i en Stream ska du skapa ett FileOutputStream-objekt och sedan [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) filen till det Stream-objektet genom att anropa sparametoden för [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-xlsm/" name="OTT Till XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-xlt/" name="OTT Till XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-ods/" name="OTT Till ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-tsv/" name="OTT Till TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-xls/" name="OTT Till XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-xlsb/" name="OTT Till XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-fods/" name="OTT Till FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-dif/" name="OTT Till DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-xltx/" name="OTT Till XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-xlam/" name="OTT Till XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-xlsx/" name="OTT Till XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-xltm/" name="OTT Till XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-sxc/" name="OTT Till SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/ott-to-excel/" name="OTT Till EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}