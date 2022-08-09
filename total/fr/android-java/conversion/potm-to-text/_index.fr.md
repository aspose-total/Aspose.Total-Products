---
title: Exporter POTM vers TEXT sur Andorid via Java
description: Convertissez POTM en TEXT dans les applications mobiles sans installer de logiciel
url: /fr/android-java/conversion/potm-to-text/
family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: TEXT
otherformats: OTT DOCX DOCM FLATOPC ODT DOTX DOTM DOC RTF WORDML WORD DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendre POTM en TEXT sur Andorid via Java" h2="API de format de fichier pour convertir POTM en TEXT dans les applications Android sans dépendre de Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total pour Android via Java](https://products.aspose.com/total/android-java/) permet de manipuler les formats de fichiers dans les applications Android. En utilisant les API fournies dans le package, vous pouvez automatiser le processus de conversion de PowerPoint POTM en Word TEXT dans vos applications.
Vous pouvez convertir votre textument donné en deux étapes. Vous pouvez utiliser [Aspose.Slides pour Andorid via Java](https://products.aspose.com/slides/android-java/) qui est une API PowerPoint pour les applications Android pour rendre POTM en HTML. Après cela, en utilisant l'API de traitement de textument [Aspose.Words pour Android via Java](https://products.aspose.com/words/android-java/), vous pouvez convertir le HTML en TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rendu POTM vers TEXT sous Android" %}}
1. Ouvrez le fichier POTM à l'aide de la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convertissez POTM en HTML en utilisant [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.MéthodeISaveOptions-) et définissez Html comme SaveFormat
3. Chargez le fichier HTML converti à l'aide de la classe [Textument](https://reference.aspose.com/words/java/com.aspose.words/Textument)
4. Enregistrez le textument au format TEXT à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Textument#save(java.lang.String,int)) et définissez Text en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.Slides pour Android via Java](https://texts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) et [Aspose.Words pour Andorid via Java](https://texts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans votre applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
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
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-ott/" name="POTM À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-textx/" name="POTM À TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-textm/" name="POTM À TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-flatopc/" name="POTM À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-odt/" name="POTM À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-dotx/" name="POTM À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-dotm/" name="POTM À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-text/" name="POTM À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-rtf/" name="POTM À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-wordml/" name="POTM À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-word/" name="POTM À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/potm-to-dot/" name="POTM À DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}