---
title: Exporter PPSM vers DOC sur Andorid via Java
description: Convertissez PPSM en DOC dans les applications mobiles sans installer de logiciel
url: /fr/android-java/conversion/ppsm-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: DOC
otherformats: DOTX WORD ODT DOTM WORDML TEXT DOCX DOCM RTF DOT OTT FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendre PPSM en DOC sur Andorid via Java" h2="API de format de fichier pour convertir PPSM en DOC dans les applications Android sans dépendre de Microsoft PowerPoint ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total pour Android via Java](https://products.aspose.com/total/android-java/) permet de manipuler les formats de fichiers dans les applications Android. En utilisant les API fournies dans le package, vous pouvez automatiser le processus de conversion de PowerPoint PPSM en Word DOC dans vos applications.
Vous pouvez convertir votre document donné en deux étapes. Vous pouvez utiliser [Aspose.Slides pour Andorid via Java](https://products.aspose.com/slides/android-java/) qui est une API PowerPoint pour les applications Android pour rendre PPSM en HTML. Après cela, en utilisant l'API de traitement de document [Aspose.Words pour Android via Java](https://products.aspose.com/words/android-java/), vous pouvez convertir le HTML en DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rendu PPSM vers DOC sous Android" %}}
1. Ouvrez le fichier PPSM à l'aide de la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convertissez PPSM en HTML en utilisant [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.MéthodeISaveOptions-) et définissez Html comme SaveFormat
3. Chargez le fichier HTML converti à l'aide de la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format DOC à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez Doc en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.Slides pour Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) et [Aspose.Words pour Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans votre applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("input.ppsm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Document
Document document = new Document("htmlOutput.html");
// save document in DOC format
document.save("output.doc",SaveFormat.Doc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-dotx/" name="PPSM À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-word/" name="PPSM À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-odt/" name="PPSM À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-dotm/" name="PPSM À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-wordml/" name="PPSM À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-text/" name="PPSM À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-docx/" name="PPSM À DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-docm/" name="PPSM À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-rtf/" name="PPSM À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-dot/" name="PPSM À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-ott/" name="PPSM À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/ppsm-to-flatopc/" name="PPSM À FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}