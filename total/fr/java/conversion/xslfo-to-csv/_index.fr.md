---
title: API Java pour rendre XSLFO en CSV
description: Exportez XSLFO vers CSV via l'API Java sans utiliser Microsoft Excel ou Adobe Reader
url_ignore: /fr/java/conversion/xslfo-to-csv/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: CSV
otherformats: XLT XLAM SXC XLSB EXCEL MD TSV DIF TXT XLTX XLTM FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter XSLFO vers CSV via Java" h2="Convertissez le fichier XSLFO en CSV en utilisant l'API Java sur site dans toutes les applications Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez intégrer la fonction de conversion XSLFO vers CSV dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez rendre XSLFO en XLSX. Dans la deuxième étape, vous pouvez convertir XLSX en CSV à l'aide de l'API de programmation de feuille de calcul [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le fichier XSLFO en CSV via Java" %}}
1. Ouvrez le fichier XSLFO à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez XSLFO en XLSX en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le document XLSX à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le document au format CSV en utilisant [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/)pdf/java/installation/) et [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) dans votre pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Si votre document XSLFO est protégé par un mot de passe, vous ne pouvez pas le convertir en CSV sans le mot de passe. À l'aide de l'API, vous pouvez d'abord ouvrir le document protégé à l'aide d'un mot de passe valide et le convertir ensuite. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir XSLFO protégé en CSV via Java" %}}
Lors de la conversion du fichier XSLFO en CSV, vous pouvez également ajouter un filigrane au format de votre fichier CSV de sortie. Pour ajouter un filigrane, créez un nouveau classeur pour ouvrir le fichier XLSX converti. Sélectionnez Feuille de calcul via son index, créez une forme et utilisez sa fonction addTextEffect, définissez les couleurs, la transparence, etc. Après cela, vous pouvez enregistrer votre document XLSX au format CSV avec filigrane. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



La conversion des fichiers XSLFO (Objets de mise en forme du langage de feuilles de style extensible) en **CSV (valeurs séparées par des virgules)** permet d'extraire facilement des données tabulaires pour des rapports rapides, des analyses de données et des flux de travail en intelligence commerciale. Le CSV reste un format léger compatible avec la plupart des outils d'analyse et de base de données.



{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}



* Exportation de rapports financiers à partir de mises en page XSLFO basées sur XML en CSV à des fins d'audit.

* Simplification du suivi des ventes et des stocks dans les outils BI basés sur le cloud.

* Préparation des données générées par XSLFO pour le prétraitement de l'apprentissage automatique.

* Génération de résumés CSV pour des rapports automatisés par e-mail.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}



* Conversion planifiée des factures XSLFO en CSV pour les systèmes comptables.

* Intégration dans les pipelines ETL pour rationaliser la migration des données XSLFO héritées.

* Extraction en temps réel des données opérationnelles basées sur XSLFO dans les tableaux de bord d'analyse.

* Conversion par lot automatisée pour des rapports multi-départements.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}