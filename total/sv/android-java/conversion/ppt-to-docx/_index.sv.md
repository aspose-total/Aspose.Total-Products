---
title: Exportera PPT till DOCX på Andorid via Java
description: Konvertera PPT till DOCX i mobilappar utan att installera någon programvara
url: /sv/android-java/conversion/ppt-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOCX
otherformats: TEXT DOTM ODT WORDML DOTX DOC DOT WORD OTT DOCM RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera PPT till DOCX på Andorid via Java" h2="Filformats-API:er för att konvertera PPT till DOCX i Android-appar utan att vara beroende av Microsoft PowerPoint eller Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total för Android via Java](https://products.aspose.com/total/android-java/) tillåter manipulering av filformat i Android-program. Genom att använda API:erna i paketet kan du automatisera konverteringsprocessen från PowerPoint PPT till Word DOCX i dina appar.
Du kan konvertera ditt givna dokument i två steg. Du kan använda [Aspose.Slides för Andorid via Java](https://products.aspose.com/slides/android-java/) som är ett PowerPoint API för Android-applikationer för att rendera PPT till HTML. Därefter kan du konvertera HTML till DOCX genom att använda API för dokumentbearbetning [Aspose.Words för Android via Java](https://products.aspose.com/words/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPT till DOCX-rendering i Android" %}}
1. Öppna PPT-filen med klassen [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Konvertera PPT till HTML genom att använda [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-)-metoden och ställ in Html som SaveFormat
3. Ladda den konverterade HTML-filen med klassen [Docxument](https://reference.aspose.com/words/java/com.aspose.words/Docxument)
4. Spara dokumentet i DOCX-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,int)) och ställ in Docx som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.Slides för Android via Java](https://docxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) och [Aspose.Words for Andorid via Java](https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i din applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("input.ppt");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Docxument
Docxument docxument = new Docxument("htmlOutput.html");
// save docxument in DOCX format
docxument.save("output.docx",SaveFormat.Docxx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-text/" name="PPT Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-dotm/" name="PPT Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-odt/" name="PPT Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-wordml/" name="PPT Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-dotx/" name="PPT Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-docx/" name="PPT Till DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-dot/" name="PPT Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-word/" name="PPT Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-ott/" name="PPT Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-docxm/" name="PPT Till DOCXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-rtf/" name="PPT Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppt-to-flatopc/" name="PPT Till FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}