---
title: Exporter EML vers WORDML via Java
description: API Java pour convertir EML en WORDML sans utiliser Microsoft Word ou Outlook
url_ignore: /fr/java/conversion/eml-to-wordml/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: WORD_ML
otherformats: DOT MD FLATOPC SVG GIF PCL DOCX JPEG PDF EPUB DOCM TEXT ODT RTF DOC WORDML OTT DOTM EMF XPS PNG PS DOTX TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java pour rendre EML en WORDML" h2="Exportez EML vers WORDML en utilisant l'API Java sur site sans utiliser de dépendances tierces" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion des e-mails est une fonctionnalité puissante que les développeurs Java peuvent intégrer dans toutes les applications Java J2SE, J2EE, J2ME via [Aspose.Total for Java](https://products.aspose.com/total/java/). En utilisant deux API dans le package, vous pouvez convertir Eml EML en WORDML sans aucune dépendance de tiers. Tout d'abord, vous pouvez utiliser l'API Eml Manipulation [Aspose.Email for Java](https://products.aspose.com/email/java/) pour convertir le format de fichier EML en HTML. Deuxièmement, vous pouvez restituer HTML en WORDML à l'aide de l'API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir EML en WORDML" %}}
1. Ouvrez le fichier EML à l'aide de la classe [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Convertissez EML en HTML en utilisant [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)) méthode
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format WORDML en utilisant [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) et définissez WORDML comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous devez utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}