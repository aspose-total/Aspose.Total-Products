---
title: API Java pour rendre TEX en TSV
description: Exportez TEX vers TSV via l'API Java sans utiliser Microsoft Excel ou Adobe Reader
url_ignore: /fr/java/conversion/tex-to-tsv/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: TSV
otherformats: SXC XLTM FODS EXCEL TSV ODS XLAM TXT XLTX XLT DIF XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter TEX vers TSV via Java" h2="Convertissez le fichier TEX en TSV en utilisant l'API Java sur site dans toutes les applications Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez intégrer la fonction de conversion TEX vers TSV dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez rendre TEX en XLSX. Dans la deuxième étape, vous pouvez convertir XLSX en TSV à l'aide de l'API de programmation de feuille de calcul [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le fichier TEX en TSV via Java" %}}
1. Ouvrez le fichier TEX à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez TEX en XLSX en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le document XLSX à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le document au format TSV en utilisant [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/)pdf/java/installation/) et [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) dans votre pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Si votre document TEX est protégé par un mot de passe, vous ne pouvez pas le convertir en TSV sans le mot de passe. À l'aide de l'API, vous pouvez d'abord ouvrir le document protégé à l'aide d'un mot de passe valide et le convertir ensuite. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir TEX protégé en TSV via Java" %}}
Lors de la conversion du fichier TEX en TSV, vous pouvez également ajouter un filigrane au format de votre fichier TSV de sortie. Pour ajouter un filigrane, créez un nouveau classeur pour ouvrir le fichier XLSX converti. Sélectionnez Feuille de calcul via son index, créez une forme et utilisez sa fonction addTextEffect, définissez les couleurs, la transparence, etc. Après cela, vous pouvez enregistrer votre document XLSX au format TSV avec filigrane. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



La conversion de TEX en **TSV (valeurs séparées par des tabulations)** fournit un format alternatif léger pour les données LaTeX numériques et textuelles, adapté à l'analyse et à l'importation de logiciels.



{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}



* Tables d'expériences académiques exportées pour l'analyse statistique.

* Ensembles de données d'ingénierie pour Python, R ou MATLAB.

* Tables LaTeX financières converties pour les plateformes d'analyse.

* Partage léger de données LaTeX entre les équipes.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}



* Conversion en lot de TEX en TSV dans les pipelines de recherche.

* Exportation automatisée de données tabulaires LaTeX pour les modèles d'IA.

* Génération en temps réel de TSV pour les tableaux de bord d'analyse collaborative.

* Intégration dans les pipelines ETL pour les ensembles de données structurées.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}