---
title: Convertir le format JSON en WORD via Java
description: Analyser JSON en WORD en Java sans utiliser Microsoft Word
url_ignore: /fr/java/conversion/json-to-word/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WORD
otherformats: EPUB PCL WORDML WORD RTF MOBI DOT ODT PS FLATOPC DOTX OTT DOCM DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le format JSON en WORD via Java" h2="API Java sur site pour analyser JSON vers WORD sans utiliser Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez convertir JSON en WORD dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez analyser JSON en PDF. Dans la deuxième étape, vous pouvez convertir un PDF en WORD en utilisant l'API de traitement de texte [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en WORD via Java" %}}
1. Créez un nouvel objet [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et lisez les données JSON valides à partir du fichier
2. Importez le fichier JSON dans la feuille de calcul à l'aide de la classe [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) et [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) au format PDF
3. Chargez le document PDF en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format WORD en utilisant [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) méthode
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
De plus, l'API vous permet de définir des options de mise en page pour votre JSON lors de l'analyse de JSON vers WORD à l'aide de [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Il vous permet de traiter Array comme une table, d'ignorer les valeurs nulles, d'ignorer le titre du tableau, d'ignorer le titre de l'objet, de convertir une chaîne en nombre ou en date, de définir le format de la date et du nombre et de définir le style du titre. Toutes ces options vous permettent de présenter vos données selon vos besoins. L'extrait de code suivant vous montre comment définir les options de mise en page.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en WORD via Java" %}}
À l'aide de l'API, vous pouvez également analyser JSON en WORD avec filigrane. Afin d'ajouter un filigrane à votre document WORD, vous pouvez d'abord convertir le fichier JSON en PDF et y ajouter un filigrane. Pour ajouter un filigrane, chargez le fichier PDF nouvellement créé à l'aide de la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), créez une instance de TextWatermarkOptions et définissez ses propriétés, appelez la méthode Watermark.setText et transmettez le texte et l'objet du filigrane de TextWatermarkOptions. Après avoir ajouté le filigrane, vous pouvez enregistrer le document sur WORD. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Convertir **JSON en WORD** est essentiel pour transformer **des ensembles de données structurées en documents Microsoft Word modifiables**. Les fichiers Word permettent aux organisations de produire des documents entièrement modifiables, normalisés et formatés de manière professionnelle directement à partir de données structurées. En convertissant le JSON en Word, les entreprises peuvent rationaliser efficacement les rapports, la documentation juridique, la création de contenu académique et la gestion des archives gouvernementales.

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}

- **Rapports d'entreprise** – Générer des rapports structurés et modifiables pour la prise de décisions d'entreprise.
- **Contrats juridiques** – Automatiser la création d'accords et de contrats normalisés.
- **Documents académiques** – Produire des articles de recherche, des essais et des notes de cours à partir de ensembles de données structurées.
- **Archives gouvernementales** – Maintenir une documentation modifiable conforme à l'utilisation officielle.
- **Documentation d'entreprise** – Normaliser les documents d'entreprise pour les flux de travail internes et externes.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}

- **Pipelines JSON vers Word** – Automatiser la transformation de données structurées en documents Word.
- **Génération automatique de documents** – Réduire la création manuelle de contenu tout en garantissant la cohérence de la mise en forme.
- **Flux de travail de reporting à l'échelle de l'entreprise** – Mettre à l'échelle la production de documents à travers les départements de manière efficace.
- **Création de contenu pilotée par JSON** – Remplir directement des documents Word à partir de ensembles de données structurées pour plus de précision et de rapidité.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}