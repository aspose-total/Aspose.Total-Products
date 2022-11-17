---
title: Exportera POWERPOINT till TEXT på Andorid via Java
description: Konvertera POWERPOINT till TEXT i mobilappar utan att installera någon programvara

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: TEXT
otherformats: WORDML OTT DOT FLATOPC DOCM DOTX DOCX DOC ODT DOTM WORD RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera POWERPOINT till TEXT på Andorid via Java" h2="Filformats-API:er för att konvertera POWERPOINT till TEXT i Android-appar utan att vara beroende av Microsoft PowerPoint eller Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) tillåter manipulering av filformat i Android-program. Genom att använda API:erna i paketet kan du automatisera konverteringsprocessen från PowerPoint POWERPOINT till Word TEXT i dina appar.
Du kan konvertera ditt givna dokument i två steg. Du kan använda [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) som är ett PowerPoint API för Android-applikationer för att rendera POWERPOINT till HTML. Därefter kan du konvertera HTML till TEXT genom att använda API för dokumentbearbetning [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POWERPOINT till TEXT-rendering i Android" %}}
1. Öppna POWERPOINT-filen med klassen [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Konvertera POWERPOINT till HTML genom att använda [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-)-metoden och ställ in Html som SaveFormat
3. Ladda den konverterade HTML-filen med klassen [Textument](https://reference.aspose.com/words/java/com.aspose.words/Textument)
4. Spara dokumentet i TEXT-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Textument#save(java.lang.String,int)) och ställ in Text som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.Slides for Android via Java](https://texts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) och [Aspose.Words for Andorid via Java](https://texts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i din applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Textument
Textument textument = new Textument("htmlOutput.html");
// save textument in TEXT format
textument.save("output.text",SaveFormat.Text);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-wordml/" name="PPTX Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-ott/" name="PPTX Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-dot/" name="PPTX Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-flatopc/" name="PPTX Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-textm/" name="PPTX Till TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-dotx/" name="PPTX Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-textx/" name="PPTX Till TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-text/" name="PPTX Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-odt/" name="PPTX Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-dotm/" name="PPTX Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-word/" name="PPTX Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/pptx-to-rtf/" name="PPTX Till RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}