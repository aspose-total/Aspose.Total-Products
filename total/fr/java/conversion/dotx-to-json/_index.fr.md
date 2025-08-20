---
title: Convertir DOTX au format JSON via Java
description: Convertissez le format DOTX au format JSON via Java sans utiliser Microsoft Word ou Microsoft Excel
url_ignore: /fr/java/conversion/dotx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir DOTX au format JSON via Java" h2="API Java sur site pour convertir DOTX en JSON sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion du format DOTX au format JSON via [Aspose.Total for Java](https://products.aspose.com/total/java/) est un processus simple en deux étapes. En utilisant l'API de manipulation et de conversion de Documents riche en fonctionnalités [Aspose.Words for Java](https://products.aspose.com/words/java/), vous pouvez exporter DOTX vers HTML. Après cela, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez convertir HTML en JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir DOTX au format JSON via Java" %}}
1. Ouvrez le fichier DOTX à l'aide de la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Convertissez DOTX en HTML en utilisant [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) méthode
3. Chargez le Document HTML à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le Document au format JSON en utilisant [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ExDocumente conversion" %}}
À l'aide de l'API, vous pouvez également ouvrir le Document protégé par mot de passe. Si votre Document DOTX d'entrée est protégé par un mot de passe, vous ne pouvez pas le convertir au format JSON sans utiliser le mot de passe. L'API vous permet d'ouvrir le Document chiffré en passant le mot de passe correct dans un objet LoadOptions. L'exemple de code suivant montre comment essayer d'ouvrir un Document chiffré avec un mot de passe :  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir le DOTX protégé au format JSON via Java" %}}
Pendant que vous convertissez DOTX en JSON, vous pouvez également définir la plage sur votre format JSON de sortie. Afin de définir la plage, vous pouvez ouvrir le code HTML converti à l'aide de la classe Workbook, créer une plage de données à exporter à l'aide de la méthode Cells.createRange, appeler la méthode JsonUtility.exportRangeToJson avec les références de Range & ExportRangeToJsonOptions et écrire les données JSON de la chaîne dans le fichier via Méthode BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Convertir **DOTX** en **JSON** permet un échange de données structurées, une intégration d'API et des flux de travail web modernes, rendant les données de document utilisables pour les services cloud, les applications web et les pipelines IA/ML.

## ✅ Cas d'utilisation clés
- Exportations de données prêtes pour les API
- Intégration d'applications web
- Services cloud
- Pipelines de données
- Préparation de jeux de données IA/ML

## ⚙️ Scénarios d'automatisation
- Pipelines DOTX-vers-JSON
- Génération automatique de JSON
- Flux de travail API cloud
- Intégrations de systèmes d'entreprise
- Automatisation du lac de données
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}