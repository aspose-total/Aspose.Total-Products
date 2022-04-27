---
title: Convertir DOCX au format JSON via Java
description: Convertissez le format DOCX au format JSON via Java sans utiliser Microsoft Word ou Microsoft Excel
url: /fr/java/conversion/docx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir DOCX au format JSON via Java" h2="API Java sur site pour convertir DOCX en JSON sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion du format DOCX au format JSON via [Aspose.Total pour Java](https://products.aspose.com/total/java/) est un processus simple en deux étapes. En utilisant l'API de manipulation et de conversion de documents riche en fonctionnalités [Aspose.Words pour Java](https://products.aspose.com/words/java/), vous pouvez exporter DOCX vers HTML. Après cela, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez convertir HTML en JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir DOCX au format JSON via Java" %}}
1. Ouvrez le fichier DOCX à l'aide de la classe [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Convertissez DOCX en HTML en utilisant [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) méthode
3. Chargez le document HTML à l'aide de la classe [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le document au format JSON en utilisant [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
À l'aide de l'API, vous pouvez également ouvrir le document protégé par mot de passe. Si votre document DOCX d'entrée est protégé par un mot de passe, vous ne pouvez pas le convertir au format JSON sans utiliser le mot de passe. L'API vous permet d'ouvrir le document chiffré en passant le mot de passe correct dans un objet LoadOptions. L'exemple de code suivant montre comment essayer d'ouvrir un document chiffré avec un mot de passe :  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir le DOCX protégé au format JSON via Java" %}}
Pendant que vous convertissez DOCX en JSON, vous pouvez également définir la plage sur votre format JSON de sortie. Afin de définir la plage, vous pouvez ouvrir le code HTML converti à l'aide de la classe Workbook, créer une plage de données à exporter à l'aide de la méthode Cells.createRange, appeler la méthode JsonUtility.exportRangeToJson avec les références de Range & ExportRangeToJsonOptions et écrire les données JSON de la chaîne dans le fichier via Méthode BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xlam/" name="DOCX Pour XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xlt/" name="DOCX Pour XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-csv/" name="DOCX Pour CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xlsx/" name="DOCX Pour XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-fods/" name="DOCX Pour FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xltm/" name="DOCX Pour XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xlsm/" name="DOCX Pour XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xltx/" name="DOCX Pour XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-ods/" name="DOCX Pour ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-xlsb/" name="DOCX Pour XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-excel/" name="DOCX Pour EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-sxc/" name="DOCX Pour SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-tsv/" name="DOCX Pour TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docx-to-dif/" name="DOCX Pour DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}