---
title: Convertir le format JSON en CHM via Java
description: Analyser JSON en CHM en Java sans utiliser Microsoft Word
url_ignore: /fr/java/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: FLATOPC DOCM WORD WORDML ODT RTF DOC MOBI OTT DOTX PCL DOT EPUB PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le format JSON en CHM via Java" h2="API Java sur site pour analyser JSON vers CHM sans utiliser Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez convertir JSON en CHM dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez analyser JSON en PDF. Dans la deuxième étape, vous pouvez convertir un PDF en CHM en utilisant l'API de traitement de texte [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en CHM via Java" %}}
1. Créez un nouvel objet [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et lisez les données JSON valides à partir du fichier
2. Importez le fichier JSON dans la feuille de calcul à l'aide de la classe [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) et [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) au format PDF
3. Chargez le document PDF en utilisant la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format CHM en utilisant [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) méthode
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
De plus, l'API vous permet de définir des options de mise en page pour votre JSON lors de l'analyse de JSON vers CHM à l'aide de [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Il vous permet de traiter Array comme une table, d'ignorer les valeurs nulles, d'ignorer le titre du tableau, d'ignorer le titre de l'objet, de convertir une chaîne en nombre ou en date, de définir le format de la date et du nombre et de définir le style du titre. Toutes ces options vous permettent de présenter vos données selon vos besoins. L'extrait de code suivant vous montre comment définir les options de mise en page.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en CHM via Java" %}}
À l'aide de l'API, vous pouvez également analyser JSON en CHM avec filigrane. Afin d'ajouter un filigrane à votre document CHM, vous pouvez d'abord convertir le fichier JSON en PDF et y ajouter un filigrane. Pour ajouter un filigrane, chargez le fichier PDF nouvellement créé à l'aide de la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), créez une instance de TextWatermarkOptions et définissez ses propriétés, appelez la méthode Watermark.setText et transmettez le texte et l'objet du filigrane de TextWatermarkOptions. Après avoir ajouté le filigrane, vous pouvez enregistrer le document sur CHM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Convertir **JSON en CHM (Compiled HTML Help)** est essentiel pour créer des **manuels d'aide compilés** directement à partir d'une documentation structurée. Les fichiers CHM regroupent plusieurs sujets d'aide en une seule ressource consultable et accessible hors ligne, ce qui les rend idéaux pour le support logiciel et la gestion des connaissances en entreprise. En transformant le JSON en CHM, les organisations peuvent rationaliser la livraison de la documentation, améliorer la convivialité et garantir l'accessibilité même sans connexion Internet.

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}

- **Documentation logicielle** – Regrouper des guides techniques dans un format convivial et compilé.
- **Systèmes d'aide hors ligne** – Distribuer la documentation sans nécessiter d'accès Internet.
- **Bases de connaissances d'entreprise** – Centraliser les connaissances organisationnelles dans un fichier d'aide structuré.
- **Manuels de formation** – Distribuer des ressources d'apprentissage compilées pour le personnel ou les étudiants.
- **Références API pour les développeurs** – Convertir des définitions JSON structurées en références hors ligne consultables.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}

- **Pipelines JSON vers CHM** – Automatiser la conversion de données structurées en manuels d'aide compilés.
- **Création automatisée de fichiers d'aide** – Générer des fichiers CHM directement à partir de contenu JSON évolutif.
- **Compilation de données en documentation** – Transformer la documentation JSON structurée en systèmes d'aide accessibles.
- **Distribution de connaissances hors ligne** – Normaliser les manuels CHM pour la formation et le support à l'échelle de l'entreprise.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}