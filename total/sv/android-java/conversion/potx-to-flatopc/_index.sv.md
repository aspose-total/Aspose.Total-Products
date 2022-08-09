---
title: Exportera POTX till FLATOPC på Andorid via Java
description: Konvertera POTX till FLATOPC i mobilappar utan att installera någon programvara
url: /sv/android-java/conversion/potx-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: FLATOPC
otherformats: ODT TEXT WORDML DOCX DOTM DOC DOT RTF WORD DOCM OTT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendera POTX till FLATOPC på Andorid via Java" h2="Filformats-API:er för att konvertera POTX till FLATOPC i Android-appar utan att vara beroende av Microsoft PowerPoint eller Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total för Android via Java](https://products.aspose.com/total/android-java/) tillåter manipulering av filformat i Android-program. Genom att använda API:erna i paketet kan du automatisera konverteringsprocessen från PowerPoint POTX till Word FLATOPC i dina appar.
Du kan konvertera ditt givna dokument i två steg. Du kan använda [Aspose.Slides för Andorid via Java](https://products.aspose.com/slides/android-java/) som är ett PowerPoint API för Android-applikationer för att rendera POTX till HTML. Därefter kan du konvertera HTML till FLATOPC genom att använda API för dokumentbearbetning [Aspose.Words för Android via Java](https://products.aspose.com/words/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTX till FLATOPC-rendering i Android" %}}
1. Öppna POTX-filen med klassen [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Konvertera POTX till HTML genom att använda [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-)-metoden och ställ in Html som SaveFormat
3. Ladda den konverterade HTML-filen med klassen [Flatopcument](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument)
4. Spara dokumentet i FLATOPC-format med metoden [save](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument#save(java.lang.String,int)) och ställ in Flatopc som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.Slides för Android via Java](https://flatopcs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) och [Aspose.Words for Andorid via Java](https://flatopcs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i din applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("input.potx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Flatopcument
Flatopcument flatopcument = new Flatopcument("htmlOutput.html");
// save flatopcument in FLATOPC format
flatopcument.save("output.flatopc",SaveFormat.FlatOpc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-odt/" name="POTX Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-text/" name="POTX Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-wordml/" name="POTX Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-flatopcx/" name="POTX Till FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-dotm/" name="POTX Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-flatopc/" name="POTX Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-dot/" name="POTX Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-rtf/" name="POTX Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-word/" name="POTX Till WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-flatopcm/" name="POTX Till FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-ott/" name="POTX Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/potx-to-dotx/" name="POTX Till DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}