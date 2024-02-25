---
title: Exporter EMLX vers DOT via Java
description: API Java pour convertir EMLX en DOT sans utiliser Microsoft Word ou Outlook
url_ignore: /fr/java/conversion/emlx-to-dot/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: DOT
otherformats: EPUB PS PDF DOTM FLATOPC SVG RTF TEXT WORDML DOT DOC DOCX JPEG EMF GIF DOCM MD DOTX ODT XPS OTT PNG PCL TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java pour rendre EMLX en DOT" h2="Exportez EMLX vers DOT en utilisant l'API Java sur site sans utiliser de dépendances tierces" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion des e-mails est une fonctionnalité puissante que les développeurs Java peuvent intégrer dans toutes les applications Java J2SE, J2EE, J2ME via [Aspose.Total for Java](https://products.aspose.com/total/java/). En utilisant deux API dans le package, vous pouvez convertir Emlx EMLX en DOT sans aucune dépendance de tiers. Tout d'abord, vous pouvez utiliser l'API Emlx Manipulation [Aspose.Email for Java](https://products.aspose.com/email/java/) pour convertir le format de fichier EMLX en HTML. Deuxièmement, vous pouvez restituer HTML en DOT à l'aide de l'API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir EMLX en DOT" %}}
1. Ouvrez le fichier EMLX à l'aide de la classe [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Convertissez EMLX en HTML en utilisant [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions)) méthode
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format DOT en utilisant [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) et définissez DOT comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous devez utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOT
document.save("output.dot", SaveFormat.DOT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}