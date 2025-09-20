---
title: Convertir le format JSON en DOCM via Java
description: Analyser JSON en DOCM en Java sans utiliser Microsoft Word
url_ignore: /fr/java/conversion/json-to-docm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOCM
otherformats: EPUB RTF DOTX WORDML DOCM OTT ODT PCL DOC FLATOPC PS MOBI DOT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le format JSON en DOCM via Java" h2="API Java sur site pour analyser JSON vers DOCM sans utiliser Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez convertir JSON en DOCM dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez analyser JSON en PDF. Dans la deuxième étape, vous pouvez convertir un PDF en DOCM en utilisant l'API de traitement de texte [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en DOCM via Java" %}}
1. Créez un nouvel objet [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et lisez les données JSON valides à partir du fichier
2. Importez le fichier JSON dans la feuille de calcul à l'aide de la classe [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) et [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) au format PDF
3. Chargez le document PDF en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format DOCM en utilisant [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) méthode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
De plus, l'API vous permet de définir des options de mise en page pour votre JSON lors de l'analyse de JSON vers DOCM à l'aide de [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Il vous permet de traiter Array comme une table, d'ignorer les valeurs nulles, d'ignorer le titre du tableau, d'ignorer le titre de l'objet, de convertir une chaîne en nombre ou en date, de définir le format de la date et du nombre et de définir le style du titre. Toutes ces options vous permettent de présenter vos données selon vos besoins. L'extrait de code suivant vous montre comment définir les options de mise en page.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en DOCM via Java" %}}
À l'aide de l'API, vous pouvez également analyser JSON en DOCM avec filigrane. Afin d'ajouter un filigrane à votre document DOCM, vous pouvez d'abord convertir le fichier JSON en PDF et y ajouter un filigrane. Pour ajouter un filigrane, chargez le fichier PDF nouvellement créé à l'aide de la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), créez une instance de TextWatermarkOptions et définissez ses propriétés, appelez la méthode Watermark.setText et transmettez le texte et l'objet du filigrane de TextWatermarkOptions. Après avoir ajouté le filigrane, vous pouvez enregistrer le document sur DOCM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Convertir **JSON en DOCM** est important pour intégrer des **macros dans les documents Word** générés à partir de données structurées. Ce processus permet aux organisations de combiner des ensembles de données brutes avec des fonctionnalités d'automatisation puissantes à l'intérieur de Word, permettant la génération de contenu dynamique, l'exécution de règles métier et la fonctionnalité de document interactive. En transformant le JSON en fichiers DOCM, les entreprises peuvent rationaliser les flux de travail, améliorer les rapports et créer des modèles activés par macro qui s'adaptent aux besoins de données évolutifs.

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}

- **Flux de travail de documents automatisés** – Piloter la création de documents répétables avec des macros intégrées.
- **Scripts d'analyse de données** – Intégrer des macros pilotées par JSON pour des calculs et un traitement en temps réel.
- **Modèles activés par macro** – Construire des modèles intelligents réutilisables pour la documentation d'entreprise.
- **Systèmes de reporting d'entreprise** – Générer des rapports avec un formatage et une analyse automatisés.
- **Formulaires de conformité interactifs** – Livrer des formulaires avec des règles de validation et de traitement activées par macro.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}

- **Pipelines JSON vers DOCM** – Automatiser la transformation d'ensembles de données structurées en fichiers Word activés par macro.
- **Macros Word déclenchées automatiquement** – Exécuter dynamiquement des macros pendant ou après la génération de documents.
- **Traitement dynamique des règles métier** – Appliquer les politiques d'entreprise et les règles de données directement dans les documents.
- **Automatisation du reporting activée par macro** – Normaliser et accélérer les flux de travail de reporting complexes à grande échelle.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}