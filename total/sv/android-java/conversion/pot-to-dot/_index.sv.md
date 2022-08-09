---
title: Exportera POT till DOT på Andorid via Java
description: Konvertera POT till DOT i mobilappar utan att installera någon programvara
url: /sv/android-java/conversion/pot-to-dot/
family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: DOT
otherformats: DOCM DOCX OTT TEXT ODT WORDML DOC FLATOPC DOTM RTF WORD DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera POT till DOT på Andorid via Java" h2="Filformats-API:er för att konvertera POT till DOT i Android-appar utan att vara beroende av Microsoft PowerPoint eller Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total för Android via Java](https://products.aspose.com/total/android-java/) tillåter manipulering av filformat i Android-program. Genom att använda API:erna i paketet kan du automatisera konverteringsprocessen från PowerPoint POT till Word DOT i dina appar.
Du kan konvertera ditt givna dokument i två steg. Du kan använda [Aspose.Slides för Andorid via Java](https://products.aspose.com/slides/android-java/) som är ett PowerPoint API för Android-applikationer för att rendera POT till HTML. Därefter kan du konvertera HTML till DOT genom att använda API för dokumentbearbetning [Aspose.Words för Android via Java](https://products.aspose.com/words/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POT till DOT-rendering i Android" %}}
1. Öppna POT-filen med klassen [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Konvertera POT till HTML genom att använda [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-)-metoden och ställ in Html som SaveFormat
3. Ladda den konverterade HTML-filen med klassen [Dotument](https://reference.aspose.com/words/java/com.aspose.words/Dotument)
4. Spara dokumentet i DOT-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,int)) och ställ in Dot som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.Slides för Android via Java](https://dots.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) och [Aspose.Words for Andorid via Java](https://dots.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i din applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("input.pot");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotument
Dotument dotument = new Dotument("htmlOutput.html");
// save dotument in DOT format
dotument.save("output.dot",SaveFormat.Dot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-dotm/" name="POT Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-dotx/" name="POT Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-ott/" name="POT Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-text/" name="POT Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-odt/" name="POT Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-wordml/" name="POT Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-dot/" name="POT Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-flatopc/" name="POT Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-dotm/" name="POT Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-rtf/" name="POT Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-word/" name="POT Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pot-to-dotx/" name="POT Till DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}