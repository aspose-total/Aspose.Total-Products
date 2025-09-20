---
title: Convertir le format JSON en WORDML via Java
description: Analyser JSON en WORDML en Java sans utiliser Microsoft Word
url_ignore: /fr/java/conversion/json-to-wordml/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WORDML
otherformats: FLATOPC PS RTF DOC MOBI WORDML DOCM DOT PCL DOTX EPUB OTT WORD ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le format JSON en WORDML via Java" h2="API Java sur site pour analyser JSON vers WORDML sans utiliser Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez convertir JSON en WORDML dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez analyser JSON en PDF. Dans la deuxième étape, vous pouvez convertir un PDF en WORDML en utilisant l'API de traitement de texte [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en WORDML via Java" %}}
1. Créez un nouvel objet [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et lisez les données JSON valides à partir du fichier
2. Importez le fichier JSON dans la feuille de calcul à l'aide de la classe [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) et [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) au format PDF
3. Chargez le document PDF en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format WORDML en utilisant [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) méthode
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
De plus, l'API vous permet de définir des options de mise en page pour votre JSON lors de l'analyse de JSON vers WORDML à l'aide de [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Il vous permet de traiter Array comme une table, d'ignorer les valeurs nulles, d'ignorer le titre du tableau, d'ignorer le titre de l'objet, de convertir une chaîne en nombre ou en date, de définir le format de la date et du nombre et de définir le style du titre. Toutes ces options vous permettent de présenter vos données selon vos besoins. L'extrait de code suivant vous montre comment définir les options de mise en page.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en WORDML via Java" %}}
À l'aide de l'API, vous pouvez également analyser JSON en WORDML avec filigrane. Afin d'ajouter un filigrane à votre document WORDML, vous pouvez d'abord convertir le fichier JSON en PDF et y ajouter un filigrane. Pour ajouter un filigrane, chargez le fichier PDF nouvellement créé à l'aide de la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), créez une instance de TextWatermarkOptions et définissez ses propriétés, appelez la méthode Watermark.setText et transmettez le texte et l'objet du filigrane de TextWatermarkOptions. Après avoir ajouté le filigrane, vous pouvez enregistrer le document sur WORDML. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Convertir **JSON en WORDML** est essentiel pour produire des **documents WordprocessingML (documents Word basés sur XML) à partir de données structurées**. WORDML permet un échange de données transparent, la création de documents basée sur des modèles et la compatibilité avec les flux de travail basés sur XML. En transformant le JSON en WORDML, les organisations peuvent automatiser la génération de documents, maintenir l'intégrité du contenu structuré et prendre en charge efficacement la publication d'entreprise, gouvernementale et académique.

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}

- **Échange de données entre systèmes** – Faciliter les formats de document interopérables pour les applications d'entreprise.
- **Stockage de documents d'entreprise** – Conserver des fichiers Word structurés basés sur XML pour un stockage à long terme.
- **Génération basée sur des modèles** – Automatiser la création de documents normalisés à partir de modèles.
- **Archives numériques gouvernementales** – Produire des documents Word conformes et prêts pour XML pour les enregistrements officiels.
- **Publication académique structurée** – Générer des articles de recherche et du contenu éducatif dans un format structuré.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}

- **Pipelines JSON vers WordML** – Automatiser la conversion de données structurées en documents Word basés sur XML.
- **Génération automatisée de documents XML** – Rationaliser la création en masse de documents tout en maintenant la structure.
- **Flux de travail de documents pilotés par JSON** – Remplir directement les fichiers WordML à partir d'ensembles de données structurées.
- **Reporting structuré de qualité professionnelle** – Mettre à l'échelle la génération automatisée de documents structurés efficacement à travers les départements.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}