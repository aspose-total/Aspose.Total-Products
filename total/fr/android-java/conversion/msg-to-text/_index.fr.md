---
title: Rendre MSG en TEXT dans l'application Andorid
description: Exportez MSG vers TEXT sans utiliser Microsoft Word ou Outlook dans vos applications Andorid

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: TEXT
otherformats: RTF DOC DOT BMP FLATOPC ODT DOCX GIF PCL EMF XPS DOTX JPEG DOTM OTT WORDML DOCM SVG PS TIFF MD PNG PDF EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transformez MSG en TEXT dans les applications Andorid" h2="Conception d'applications Andorid pour exporter MSG vers TEXT en utilisant Andorid via l'API Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Les applications Andorid sont faciles à utiliser pour les utilisateurs finaux au quotidien. Jour après jour, le nombre d'utilisateurs de téléphones Andorid augmente. En utilisant les puissantes bibliothèques d'automatisation du format de fichier [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), vous pouvez développer des applications de manipulation et de conversion d'e-mails. Vous pouvez convertir MSG en TEXT en combinant [Aspose.Msg pour Android Java](https://products.aspose.com/msg/android-java/) & [Aspose.Words pour Andorid Java](https:// produits.aspose.com/words/android-java/). En utilisant la première API, vous pouvez convertir le format de fichier MSG en HTML et en utilisant la deuxième API, vous pouvez rendre le HTML en TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir MSG en TEXT dans Andorid" %}}
1. Ouvrez le fichier MSG à l'aide de la classe [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Convertissez MSG en HTML en utilisant [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions )) méthode
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format TEXT en utilisant [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) et définissez TEXT comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://releases.aspose.com/total/java/)ocs.aspose.com/msg/androidjava/installation/) et [Aspose.Words pour Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.TEXT
document.save("output.text", SaveFormat.TEXT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}