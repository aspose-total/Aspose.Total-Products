---
title: Konvertera ODP till JSON-format i Android via Java
description: Analysera ODP till JSON-format i Android via Java utan att använda Microsoft Word eller Excel

family: total
platformtag: cpp
feature: conversion
informat: ODP
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera ODP till JSON-format i Android via Java" h2="Designa Android-program för att exportera ODP till JSON utan att använda Microsoft<sup>&reg;</sup> Word eller Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Du kan konvertera ODP till JSON-format i dina Android-applikationer via [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). Genom att använda API för dokumentmanipulation och konvertering [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), kan du exportera ODP till HTML. Efter det, genom att använda [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), kan du konvertera HTML till JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera ODP till JSON-format i Android" %}}
1. Öppna ODP-filen med klassen [Odpument](https://reference.aspose.com/words/java/com.aspose.words/Odpument)
2. Konvertera ODP till HTML genom att använda [Save](https://reference.aspose.com/words/java/com.aspose.words/Odpument#save(java.lang.String,com.aspose.words.SaveOptions) ) metod
3. Ladda HTML-dokument med hjälp av klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Spara dokumentet i JSON-format med [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metod
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://releases.aspose.com/total/java/) och installera bibliotek i din app.

Alternativt kan du få en ZIP-fil från [downloads](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera skyddad ODP till JSON-format i Android via Java" %}}
Med hjälp av API:et kan du också öppna det lösenordsskyddade dokumentet. Om ditt inmatade ODP-dokument är lösenordsskyddat kan du inte konvertera det till JSON-format utan att använda lösenordet. API:et låter dig öppna det krypterade dokumentet genom att skicka in rätt lösenord i ett LoadOptions-objekt. Följande kodexempel visar hur man öppnar ett krypterat dokument med ett lösenord.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera ODP till JSON i Range i Android via Java" %}}
Medan du konverterar ODP till JSON kan du också ställa in intervallet till ditt utdata-JSON-format. För att ställa in intervallet kan du öppna den konverterade HTML-koden med Workbook-klassen, skapa ett dataområde som ska exporteras med metoden Cells.createRange, anropa metoden JsonUtility.exportRangeToJson med referenser till Range & ExportRangeToJsonOptions och skriva sträng JSON-data till fil via BufferedWriter.write-metoden.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}