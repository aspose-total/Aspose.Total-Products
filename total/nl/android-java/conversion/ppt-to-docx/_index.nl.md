---
title: Exporteer PPT naar DOCX op Andorid via Java
description: Converteer PPT naar DOCX in mobiele apps zonder software te installeren
url: /nl/android-java/conversion/ppt-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOCX
otherformats: TEXT DOTM ODT WORDML DOTX DOC DOT WORD OTT DOCM RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PPT naar DOCX op Andorid via Java" h2="Bestandsformaat-API's om PPT naar DOCX te converteren binnen Android-apps zonder afhankelijk te zijn van Microsoft PowerPoint of Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total voor Android via Java](https://products.aspose.com/total/android-java/) maakt het manipuleren van bestandsindelingen binnen Android-applicaties mogelijk. Door de API's in het pakket te gebruiken, kunt u het conversieproces van PowerPoint PPT naar Word DOCX in uw apps automatiseren.
U kunt uw opgegeven docxument in twee stappen converteren. U kunt [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) gebruiken, een PowerPoint-API voor Android-toepassingen om PPT naar HTML weer te geven. Daarna kunt u met behulp van de docxumentverwerkings-API [Aspose.Words voor Android via Java](https://products.aspose.com/words/android-java/) de HTML naar DOCX converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PPT naar DOCX-weergave in Android" %}}
1. Open het PPT-bestand met de klasse [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Converteer PPT naar HTML met behulp van [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) methode en stel Html in als SaveFormat
3. Laad het geconverteerde HTML-bestand met de klasse [Docxument](https://reference.aspose.com/words/java/com.aspose.words/Docxument)
4. Sla het docxument op in DOCX-indeling met de methode [save](https://reference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,int)) en stel Docx in als OpslaanFormaat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
U kunt Aspose.Total voor Android eenvoudig via Java rechtstreeks vanuit [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) en installeer [Aspose.Slides voor Android via Java](https://docxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) en [Aspose.Words voor Andorid via Java](https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) in uw toepassingen.

U kunt ook een ZIP-bestand krijgen van [downloads](https://downloads.aspose.com/total/androidjava).
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
{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde conversies" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-text/" name="PPT Tot TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-dotm/" name="PPT Tot DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-odt/" name="PPT Tot ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-wordml/" name="PPT Tot WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-dotx/" name="PPT Tot DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-docx/" name="PPT Tot DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-dot/" name="PPT Tot DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-word/" name="PPT Tot WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-ott/" name="PPT Tot OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-docxm/" name="PPT Tot DOCXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-rtf/" name="PPT Tot RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/nl/android-java/conversion/ppt-to-flatopc/" name="PPT Tot FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}