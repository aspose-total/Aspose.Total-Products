---
title: API Java pour rendre XSLFO en ODS
description: Exportez XSLFO vers ODS via l'API Java sans utiliser Microsoft Excel ou Adobe Reader
url_ignore: /fr/java/conversion/xslfo-to-ods/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: ODS
otherformats: TXT XLSB EXCEL XLT DIF XLTM FODS XLAM XLTX SXC XLSM MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter XSLFO vers ODS via Java" h2="Convertissez le fichier XSLFO en ODS en utilisant l'API Java sur site dans toutes les applications Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez intégrer la fonction de conversion XSLFO vers ODS dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez rendre XSLFO en XLSX. Dans la deuxième étape, vous pouvez convertir XLSX en ODS à l'aide de l'API de programmation de feuille de calcul [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le fichier XSLFO en ODS via Java" %}}
1. Ouvrez le fichier XSLFO à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez XSLFO en XLSX en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le document XLSX à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le document au format ODS en utilisant [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/)pdf/java/installation/) et [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) dans votre pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Si votre document XSLFO est protégé par un mot de passe, vous ne pouvez pas le convertir en ODS sans le mot de passe. À l'aide de l'API, vous pouvez d'abord ouvrir le document protégé à l'aide d'un mot de passe valide et le convertir ensuite. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir XSLFO protégé en ODS via Java" %}}
Lors de la conversion du fichier XSLFO en ODS, vous pouvez également ajouter un filigrane au format de votre fichier ODS de sortie. Pour ajouter un filigrane, créez un nouveau classeur pour ouvrir le fichier XLSX converti. Sélectionnez Feuille de calcul via son index, créez une forme et utilisez sa fonction addTextEffect, définissez les couleurs, la transparence, etc. Après cela, vous pouvez enregistrer votre document XLSX au format ODS avec filigrane. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



La conversion de XSLFO en **ODS (OpenDocument Spreadsheet)** garantit la compatibilité avec les applications de tableur open-source modernes. ODS préserve les styles, les formules et les tableaux, en en faisant un choix idéal pour les rapports collaboratifs et le partage de données.



{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}



* Conversion de rapports RH générés en XSLFO pour les utilisateurs de LibreOffice.

* Partage trimestriel d'analyses avec des partenaires externes au format ODS.

* Préparation de tableaux de bord opérationnels pour examen interdépartemental.

* Archivage de tableaux financiers basés sur XSLFO dans un format ouvert et pérenne.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}



* Conversion en temps réel de XSLFO en ODS pour les environnements de bureau collaboratifs.

* Exportation planifiée en lot de métriques opérationnelles à partir de XSLFO.

* Intégration dans des pipelines de reporting automatisés pour les équipes à distance.

* Génération automatique de feuilles de calcul ODS à partir de modèles XSLFO pour des rapports récurrents.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}