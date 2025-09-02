---
title: Exporter EMLX vers MD via Java
description: API Java pour convertir EMLX en MD sans utiliser Microsoft Word ou Outlook
url_ignore: /fr/java/conversion/emlx-to-md/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: MD
otherformats: SVG TEXT OTT DOCX XPS DOT GIF PCL PNG DOC DOTX PS DOTM EMF MD PDF DOCM TIFF ODT EPUB RTF FLATOPC WORDML JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java pour rendre EMLX en MD" h2="Exportez EMLX vers MD en utilisant l'API Java sur site sans utiliser de dépendances tierces" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion des e-mails est une fonctionnalité puissante que les développeurs Java peuvent intégrer dans toutes les applications Java J2SE, J2EE, J2ME via [Aspose.Total for Java](https://products.aspose.com/total/java/). En utilisant deux API dans le package, vous pouvez convertir Emlx EMLX en MD sans aucune dépendance de tiers. Tout d'abord, vous pouvez utiliser l'API Emlx Manipulation [Aspose.Email for Java](https://products.aspose.com/email/java/) pour convertir le format de fichier EMLX en HTML. Deuxièmement, vous pouvez restituer HTML en MD à l'aide de l'API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir EMLX en MD" %}}
1. Ouvrez le fichier EMLX à l'aide de la classe [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Convertissez EMLX en HTML en utilisant [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions)) méthode
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format MD en utilisant [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) et définissez MD comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous devez utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-summary %}}
```
Convertissez EMLX en **Markdown (MD)** permet un formatage propre, basé sur du texte et convivial pour les développeurs pour la documentation technique, les blogs ou les plateformes collaboratives.

## ✅ Cas d'utilisation clés
- Stocker les e-mails d'Apple Mail dans des fichiers Markdown légers.
- Publier des newsletters ou des annonces sur des blogs.
- Réutilisation de la documentation technique à partir de communications par e-mail.
- Stockage de discussions par e-mail pour le contrôle de version (basé sur Git).

## ⚙️ Scénarios d'automatisation
- Conversion automatique des e-mails liés au projet en documents Markdown.
- Pipelines d'e-mails vers les problèmes/README de GitHub.
- Référentiels de connaissances centralisés basés sur Markdown.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}