---
title: Exporteer POTM naar ODT op Andorid via Java
description: Converteer POTM naar ODT in mobiele apps zonder software te installeren
url: /nl/android-java/conversion/potm-to-odt/
family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: ODT
otherformats: DOTM TEXT OTT WORD DOC DOCX FLATOPC DOT WORDML DOTX RTF DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render POTM naar ODT op Andorid via Java" h2="Bestandsformaat-API's om POTM naar ODT te converteren binnen Android-apps zonder afhankelijk te zijn van Microsoft PowerPoint of Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total voor Android via Java](https://products.aspose.com/total/android-java/) maakt het manipuleren van bestandsindelingen binnen Android-applicaties mogelijk. Door de API's in het pakket te gebruiken, kunt u het conversieproces van PowerPoint POTM naar Word ODT in uw apps automatiseren.
U kunt uw opgegeven odtument in twee stappen converteren. U kunt [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) gebruiken, een PowerPoint-API voor Android-toepassingen om POTM naar HTML weer te geven. Daarna kunt u met behulp van de odtumentverwerkings-API [Aspose.Words voor Android via Java](https://products.aspose.com/words/android-java/) de HTML naar ODT converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="POTM naar ODT-weergave in Android" %}}
1. Open het POTM-bestand met de klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converteer POTM naar HTML met behulp van [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) methode en stel Html in als SaveFormat
3. Laad het geconverteerde HTML-bestand met de klasse [Odtument](https://reference.aspose.com/words/java/com.aspose.words/Odtument)
4. Sla het odtument op in ODT-indeling met de methode [save](https://reference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,int)) en stel Odt in als OpslaanFormaat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.Slides voor Android via Java](https://odts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) en [Aspose.Words voor Andorid via Java](https://odts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Odtument
Odtument odtument = new Odtument("htmlOutput.html");
// save odtument in ODT format
odtument.save("output.odt",SaveFormat.Odt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-dotm/" name="POTM Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-text/" name="POTM Tot TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-ott/" name="POTM Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-word/" name="POTM Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-odt/" name="POTM Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-odtx/" name="POTM Tot ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-flatopc/" name="POTM Tot FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-dot/" name="POTM Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-wordml/" name="POTM Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-dotx/" name="POTM Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-rtf/" name="POTM Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/potm-to-odtm/" name="POTM Tot ODTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}