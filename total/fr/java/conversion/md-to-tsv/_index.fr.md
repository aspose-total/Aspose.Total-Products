---
title: API Java pour rendre MD en TSV
description: Exportez MD vers TSV via l'API Java sans utiliser Microsoft Excel ou Adobe Reader
url: /fr/java/conversion/md-to-tsv/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: TSV
otherformats: XLT XLSB EXCEL XLAM TXT TSV SXC FODS XLSM DIF ODS XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter MD vers TSV via Java" h2="Convertissez le fichier MD en TSV en utilisant l'API Java sur site dans toutes les applications Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total pour Java](https://products.aspose.com/total/java/), vous pouvez intégrer la fonction de conversion MD vers TSV dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez rendre MD en XLSX. Dans la deuxième étape, vous pouvez convertir XLSX en TSV à l'aide de l'API de programmation de feuille de calcul [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le fichier MD en TSV via Java" %}}
1. Ouvrez le fichier MD à l'aide de la classe [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez MD en XLSX en utilisant [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le document XLSX à l'aide de la classe [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le document au format TSV en utilisant [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et inclure [Aspose.PDF pour Java](https://docs.aspose.com/pdf/java/installation/) et [Aspose.Cells pour Java](https://docs.aspose.com/cells/java/ installation/) dans votre pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Si votre document MD est protégé par un mot de passe, vous ne pouvez pas le convertir en TSV sans le mot de passe. À l'aide de l'API, vous pouvez d'abord ouvrir le document protégé à l'aide d'un mot de passe valide et le convertir ensuite. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir MD protégé en TSV via Java" %}}
Lors de la conversion du fichier MD en TSV, vous pouvez également ajouter un filigrane au format de votre fichier TSV de sortie. Pour ajouter un filigrane, créez un nouveau classeur pour ouvrir le fichier XLSX converti. Sélectionnez Feuille de calcul via son index, créez une forme et utilisez sa fonction addTextEffect, définissez les couleurs, la transparence, etc. Après cela, vous pouvez enregistrer votre document XLSX au format TSV avec filigrane. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-dif/" name="MD Pour DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-xltx/" name="MD Pour XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-md/" name="MD Pour MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-fods/" name="MD Pour FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-xltm/" name="MD Pour XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-excel/" name="MD Pour EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-xlsm/" name="MD Pour XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-xlam/" name="MD Pour XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-xlt/" name="MD Pour XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-xlsb/" name="MD Pour XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-ods/" name="MD Pour ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/md-to-sxc/" name="MD Pour SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}