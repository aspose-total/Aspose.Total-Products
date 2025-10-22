---
title: Convertir PPT au format JSON via Java
description: Convertir PPT au format JSON via Java sans utiliser Microsoft Excel ou PowerPoint
url_ignore: /fr/java/conversion/ppt-to-json/
family: total
platformtag: net
feature: conversion
informat: PPT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir PPT au format JSON via Java" h2="API Java sur site pour exporter PPT vers JSON sans utiliser Microsoft<sup>&reg;</sup> Excel ou PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion du format PPT au format JSON via [Aspose.Total for Java](https://products.aspose.com/total/java/) est un processus simple en deux étapes. Dans la première étape, vous pouvez exporter PPT vers HTML en utilisant [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Deuxièmement, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez convertir HTML en JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir PPT au format JSON via Java" %}}
1. Ouvrez le fichier PPT à l'aide de la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convertissez PPT en HTML en utilisant [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. Méthode ISaveOptions-)
3. Chargez le document HTML à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le document au format JSON en utilisant [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/)

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
À l'aide de l'API, vous pouvez également ouvrir le document protégé par mot de passe. Si votre document PPT d'entrée est protégé par un mot de passe, vous ne pouvez pas le convertir au format JSON sans utiliser le mot de passe. L'API vous permet d'ouvrir le document chiffré en passant le mot de passe correct dans un objet LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir PPT protégé au format JSON via Java" %}}
Pendant que vous convertissez PPT en JSON, vous pouvez également définir la plage de votre format JSON de sortie. Afin de définir la plage, vous pouvez ouvrir le code HTML converti à l'aide de la classe Workbook, créer une plage de données à exporter à l'aide de la méthode Cells.createRange, appeler la méthode JsonUtility.exportRangeToJson avec les références de Range & ExportRangeToJsonOptions et écrire les données JSON de la chaîne dans le fichier via Méthode BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
## Conversion des fichiers PPT (PowerPoint) en JSON (JavaScript Object Notation)

La conversion des fichiers PPT (PowerPoint) en JSON (JavaScript Object Notation) permet de traduire des données de présentation complexes en formats structurés, légers et lisibles par les machines. Ce format est idéal pour les développeurs qui intègrent des métadonnées de présentation, des diapositives ou des visuels dans des applications web et des plateformes alimentées par l'IA.

## Cas d'utilisation clés

- Extraction des métadonnées des diapositives PowerPoint pour les applications web ou mobiles.
- Intégration des données de présentation dans des tableaux de bord ou des systèmes de visualisation des données.
- Construction d'API basées sur JSON pour un rendu dynamique des diapositives.
- Prise en charge des systèmes d'IA qui interprètent le contenu PowerPoint de manière contextuelle.

## Scénarios d'automatisation

- Conversion en temps réel de PPT en JSON pour l'analyse automatisée du contenu.
- Intégration avec des systèmes de gestion de contenu sans tête ou d'indexation de documents.
- Traitement par lots pour les plateformes d'analyse nécessitant des données de présentation structurées.
- Résumé et étiquetage automatisés du contenu PowerPoint alimentés par l'IA.
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}