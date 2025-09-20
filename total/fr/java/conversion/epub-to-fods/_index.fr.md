---
title: API Java pour rendre EPUB en FODS
description: Exportez EPUB vers FODS via l'API Java sans utiliser Microsoft Excel ou Adobe Reader
url_ignore: /fr/java/conversion/epub-to-fods/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: FODS
otherformats: SXC XLT FODS MD XLSM XLSB XLTX EXCEL TXT XLAM XLTM TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter EPUB vers FODS via Java" h2="Convertissez le fichier EPUB en FODS en utilisant l'API Java sur site dans toutes les applications Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez intégrer la fonction de conversion EPUB vers FODS dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez rendre EPUB en XLSX. Dans la deuxième étape, vous pouvez convertir XLSX en FODS à l'aide de l'API de programmation de feuille de calcul [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le fichier EPUB en FODS via Java" %}}
1. Ouvrez le fichier EPUB à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez EPUB en XLSX en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le document XLSX à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le document au format FODS en utilisant [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et inclure [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) et [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) dans votre pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Si votre document EPUB est protégé par un mot de passe, vous ne pouvez pas le convertir en FODS sans le mot de passe. À l'aide de l'API, vous pouvez d'abord ouvrir le document protégé à l'aide d'un mot de passe valide et le convertir ensuite. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir EPUB protégé en FODS via Java" %}}
Lors de la conversion du fichier EPUB en FODS, vous pouvez également ajouter un filigrane au format de votre fichier FODS de sortie. Pour ajouter un filigrane, créez un nouveau classeur pour ouvrir le fichier XLSX converti. Sélectionnez Feuille de calcul via son index, créez une forme et utilisez sa fonction addTextEffect, définissez les couleurs, la transparence, etc. Après cela, vous pouvez enregistrer votre document XLSX au format FODS avec filigrane. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}  
La conversion **EPUB en FODS (feuilles de calcul ODS XML plates)** est essentielle pour générer des **fichiers de feuilles de calcul au format ouvert** à partir d'eBooks et de publications numériques. FODS garantit la compatibilité avec les suites bureautiques open-source, prend en charge le formatage XML structuré et permet le partage de données transparent. En transformant l'EPUB en FODS, les éditeurs, chercheurs et institutions peuvent tabuler les métadonnées, rationaliser le catalogage et partager des ensembles de données de recherche dans un format universellement accessible.  

{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}  
- **Tabulation des métadonnées** – Convertir les métadonnées d'eBook en tables de feuilles de calcul structurées.  
- **Collecte de données de recherche** – Extraire et organiser des données académiques à partir de publications numériques.  
- **Flux de travail de publication open-source** – Utiliser FODS avec LibreOffice et d'autres plateformes ouvertes.  
- **Enregistrements de catalogues de bibliothèque** – Gérer les données bibliographiques dans des feuilles de calcul au format ouvert.  
- **Partage d'ensembles de données académiques** – Distribuer des ensembles de données structurés pour la collaboration et l'analyse.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}  
- **Pipelines EPUB vers FODS** – Automatiser la conversion des publications numériques en feuilles de calcul FODS.  
- **Génération automatisée de feuilles de calcul** – Rationaliser le traitement des données de publication et de recherche.  
- **Extraction de jeux de données pilotée par XML** – Convertir le contenu d'eBook en feuilles de calcul structurées et lisibles par machine.  
- **Flux de travail de publication académique d'entreprise** – Normaliser la gestion des données de recherche à travers les institutions.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{< /blocks/products/pf/agp/feature-section >}}  
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}