---
title: Java API för att konvertera DOCX till XLAM
description: Konvertera DOCX till XLAM via Java utan att använda Microsoft Word eller Microsoft Excel
url: /sv/java/conversion/docx-to-xlam/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: XLAM
otherformats: XLAM EXCEL XLT XLSM DIF SXC XLTM FODS XLTX XLS ODS TSV XLSX XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera DOCX till XLAM via Java" h2="On Premise Java API för att konvertera DOCX till XLAM utan att använda Microsoft<sup>&reg;</sup> Word eller Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Att konvertera DOCX till XLAM via [Aspose.Total for Java](https://products.aspose.com/total/java/) är en enkel process i två steg. Genom att använda funktionsrika, dokumentmanipulerings- och konverterings-API [Aspose.Words for Java](https://products.aspose.com/words/java/), kan du exportera DOCX till HTML. Efter det, genom att använda [Aspose.Cells for Java](https://products.aspose.com/cells/java/), kan du konvertera HTML till XLAM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API för att konvertera DOCX till XLAM" %}}
1. Öppna DOCX-filen med klassen [Docxument](https://apireference.aspose.com/words/java/com.aspose.words/Docxument)
2. Konvertera DOCX till HTML genom att använda [Save](https://apireference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,com.aspose.words.SaveOptions) ) metod
3. Ladda HTML-dokument genom att använda klassen [Arbetsbok](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i XLAM-format med [Spara](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera [Aspose.Words for Java](https://docxs.aspose.com/words/java/installation/) och [Aspose.Cells for Java](https://docxs.aspose.com/cells/java/ installation/) i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
Innan du konverterar DOCX till XLAM kan du ta bort oanvänd information från DOCX Docxument via [Aspose.Words for Java](https://products.aspose.com/words/java/). Ibland kan du behöva ta bort oanvänd eller dubblerad information för att minska storleken på utdatadokumentet och bearbetningstiden. Klassen [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) låter dig ange alternativ för dokumentrensning. För att ta bort dubbletter av stilar eller bara oanvända stilar eller listor från dokumentet kan du använda metoden [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Docxument#cleanup()). Du kan använda [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) och [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) egenskaper för att upptäcka och ta bort stilar som är markerade som "oanvända".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docxument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ta bort oanvänd information från ett DOCX-dokument via Java" %}}
Efter att ha konverterat DOCX till XLAM, gör [Aspose.Cells for Java](https://products.aspose.com/cells/java/) det möjligt för dig att spara ditt dokument för att streama. Om du behöver spara filer i en Stream ska du skapa ett FileOutputStream-objekt och sedan [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) filen till det Stream-objektet genom att anropa sparametoden för [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-xlsm/" name="DOCX Till XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-xlt/" name="DOCX Till XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-ods/" name="DOCX Till ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-tsv/" name="DOCX Till TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-xls/" name="DOCX Till XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-xlsb/" name="DOCX Till XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-fods/" name="DOCX Till FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-dif/" name="DOCX Till DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-xltx/" name="DOCX Till XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-xlam/" name="DOCX Till XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-xlsx/" name="DOCX Till XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-xltm/" name="DOCX Till XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-sxc/" name="DOCX Till SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/docx-to-excel/" name="DOCX Till EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}