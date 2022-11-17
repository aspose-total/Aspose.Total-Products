---
title: Exporter PPT vers DOCM sur Andorid via Java
description: Convertissez PPT en DOCM dans les applications mobiles sans installer de logiciel

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOCM
otherformats: DOCX RTF ODT DOTM TEXT OTT DOC FLATOPC DOTX WORD WORDML DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendre PPT en DOCM sur Andorid via Java" h2="API de format de fichier pour convertir PPT en DOCM dans les applications Android sans dépendre de Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) permet de manipuler les formats de fichiers dans les applications Android. En utilisant les API fournies dans le package, vous pouvez automatiser le processus de conversion de PowerPoint PPT en Word DOCM dans vos applications.
Vous pouvez convertir votre docmument donné en deux étapes. Vous pouvez utiliser [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) qui est une API PowerPoint pour les applications Android pour rendre PPT en HTML. Après cela, en utilisant l'API de traitement de docmument [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), vous pouvez convertir le HTML en DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rendu PPT vers DOCM sous Android" %}}
1. Ouvrez le fichier PPT à l'aide de la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convertissez PPT en HTML en utilisant [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.MéthodeISaveOptions-) et définissez Html comme SaveFormat
3. Chargez le fichier HTML converti à l'aide de la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le docmument au format DOCM à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez Docm en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.Slides for Android via Java](https://docms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) et [Aspose.Words pour Andorid via Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans votre applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("input.ppt");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Document
Document docmument = new Document("htmlOutput.html");
// save docmument in DOCM format
docmument.save("output.docm",SaveFormat.Docmm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-docmx/" name="PPT À DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-rtf/" name="PPT À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-odt/" name="PPT À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-dotm/" name="PPT À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-text/" name="PPT À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-ott/" name="PPT À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-docm/" name="PPT À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-flatopc/" name="PPT À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-dotx/" name="PPT À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-word/" name="PPT À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-wordml/" name="PPT À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppt-to-dot/" name="PPT À DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}