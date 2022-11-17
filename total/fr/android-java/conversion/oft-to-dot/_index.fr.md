---
title: Rendre OFT en DOT dans l'application Andorid
description: Exportez OFT vers DOT sans utiliser Microsoft Word ou Outlook dans vos applications Andorid

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: DOT
otherformats: DOTX OTT FLATOPC RTF DOCX ODT DOCM EPUB GIF DOC TIFF JPEG MD PDF BMP TEXT PS WORDML XPS PCL SVG PNG EMF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformez OFT en DOT dans les applications Andorid" h2="Conception d'applications Andorid pour exporter OFT vers DOT en utilisant Andorid via l'API Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Les applications Andorid sont faciles à utiliser pour les utilisateurs finaux au quotidien. Jour après jour, le nombre d'utilisateurs de téléphones Andorid augmente. En utilisant les puissantes bibliothèques d'automatisation du format de fichier [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), vous pouvez développer des applications de manipulation et de conversion d'e-mails. Vous pouvez convertir OFT en DOT en combinant [Aspose.Oft pour Android Java](https://products.aspose.com/oft/android-java/) & [Aspose.Words pour Andorid Java](https:// produits.aspose.com/words/android-java/). En utilisant la première API, vous pouvez convertir le format de fichier OFT en HTML et en utilisant la deuxième API, vous pouvez rendre le HTML en DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir OFT en DOT dans Andorid" %}}
1. Ouvrez le fichier OFT à l'aide de la classe [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Convertissez OFT en HTML en utilisant [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions )) méthode
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format DOT en utilisant [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) et définissez DOT comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.Oft pour Android via Java](https://docs.aspose.com/oft/androidjava/installation/) et [Aspose.Words pour Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOT
document.save("output.dot", SaveFormat.DOT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-dotx/" name="OFT À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-ott/" name="OFT À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-flatopc/" name="OFT À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-rtf/" name="OFT À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-docx/" name="OFT À DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-odt/" name="OFT À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-docm/" name="OFT À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-epub/" name="OFT À EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-gif/" name="OFT À GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-doc/" name="OFT À DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-tiff/" name="OFT À TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-jpeg/" name="OFT À JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-md/" name="OFT À MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-pdf/" name="OFT À PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-dot/" name="OFT À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-text/" name="OFT À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-ps/" name="OFT À PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-wordml/" name="OFT À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-xps/" name="OFT À XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-pcl/" name="OFT À PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-svg/" name="OFT À SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-png/" name="OFT À PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-emf/" name="OFT À EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/oft-to-dotm/" name="OFT À DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}