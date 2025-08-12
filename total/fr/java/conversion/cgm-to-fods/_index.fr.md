---
title: API Java pour rendre CGM en FODS
description: Exportez CGM vers FODS via l'API Java sans utiliser Microsoft Excel ou Adobe Reader
url_ignore: /fr/java/conversion/cgm-to-fods/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: FODS
otherformats: ODS TSV XLTX EXCEL XLSB TXT SXC XLSM XLTM MD XLT DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter CGM vers FODS via Java" h2="Convertissez le fichier CGM en FODS en utilisant l'API Java sur site dans toutes les applications Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez intégrer la fonction de conversion CGM vers FODS dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez rendre CGM en XLSX. Dans la deuxième étape, vous pouvez convertir XLSX en FODS à l'aide de l'API de programmation de feuille de calcul [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le fichier CGM en FODS via Java" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez CGM en XLSX en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
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
Si votre document CGM est protégé par un mot de passe, vous ne pouvez pas le convertir en FODS sans le mot de passe. À l'aide de l'API, vous pouvez d'abord ouvrir le document protégé à l'aide d'un mot de passe valide et le convertir ensuite. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir CGM protégé en FODS via Java" %}}
Lors de la conversion du fichier CGM en FODS, vous pouvez également ajouter un filigrane au format de votre fichier FODS de sortie. Pour ajouter un filigrane, créez un nouveau classeur pour ouvrir le fichier XLSX converti. Sélectionnez Feuille de calcul via son index, créez une forme et utilisez sa fonction addTextEffect, définissez les couleurs, la transparence, etc. Après cela, vous pouvez enregistrer votre document XLSX au format FODS avec filigrane. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Convertissez les fichiers **Computer Graphics Metafile (CGM)** au format **FODS (Feuille de calcul OpenDocument plate)** est un moyen efficace de transformer des données techniques graphiques en feuilles de calcul structurées et ouvertes. Dans les applications **open-source basées sur Java**, cette conversion permet aux ingénieurs, chercheurs et analystes de données d'extraire des valeurs de mesure, des spécifications et des détails vectoriels à partir de diagrammes CGM dans des feuilles de calcul FODS modifiables. En tant que format XML conforme à l'ODF, FODS garantit la compatibilité avec des outils tels qu'OpenOffice, facilitant le partage et la collaboration sans contraintes propriétaires.


## ✅ Cas d'utilisation clés

- **Conversion de données techniques graphiques en feuilles de calcul**  
  Extraire des données graphiques vectorielles des fichiers CGM dans des lignes et des colonnes structurées pour l'analyse.

- **Documentation des valeurs de mesure**  
  Stocker et gérer les mesures d'ingénierie ou les résultats d'expériences dans un format de feuille de calcul portable.

- **Partage via des outils ODF**  
  Distribuer des données de feuille de calcul dérivées de CGM via des applications conformes à l'ODF.


## ⚙️ Scénarios d'automatisation

- **Bibliothèques Java comme JOpenDocument**  
  Automatisez la conversion CGM en FODS dans les flux de travail Java en utilisant des bibliothèques de manipulation de feuilles de calcul open-source.

- **Intégration de LibreOffice en mode sans tête**  
  Exécutez LibreOffice en mode sans tête à partir d'applications Java pour convertir en masse des graphiques CGM en feuilles de calcul FODS.

- **Génération massive de FODS**  
  Intégrez l'analyse de CGM et la création de FODS dans des pipelines ETL basés sur Java pour l'extraction de données à grande échelle.

- **Systèmes de traitement de données open-source**  
  Utilisez FODS comme partie des plates-formes scientifiques ou d'ingénierie alimentées par Java pour une gestion transparente des données basée sur des normes.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}