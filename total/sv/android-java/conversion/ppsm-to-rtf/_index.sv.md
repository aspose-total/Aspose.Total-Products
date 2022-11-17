---
title: Exportera PPSM till RTF på Andorid via Java
description: Konvertera PPSM till RTF i mobilappar utan att installera någon programvara

family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: RTF
otherformats: DOCX DOCM WORDML DOTM OTT ODT DOTX DOC DOT TEXT FLATOPC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera PPSM till RTF på Andorid via Java" h2="Filformats-API:er för att konvertera PPSM till RTF i Android-appar utan att vara beroende av Microsoft PowerPoint eller Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) tillåter manipulering av filformat i Android-program. Genom att använda API:erna i paketet kan du automatisera konverteringsprocessen från PowerPoint PPSM till Word RTF i dina appar.
Du kan konvertera ditt givna dokument i två steg. Du kan använda [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) som är ett PowerPoint API för Android-applikationer för att rendera PPSM till HTML. Därefter kan du konvertera HTML till RTF genom att använda API för dokumentbearbetning [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSM till RTF-rendering i Android" %}}
1. Öppna PPSM-filen med klassen [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Konvertera PPSM till HTML genom att använda [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-)-metoden och ställ in Html som SaveFormat
3. Ladda den konverterade HTML-filen med klassen [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)
4. Spara dokumentet i RTF-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int)) och ställ in Rtf som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.Slides for Android via Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) och [Aspose.Words for Andorid via Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i din applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("input.ppsm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Rtfument
Rtfument rtfument = new Rtfument("htmlOutput.html");
// save rtfument in RTF format
rtfument.save("output.rtf",SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-rtfx/" name="PPSM Till RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-rtfm/" name="PPSM Till RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-wordml/" name="PPSM Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-dotm/" name="PPSM Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-ott/" name="PPSM Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-odt/" name="PPSM Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-dotx/" name="PPSM Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-rtf/" name="PPSM Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-dot/" name="PPSM Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-text/" name="PPSM Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-flatopc/" name="PPSM Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/ppsm-to-word/" name="PPSM Till WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}