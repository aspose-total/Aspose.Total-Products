---
title: Rendre EMAIL en SVG dans l'application Andorid
description: Exportez EMAIL vers SVG sans utiliser Microsoft Word ou Outlook dans vos applications Andorid
url: /fr/android-java/conversion/email-to-svg/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: SVG
otherformats: PCL JPEG WORDML EPUB DOCX OTT MD RTF DOTX DOC TEXT BMP TIFF ODT DOT DOCM EMF PDF PS XPS PNG DOTM GIF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformez EMAIL en SVG dans les applications Andorid" h2="Conception d'applications Andorid pour exporter EMAIL vers SVG en utilisant Andorid via l'API Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Les applications Andorid sont faciles à utiliser pour les utilisateurs finaux au quotidien. Jour après jour, le nombre d'utilisateurs de téléphones Andorid augmente. En utilisant les puissantes bibliothèques d'automatisation du format de fichier [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), vous pouvez développer des applications de manipulation et de conversion d'e-mails. Vous pouvez convertir EMAIL en SVG en combinant [Aspose.Email for Android via Java](https://products.aspose.com/email/android-java/) & [Aspose.Words pour Andorid Java](https:// produits.aspose.com/words/android-java/). En utilisant la première API, vous pouvez convertir le format de fichier EMAIL en HTML et en utilisant la deuxième API, vous pouvez rendre le HTML en SVG. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir EMAIL en SVG dans Andorid" %}}
1. Ouvrez le fichier EMAIL à l'aide de la classe [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Convertissez EMAIL en HTML en utilisant [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) méthode
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format SVG en utilisant [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) et définissez SVG comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.Email for Android via Java](https://docs.aspose.com/email/androidjava/installation/) et [Aspose.Words pour Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.SVG
document.save("output.svg", SaveFormat.SVG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-pcl/" name="MSG À PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-jpeg/" name="MSG À JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-wordml/" name="MSG À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-epub/" name="MSG À EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-docx/" name="MSG À DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-ott/" name="MSG À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-md/" name="MSG À MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-rtf/" name="MSG À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-dotx/" name="MSG À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-doc/" name="MSG À DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-text/" name="MSG À TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-svg/" name="MSG À SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-tiff/" name="MSG À TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-odt/" name="MSG À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-dot/" name="MSG À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-docm/" name="MSG À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-emf/" name="MSG À EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-pdf/" name="MSG À PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-ps/" name="MSG À PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-xps/" name="MSG À XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-png/" name="MSG À PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-dotm/" name="MSG À DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-gif/" name="MSG À GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/msg-to-flatopc/" name="MSG À FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}