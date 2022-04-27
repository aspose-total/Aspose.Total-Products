---
title: Konvertera DOC till JSON-format via Java
description: Konvertera DOC till JSON-format via Java utan att använda Microsoft Word eller Microsoft Excel
url: /sv/java/conversion/doc-to-json/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera DOC till JSON-format via Java" h2="On Premise Java API för att konvertera DOC till JSON utan att använda Microsoft<sup>&reg;</sup> Word eller Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Att konvertera DOC till JSON-format via [Aspose.Total for Java](https://products.aspose.com/total/java/) är en enkel process i två steg. Genom att använda funktionsrika, dokumentmanipulerings- och konverterings-API [Aspose.Words for Java](https://products.aspose.com/words/java/), kan du exportera DOC till HTML. Efter det, genom att använda [Aspose.Cells for Java](https://products.aspose.com/cells/java/), kan du konvertera HTML till JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera DOC till JSON-format via Java" %}}
1. Öppna DOC-filen med klassen [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Konvertera DOC till HTML genom att använda [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metod
3. Ladda HTML-dokument genom att använda klassen [Arbetsbok](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i JSON-format med [Spara](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) baserat projekt och inkludera bibliotek i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
Med hjälp av API:t kan du också öppna det lösenordsskyddade dokumentet. Om ditt inmatade DOC-dokument är lösenordsskyddat kan du inte konvertera det till JSON-format utan att använda lösenordet. API:et låter dig öppna det krypterade dokumentet genom att skicka in rätt lösenord i ett LoadOptions-objekt. Följande kodexempel visar hur du försöker öppna ett krypterat dokument med ett lösenord:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konvertera skyddad DOC till JSON-format via Java" %}}
Medan du konverterar DOC till JSON kan du också ställa in intervallet för ditt utdata-JSON-format. För att ställa in intervallet kan du öppna den konverterade HTML-koden med Workbook-klassen, skapa ett dataområde som ska exporteras med metoden Cells.createRange, anropa metoden JsonUtility.exportRangeToJson med referenser till Range & ExportRangeToJsonOptions och skriva sträng JSON-data till fil via BufferedWriter.write-metoden. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-xlam/" name="DOC Till XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-xlt/" name="DOC Till XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-csv/" name="DOC Till CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-xlsx/" name="DOC Till XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-fods/" name="DOC Till FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-xltm/" name="DOC Till XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-xlsm/" name="DOC Till XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-xltx/" name="DOC Till XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-ods/" name="DOC Till ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-xlsb/" name="DOC Till XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-excel/" name="DOC Till EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-sxc/" name="DOC Till SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-tsv/" name="DOC Till TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/doc-to-dif/" name="DOC Till DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}