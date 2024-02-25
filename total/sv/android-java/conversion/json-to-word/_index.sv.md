---
title: Konvertera JSON-format till WORD i Android via Java
description: Analysera JSON till WORD i Java utan att använda Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: WORD
otherformats: DOT PS RTF MOBI EPUB WORDML DOTX CHM OTT PCL DOCM FLATOPC DOC ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera JSON-format till WORD i Android-applikationer" h2="Analysera JSON till WORD i Android-applikationer utan att använda Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Du kan konvertera JSON till WORD i dina Android-applikationer i tvåstegsprocess. För det första, genom att använda Powerful Spreadsheet Processing API [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) kan du tolka JSON till PDF. I det andra steget kan du konvertera PDF till WORD genom att använda Word Processing API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Båda API:erna faller under produktfamiljen [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera JSON-format till WORD i Android via Java" %}}
1. Skapa ett nytt [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objekt och läs giltig JSON-data från filen
2. Importera JSON-fil till kalkylblad med klassen [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) och [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) den som PDF
3. Ladda PDF-dokument med hjälp av klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Spara dokumentet i WORD-format med [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://releases.aspose.com/total/java/) och installera bibliotek i din app.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ställ in layout och konvertera JSON-format till WORD i Android via Java" %}}
Dessutom låter API:et dig ställa in layoutalternativ för ditt JSON-format medan du analyserar JSON till WORD med [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Den låter dig bearbeta Array som en tabell, ignorera nollvärden, ignorera arraytitel, ignorera objekttitel, konvertera sträng till nummer eller datum, ställa in datum och nummerformat och ställa in titelstil. Alla dessa alternativ låter dig presentera din data enligt dina behov. Följande kodavsnitt visar hur du ställer in layoutalternativen.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera JSON-format till WORD med vattenstämpel i Android via Java" %}}
Med hjälp av API:t kan du också konvertera JSON till WORD med vattenstämpel. För att lägga till en vattenstämpel till ditt WORD-dokument kan du först analysera JSON-filen till PDF och lägga till en vattenstämpel till den. För att lägga till en vattenstämpel, ladda den nyskapade PDF-filen med klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), skapa en instans av TextWatermarkOptions och ställ in dess egenskaper, anrop Watermark.setText-metoden och skicka vattenstämpeltext och objekt av TextWatermarkOptions. När du har lagt till vattenstämpeln kan du spara dokumentet i WORD.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}