---
title: API Java pour exporter CGM vers DOCM
description: Convertir CGM en DOCM à l'aide de l'API Java sur site
url_ignore: /fr/java/conversion/cgm-to-docm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOCM
otherformats: RTF WORDML ODT FLATOPC PS PCL MHTML DOTM OTT DOTX XAMLFLOW MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Transformez CGM en DOCM via Java" h2="API Java sur site pour rendre CGM en DOCM sans utiliser d'application tierce" >}}
{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir CGM en DOCM en utilisant deux étapes simples. Vous devez d'abord rendre le fichier CGM au format DOC à l'aide de [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Après cela, en utilisant la puissante API de traitement de documents [Aspose.Words for Java](https://products.aspose.com/words/java/), vous pouvez convertir DOC en DOCM. Les deux API font partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Java pour convertir CGM en DOCM" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez CGM en DOC en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le fichier DOC en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) de Aspose.Words
4. Enregistrez le document au format DOCM à l'aide de la méthode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) et définissez DOCM en tant que format de sauvegarde
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et inclure [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) et [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "cgm-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Lors de la conversion de CGM en DOCM, même si votre document est protégé par un mot de passe, vous pouvez toujours l'ouvrir à l'aide de l'API de manipulation PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Pour ouvrir le fichier chiffré, vous devez créer un objet [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) et ouvrir le CGM à l'aide du mot de passe du propriétaire.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "open-password-protected-cgm.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Ouvrir un document CGM protégé par mot de passe via Java" %}}
Lors de l'enregistrement de votre document d'entrée au format de fichier DOCM, vous pouvez également enregistrer votre document dans une base de données au lieu d'un système de fichiers. Vous devrez peut-être implémenter le stockage et la récupération d'objets Document vers et depuis une base de données. Cela serait nécessaire si vous mettiez en œuvre tout type de système de gestion de contenu. Afin d'enregistrer votre DOCM dans la base de données, il est souvent nécessaire de sérialiser le document pour obtenir un tableau d'octets. Cela peut être fait à l'aide de l'API [Aspose.Words for Java](https://products.aspose.com/words/Java/). Après avoir obtenu votre tableau d'octets, vous pouvez le stocker dans la base de données à l'aide de l'instruction SQL. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "save-cgm-to-database.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## ✅ Cas d'utilisation clés

- **Reporting technique dynamique**  
  Intégrez des illustrations basées sur CGM dans des modèles DOCM qui mettent à jour automatiquement les graphiques, les tableaux et le contenu d'analyse.

- **Génération de documents activée par macro pour les journaux d'ingénierie**  
  Créez des carnets de bord d'ingénierie où les macros traitent et présentent les données de diagramme CGM avec des résultats calculés.

- **Documentation des flux de travail**  
  Générez des manuels interactifs ou des guides opérationnels avec des visuels CGM intégrés et une navigation pilotée par macro.


## ⚙️ Scénarios d'automatisation

- **Bibliothèques Java pour la création de DOCM**  
  Utilisez des APIs comme **Apache POI**, **docx4j**, ou **Aspose.Words for Java** pour automatiser la conversion de CGM en DOCM avec prise en charge des macros.

- **Assemblage de documents d'entreprise**  
  Intégrez le processus de conversion dans des systèmes de gestion de contenu d'entreprise alimentés par Java pour une génération instantanée de fichiers activés par macro.

- **Traitement de données piloté par macro**  
  Automatisez l'analyse technique en intégrant des macros qui lisent, interprètent et mettent à jour les données liées aux visuels CGM.

- **Flux de travail de traitement par lots**  
  Convertissez et compilez plusieurs fichiers CGM en rapports DOCM activés par macro grâce à des outils d'automatisation par lots basés sur Java.
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}