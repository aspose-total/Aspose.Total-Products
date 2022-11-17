---
title: Exporteer PPSM naar TEXT op Andorid via Java
description: Converteer PPSM naar TEXT in mobiele apps zonder software te installeren

family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: TEXT
otherformats: DOTX DOT DOCX DOTM RTF FLATOPC DOCM WORDML ODT OTT WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PPSM naar TEXT op Andorid via Java" h2="Bestandsformaat-API's om PPSM naar TEXT te converteren binnen Android-apps zonder afhankelijk te zijn van Microsoft PowerPoint of Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) maakt het manipuleren van bestandsindelingen binnen Android-applicaties mogelijk. Door de API's in het pakket te gebruiken, kunt u het conversieproces van PowerPoint PPSM naar Word TEXT in uw apps automatiseren.
U kunt uw opgegeven textument in twee stappen converteren. U kunt [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) gebruiken, een PowerPoint-API voor Android-toepassingen om PPSM naar HTML weer te geven. Daarna kunt u met behulp van de textumentverwerkings-API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) de HTML naar TEXT converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPSM naar TEXT-weergave in Android" %}}
1. Open het PPSM-bestand met de klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converteer PPSM naar HTML met behulp van [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) methode en stel Html in als SaveFormat
3. Laad het geconverteerde HTML-bestand met de klasse [Textument](https://reference.aspose.com/words/java/com.aspose.words/Textument)
4. Sla het textument op in TEXT-indeling met de methode [save](https://reference.aspose.com/words/java/com.aspose.words/Textument#save(java.lang.String,int)) en stel Text in als OpslaanFormaat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total for Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.Slides for Android via Java](https://texts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) en [Aspose.Words voor Andorid via Java](https://texts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("input.ppsm");
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
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-dotx/" name="PPSM Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-dot/" name="PPSM Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-textx/" name="PPSM Tot TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-dotm/" name="PPSM Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-rtf/" name="PPSM Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-flatopc/" name="PPSM Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-textm/" name="PPSM Tot TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-wordml/" name="PPSM Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-odt/" name="PPSM Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-ott/" name="PPSM Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-word/" name="PPSM Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppsm-to-text/" name="PPSM Tot TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}