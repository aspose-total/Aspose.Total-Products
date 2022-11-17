---
title: Rendre EML en PS dans l'application Andorid
description: Exportez EML vers PS sans utiliser Microsoft Word ou Outlook dans vos applications Andorid

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: PS
otherformats: DOCX RTF JPEG XPS GIF SVG DOTM EPUB MD DOCM ODT WORDML EMF OTT BMP DOTX TIFF DOC TEXT PNG PDF DOT FLATOPC PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformez EML en PS dans les applications Andorid" h2="Conception d'applications Andorid pour exporter EML vers PS en utilisant Andorid via l'API Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Les applications Andorid sont faciles à utiliser pour les utilisateurs finaux au quotidien. Jour après jour, le nombre d'utilisateurs de téléphones Andorid augmente. En utilisant les puissantes bibliothèques d'automatisation du format de fichier [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), vous pouvez développer des applications de manipulation et de conversion d'e-mails. Vous pouvez convertir EML en PS en combinant [Aspose.Eml pour Android Java](https://products.aspose.com/eml/android-java/) & [Aspose.Words pour Andorid Java](https:// produits.aspose.com/words/android-java/). En utilisant la première API, vous pouvez convertir le format de fichier EML en HTML et en utilisant la deuxième API, vous pouvez rendre le HTML en PS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir EML en PS dans Andorid" %}}
1. Ouvrez le fichier EML à l'aide de la classe [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Convertissez EML en HTML en utilisant [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions )) méthode
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format PS en utilisant [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) et définissez PS comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.Eml pour Android via Java](https://docs.aspose.com/eml/androidjava/installation/) et [Aspose.Words pour Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PS
document.save("output.ps", SaveFormat.PS); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-docx/" name="EML À DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-rtf/" name="EML À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-jpeg/" name="EML À JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-xps/" name="EML À XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-gif/" name="EML À GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-svg/" name="EML À SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-dotm/" name="EML À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-epub/" name="EML À EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-md/" name="EML À MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-docm/" name="EML À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-odt/" name="EML À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-wordml/" name="EML À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-emf/" name="EML À EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-ott/" name="EML À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-ps/" name="EML À PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-dotx/" name="EML À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-tiff/" name="EML À TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-doc/" name="EML À DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-text/" name="EML À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-png/" name="EML À PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-pdf/" name="EML À PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-dot/" name="EML À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-flatopc/" name="EML À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/eml-to-pcl/" name="EML À PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}