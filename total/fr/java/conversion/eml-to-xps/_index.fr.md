---
title: Exporter EML vers XPS via Java
description: API Java pour convertir EML en XPS sans utiliser Microsoft Word ou Outlook
url_ignore: /fr/java/conversion/eml-to-xps/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: XPS
otherformats: MD DOC DOCX WORDML DOTX RTF DOT PDF OTT XPS TIFF JPEG DOTM EMF SVG TEXT GIF PCL DOCM PS EPUB FLATOPC ODT PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java pour rendre EML en XPS" h2="Exportez EML vers XPS en utilisant l'API Java sur site sans utiliser de dépendances tierces" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion des e-mails est une fonctionnalité puissante que les développeurs Java peuvent intégrer dans toutes les applications Java J2SE, J2EE, J2ME via [Aspose.Total for Java](https://products.aspose.com/total/java/). En utilisant deux API dans le package, vous pouvez convertir Eml EML en XPS sans aucune dépendance de tiers. Tout d'abord, vous pouvez utiliser l'API Eml Manipulation [Aspose.Email for Java](https://products.aspose.com/email/java/) pour convertir le format de fichier EML en HTML. Deuxièmement, vous pouvez restituer HTML en XPS à l'aide de l'API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir EML en XPS" %}}
1. Ouvrez le fichier EML à l'aide de la classe [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Convertissez EML en HTML en utilisant [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)) méthode
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format XPS en utilisant [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) et définissez XPS comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous devez utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/feature-section >}}
**XPS (XML Paper Specification)** est un format de mise en page fixe de Microsoft. Convertir **EML en XPS** garantit un rendu de document cohérent.

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}
- Archivage des e-mails avec des mises en page fixes.
- Création de versions sécurisées en lecture seule de correspondances.
- Alternative au PDF dans les écosystèmes Windows.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}
- Pipelines d'archivage d'e-mails d'entreprise.
- Exportation automatisée en XPS pour la conformité et les enregistrements.
- Conversion en lot d'e-mails en XPS pour la documentation.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}