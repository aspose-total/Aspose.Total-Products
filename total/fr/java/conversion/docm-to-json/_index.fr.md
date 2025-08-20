---
title: Convertir DOCM au format JSON via Java
description: Convertissez le format DOCM au format JSON via Java sans utiliser Microsoft Word ou Microsoft Excel
url_ignore: /fr/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir DOCM au format JSON via Java" h2="API Java sur site pour convertir DOCM en JSON sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion du format DOCM au format JSON via [Aspose.Total for Java](https://products.aspose.com/total/java/) est un processus simple en deux étapes. En utilisant l'API de manipulation et de conversion de document riche en fonctionnalités [Aspose.Words for Java](https://products.aspose.com/words/java/), vous pouvez exporter DOCM vers HTML. Après cela, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez convertir HTML en JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir DOCM au format JSON via Java" %}}
1. Ouvrez le fichier DOCM à l'aide de la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Convertissez DOCM en HTML en utilisant [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) méthode
3. Chargez le documentHTML à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le documentau format JSON en utilisant [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
À l'aide de l'API, vous pouvez également ouvrir le documentprotégé par mot de passe. Si votre ddocumentOCM d'entrée est protégé par un mot de passe, vous ne pouvez pas le convertir au format JSON sans utiliser le mot de passe. L'API vous permet d'ouvrir le dodocumentiffré en passant le mot de passe correct dans un objet LoadOptions. L'exemple de code suivant montre comment essayer d'ouvrir un docdocumentffré avec un mot de passe :  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir le DOCM protégé au format JSON via Java" %}}
Pendant que vous convertissez DOCM en JSON, vous pouvez également définir la plage sur votre format JSON de sortie. Afin de définir la plage, vous pouvez ouvrir le code HTML converti à l'aide de la classe Workbook, créer une plage de données à exporter à l'aide de la méthode Cells.createRange, appeler la méthode JsonUtility.exportRangeToJson avec les références de Range & ExportRangeToJsonOptions et écrire les données JSON de la chaîne dans le fichier via Méthode BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## ✅ Cas d'utilisation clés

- **Publication des données du document sur les API REST/GraphQL**  
  Servir le contenu extrait de DOCM sous forme de JSON pour une consommation directe des API dans les applications web et mobiles.

- **Alimenter les bases de données NoSQL et les Data Lakes**  
  Charger les données structurées dérivées de DOCM dans MongoDB, Elasticsearch ou des Data Lakes basés sur le cloud.

- **Alimenter les tableaux de bord avec des flux JSON en temps réel**  
  Diffuser des KPI et des métriques basés sur des documents dans les tableaux de bord BI et les outils de surveillance.

- **Validation des entrées par rapport au schéma JSON**  
  Assurer la cohérence et l'intégrité en alignant les données de champ DOCM sur les règles du schéma JSON.

- **Activer les CMS sans tête ou les architectures de microservices**  
  Intégrer le contenu DOCM dans des systèmes distribués d'abord par API où JSON est la lingua franca.

## ⚙️ Scénarios d'automatisation

- **Extraction DOCM vers JSON avec mappage de champs**  
  Définir des mappings pour transformer les tables, les en-têtes et les champs en objets JSON structurés.

- **Fonctions sans serveur qui convertissent et émettent des événements JSON**  
  Déclencher des conversions lors du téléchargement de fichiers, émettant des charges utiles JSON vers des systèmes pilotés par événements.

- **Tâches ETL qui normalisent les types et les clés**  
  Normaliser les exportations DOCM en structures JSON cohérentes pour l'analyse en aval.

- **Webhooks qui poussent du JSON vers les systèmes en aval**  
  Automatiser les exportations DOCM vers JSON qui alimentent les CRM, les outils ERP ou les applications tierces.

- **Règles de gouvernance qui suppriment les macros et les informations personnelles avant l'exportation en JSON**  
  Appliquer des vérifications de conformité pour garantir des sorties JSON sûres et sanitaires à partir de fichiers activés par macro.
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}