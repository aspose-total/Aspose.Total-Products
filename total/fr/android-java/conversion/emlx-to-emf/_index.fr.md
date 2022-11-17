---
title: Rendre EMLX en EMF dans l'application Andorid
description: Exportez EMLX vers EMF sans utiliser Microsoft Word ou Outlook dans vos applications Andorid

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: EMF
otherformats: PNG DOC DOTX MD ODT FLATOPC JPEG TIFF DOTM PCL PS DOT OTT WORDML SVG PDF RTF EPUB GIF BMP XPS TEXT DOCM DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformez EMLX en EMF dans les applications Andorid" h2="Conception d'applications Andorid pour exporter EMLX vers EMF en utilisant Andorid via l'API Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Les applications Andorid sont faciles à utiliser pour les utilisateurs finaux au quotidien. Jour après jour, le nombre d'utilisateurs de téléphones Andorid augmente. En utilisant les puissantes bibliothèques d'automatisation du format de fichier [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), vous pouvez développer des applications de manipulation et de conversion d'e-mails. Vous pouvez convertir EMLX en EMF en combinant [Aspose.Emlx pour Android Java](https://products.aspose.com/emlx/android-java/) & [Aspose.Words pour Andorid Java](https:// produits.aspose.com/words/android-java/). En utilisant la première API, vous pouvez convertir le format de fichier EMLX en HTML et en utilisant la deuxième API, vous pouvez rendre le HTML en EMF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir EMLX en EMF dans Andorid" %}}
1. Ouvrez le fichier EMLX à l'aide de la classe [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. Convertissez EMLX en HTML en utilisant [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions )) méthode
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format EMF en utilisant [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) et définissez EMF comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.Emlx pour Android via Java](https://docs.aspose.com/emlx/androidjava/installation/) et [Aspose.Words pour Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.EMF
document.save("output.emf", SaveFormat.EMF); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-png/" name="EMLX À PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-doc/" name="EMLX À DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-dotx/" name="EMLX À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-md/" name="EMLX À MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-odt/" name="EMLX À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-flatopc/" name="EMLX À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-jpeg/" name="EMLX À JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-tiff/" name="EMLX À TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-dotm/" name="EMLX À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-pcl/" name="EMLX À PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-ps/" name="EMLX À PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-dot/" name="EMLX À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-ott/" name="EMLX À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-wordml/" name="EMLX À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-svg/" name="EMLX À SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-pdf/" name="EMLX À PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-rtf/" name="EMLX À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-epub/" name="EMLX À EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-gif/" name="EMLX À GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-emf/" name="EMLX À EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-xps/" name="EMLX À XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-text/" name="EMLX À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-docm/" name="EMLX À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/emlx-to-docx/" name="EMLX À DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}