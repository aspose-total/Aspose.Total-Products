---
title: Exporter EMAIL vers TEXT via Java
description: API Java pour convertir EMAIL en TEXT sans utiliser Microsoft Word ou Outlook
url_ignore: /fr/java/conversion/email-to-text/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TEXT
otherformats: DOT PS SVG PDF XPS FLATOPC WORDML JPEG DOCM PCL DOCX RTF GIF TIFF PNG EPUB TEXT MD OTT DOC ODT DOTM DOTX EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java pour rendre EMAIL en TEXT" h2="Exportez EMAIL vers TEXT en utilisant l'API Java sur site sans utiliser de dépendances tierces" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion des e-mails est une fonctionnalité puissante que les développeurs Java peuvent intégrer dans toutes les applications Java J2SE, J2EE, J2ME via [Aspose.Total for Java](https://products.aspose.com/total/java/). En utilisant deux API dans le package, vous pouvez convertir Email EMAIL en TEXT sans aucune dépendance de tiers. Tout d'abord, vous pouvez utiliser l'API Email Manipulation [Aspose.Email for Java](https://products.aspose.com/email/java/) pour convertir le format de fichier EMAIL en HTML. Deuxièmement, vous pouvez restituer HTML en TEXT à l'aide de l'API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir EMAIL en TEXT" %}}
1. Ouvrez le fichier EMAIL à l'aide de la classe [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Convertissez EMAIL en HTML en utilisant [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) méthode
3. Chargez HTML en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format TEXT en utilisant [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) et définissez TEXT comme SaveFormat
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
```
Convertir les e-mails en **texte brut (.txt)** garantit que le contenu essentiel des messages est extrait sous sa forme la plus simple et la plus portable. Ce format élimine les mises en forme inutiles, rendant les données légères, consultables et hautement compatibles sur toutes les plateformes.  


{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}  
- **Archivage & Conformité** : Stockez les e-mails sous forme de texte pour un archivage léger et à long terme.  
- **E-Discovery & Juridique** : Extrayez uniquement le texte brut pour des enquêtes ou un support juridique.  
- **Exploration de données & Analyse** : Préparez le texte d'e-mail non structuré pour le TALN, l'IA ou l'indexation de recherche.  
- **Migration vers des systèmes hérités** : Fournir le contenu de l'e-mail dans un format texte universellement accepté.  
- **Accès hors ligne** : Lire des e-mails sur des appareils ou des applications qui ne prennent pas en charge les mises en forme riches.  


{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}  
- **Exportation par lots** : Convertissez des milliers d'e-mails en `.txt` pour le stockage ou les pipelines d'analyse.  
- **Extraction de contenu** : Automatisez les flux de travail pour supprimer les métadonnées, le HTML et les signatures, ne conservant que le texte propre.  
- **Indexation des moteurs de recherche** : Créez des sorties `.txt` automatisées pour construire des archives consultables.  
- **Pipelines d'analyse d'e-mails** : Utilisez la sortie `.txt` comme format intermédiaire pour l'extraction de données structurées.  
- **Automatisation de la conformité** : Générez automatiquement des journaux en texte brut à partir des e-mails entrants et sortants.  
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}