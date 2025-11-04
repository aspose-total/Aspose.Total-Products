---
title: Convertir POTM au format JSON via Java
description: Convertir POTM au format JSON via Java sans utiliser Microsoft Excel ou PowerPoint
url_ignore: /fr/java/conversion/potm-to-json/
family: total
platformtag: net
feature: conversion
informat: POTM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir POTM au format JSON via Java" h2="API Java sur site pour exporter POTM vers JSON sans utiliser Microsoft<sup>&reg;</sup> Excel ou PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion du format POTM au format JSON via [Aspose.Total for Java](https://products.aspose.com/total/java/) est un processus simple en deux étapes. Dans la première étape, vous pouvez exporter POTM vers HTML en utilisant [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Deuxièmement, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez convertir HTML en JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir POTM au format JSON via Java" %}}
1. Ouvrez le fichier POTM à l'aide de la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convertissez POTM en HTML en utilisant [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. Méthode ISaveOptions-)
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
À l'aide de l'API, vous pouvez également ouvrir le document protégé par mot de passe. Si votre document POTM d'entrée est protégé par un mot de passe, vous ne pouvez pas le convertir au format JSON sans utiliser le mot de passe. L'API vous permet d'ouvrir le document chiffré en passant le mot de passe correct dans un objet LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir POTM protégé au format JSON via Java" %}}
Pendant que vous convertissez POTM en JSON, vous pouvez également définir la plage de votre format JSON de sortie. Afin de définir la plage, vous pouvez ouvrir le code HTML converti à l'aide de la classe Workbook, créer une plage de données à exporter à l'aide de la méthode Cells.createRange, appeler la méthode JsonUtility.exportRangeToJson avec les références de Range & ExportRangeToJsonOptions et écrire les données JSON de la chaîne dans le fichier via Méthode BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



La transformation de POTM en JSON permet l'extraction du contenu structuré des diapositives dans un format d'échange de données flexible. JSON est idéal pour les applications web, les API et les plateformes pilotées par l'IA ayant besoin des informations des diapositives sous une forme lisible par machine.



{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}



* Conversion des tableaux et du texte des diapositives pour des tableaux de bord web dynamiques.

* Alimentation du contenu PowerPoint dans des plateformes SaaS basées sur les données.

* Exportation du contenu de la présentation pour la formation à l'IA ou l'analyse de contenu.

* Transformation des diapositives de modèle en JSON pour les outils de collaboration basés sur le cloud.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}



* Pipelines d'exportation JSON automatisés pour la gestion des diapositives en entreprise.

* Intégration avec des API REST pour des mises à jour de données de présentation en temps réel.

* Conversion en lot de modèles POTM en JSON pour des flux de travail analytiques.

* Génération JSON déclenchée pour la consommation de présentations multiplateformes.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}