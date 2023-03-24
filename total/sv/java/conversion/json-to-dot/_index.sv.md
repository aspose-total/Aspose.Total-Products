---
title: Konvertera JSON-format till DOT via Java
description: Analysera JSON till DOT i Java utan att använda Microsoft Word
url_ignore: /sv/java/conversion/json-to-dot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOT
otherformats: RTF FLATOPC ODT DOTX WORDML PCL DOC EPUB OTT WORD PS MOBI DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertera JSON-format till DOT via Java" h2="På premiss Java API för att tolka JSON till DOT utan att använda Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Genom att använda [Aspose.Total for Java](https://products.aspose.com/total/java/) kan du konvertera JSON till DOT i dina Java-applikationer i tvåstegsprocess. För det första, genom att använda [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kan du tolka JSON till PDF. I det andra steget kan du konvertera PDF till DOT genom att använda Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera JSON-format till DOT via Java" %}}
1. Skapa ett nytt [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt och läs giltig JSON-data från filen
2. Importera JSON-fil till kalkylblad med klassen [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) och [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) den som PDF
3. Ladda PDF-dokument genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Spara dokumentet i DOT-format med [Spara](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Java direkt från ett [Maven](https://releases.aspose.com/total/java/) baserat projekt och inkludera bibliotek i din pom.xml.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konverteringskrav" %}}
Dessutom tillåter API:et dig att ställa in layoutalternativ för din JSON medan du analyserar JSON till DOT med [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Det låter dig bearbeta Array som en tabell, ignorera nollvärden, ignorera arraytitel, ignorera objekttitel, konvertera sträng till nummer eller datum, ställa in datum och nummerformat och ställa in titelstil. Alla dessa alternativ låter dig presentera din data enligt dina behov. Följande kodavsnitt visar hur du ställer in layoutalternativen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ställ in layout och konvertera JSON-format till DOT via Java" %}}
Med hjälp av API:t kan du också analysera JSON till DOT med vattenstämpel. För att lägga till en vattenstämpel till ditt DOT-dokument kan du först konvertera JSON-filen till PDF och lägga till en vattenstämpel till den. För att lägga till en vattenstämpel, ladda den nyskapade PDF-filen med klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), skapa en instans av TextWatermarkOptions och ställ in dess egenskaper, anrop Watermark.setText-metoden och skicka vattenstämpeltext och objekt av TextWatermarkOptions. Efter att ha lagt till vattenstämpeln kan du spara dokumentet i DOT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}