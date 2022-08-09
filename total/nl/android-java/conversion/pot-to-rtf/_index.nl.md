---
title: Exporteer POT naar RTF op Andorid via Java
description: Converteer POT naar RTF in mobiele apps zonder software te installeren
url: /nl/android-java/conversion/pot-to-rtf/
family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: RTF
otherformats: DOTX FLATOPC DOC DOCX DOT DOCM OTT WORD DOTM TEXT ODT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render POT naar RTF op Andorid via Java" h2="Bestandsformaat-API's om POT naar RTF te converteren binnen Android-apps zonder afhankelijk te zijn van Microsoft PowerPoint of Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total voor Android via Java](https://products.aspose.com/total/android-java/) maakt het manipuleren van bestandsindelingen binnen Android-applicaties mogelijk. Door de API's in het pakket te gebruiken, kunt u het conversieproces van PowerPoint POT naar Word RTF in uw apps automatiseren.
U kunt uw opgegeven rtfument in twee stappen converteren. U kunt [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) gebruiken, een PowerPoint-API voor Android-toepassingen om POT naar HTML weer te geven. Daarna kunt u met behulp van de rtfumentverwerkings-API [Aspose.Words voor Android via Java](https://products.aspose.com/words/android-java/) de HTML naar RTF converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POT naar RTF-weergave in Android" %}}
1. Open het POT-bestand met de klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converteer POT naar HTML met behulp van [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) methode en stel Html in als SaveFormat
3. Laad het geconverteerde HTML-bestand met de klasse [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)
4. Sla het rtfument op in RTF-indeling met de methode [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int)) en stel Rtf in als OpslaanFormaat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.Slides voor Android via Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) en [Aspose.Words voor Andorid via Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("input.pot");
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
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-dotx/" name="POT Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-flatopc/" name="POT Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-rtf/" name="POT Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-rtfx/" name="POT Tot RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-dot/" name="POT Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-rtfm/" name="POT Tot RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-ott/" name="POT Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-word/" name="POT Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-dotm/" name="POT Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-text/" name="POT Tot TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-odt/" name="POT Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/pot-to-wordml/" name="POT Tot WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}