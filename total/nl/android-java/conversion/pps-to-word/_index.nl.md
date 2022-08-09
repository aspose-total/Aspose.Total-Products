---
title: Exporteer PPS naar WORD op Andorid via Java
description: Converteer PPS naar WORD in mobiele apps zonder software te installeren
url: /nl/android-java/conversion/pps-to-word/
family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOCX
otherformats: FLATOPC ODT DOCM TEXT DOTM DOTX DOCX DOT RTF WORDML DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PPS naar WORD op Andorid via Java" h2="Bestandsformaat-API's om PPS naar WORD te converteren binnen Android-apps zonder afhankelijk te zijn van Microsoft PowerPoint of Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total voor Android via Java](https://products.aspose.com/total/android-java/) maakt het manipuleren van bestandsindelingen binnen Android-applicaties mogelijk. Door de API's in het pakket te gebruiken, kunt u het conversieproces van PowerPoint PPS naar Word WORD in uw apps automatiseren.
U kunt uw opgegeven wordument in twee stappen converteren. U kunt [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) gebruiken, een PowerPoint-API voor Android-toepassingen om PPS naar HTML weer te geven. Daarna kunt u met behulp van de wordumentverwerkings-API [Aspose.Words voor Android via Java](https://products.aspose.com/words/android-java/) de HTML naar WORD converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPS naar WORD-weergave in Android" %}}
1. Open het PPS-bestand met de klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converteer PPS naar HTML met behulp van [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) methode en stel Html in als SaveFormat
3. Laad het geconverteerde HTML-bestand met de klasse [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument)
4. Sla het wordument op in WORD-indeling met de methode [save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,int)) en stel Word in als OpslaanFormaat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.Slides voor Android via Java](https://words.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) en [Aspose.Words voor Andorid via Java](https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Wordument
Wordument wordument = new Wordument("htmlOutput.html");
// save wordument in WORDX format
wordument.save("output.wordx",SaveFormat.Wordx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-flatopc/" name="PPS Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-odt/" name="PPS Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-wordm/" name="PPS Tot WORDM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-text/" name="PPS Tot TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-dotm/" name="PPS Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-dotx/" name="PPS Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-wordx/" name="PPS Tot WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-dot/" name="PPS Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-rtf/" name="PPS Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-wordml/" name="PPS Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-word/" name="PPS Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pps-to-ott/" name="PPS Tot OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}