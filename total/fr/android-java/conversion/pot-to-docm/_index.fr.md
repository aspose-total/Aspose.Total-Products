---
title: Exporter POT vers DOCM sur Andorid via Java
description: Convertissez POT en DOCM dans les applications mobiles sans installer de logiciel

family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: DOCM
otherformats: DOTX TEXT WORD DOCX DOT DOC FLATOPC ODT WORDML OTT RTF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendre POT en DOCM sur Andorid via Java" h2="API de format de fichier pour convertir POT en DOCM dans les applications Android sans dépendre de Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) permet de manipuler les formats de fichiers dans les applications Android. En utilisant les API fournies dans le package, vous pouvez automatiser le processus de conversion de PowerPoint POT en Word DOCM dans vos applications.
Vous pouvez convertir votre docmument donné en deux étapes. Vous pouvez utiliser [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) qui est une API PowerPoint pour les applications Android pour rendre POT en HTML. Après cela, en utilisant l'API de traitement de docmument [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), vous pouvez convertir le HTML en DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rendu POT vers DOCM sous Android" %}}
1. Ouvrez le fichier POT à l'aide de la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convertissez POT en HTML en utilisant [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.MéthodeISaveOptions-) et définissez Html comme SaveFormat
3. Chargez le fichier HTML converti à l'aide de la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le docmument au format DOCM à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez Docm en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.Slides for Android via Java](https://docms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) et [Aspose.Words pour Andorid via Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans votre applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("input.pot");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-dotx/" name="POT À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-text/" name="POT À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-word/" name="POT À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-docmx/" name="POT À DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-dot/" name="POT À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-docm/" name="POT À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-flatopc/" name="POT À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-odt/" name="POT À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-wordml/" name="POT À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-ott/" name="POT À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-rtf/" name="POT À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/pot-to-dotm/" name="POT À DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}