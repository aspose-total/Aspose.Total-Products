---
title: API Java pour convertir WORD en CSV
description: Convertir WORD en CSV via Java sans utiliser Microsoft Word ou Microsoft Excel
url: /fr/java/conversion/word-to-csv/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: CSV
otherformats: XLSX XLSM XLT SXC XLS XLTM FODS XLSB DIF XLTX XLAM EXCEL TSV ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir WORD en CSV via Java" h2="API Java sur site pour convertir WORD en CSV sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion de WORD en CSV via [Aspose.Total pour Java](https://products.aspose.com/total/java/) est un processus simple en deux étapes. En utilisant l'API de manipulation et de conversion de documents riche en fonctionnalités [Aspose.Words pour Java](https://products.aspose.com/words/java/), vous pouvez exporter WORD vers HTML. Après cela, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez convertir HTML en CSV.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir WORD en CSV" %}}
1. Ouvrez le fichier WORD à l'aide de la classe [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Convertissez WORD en HTML en utilisant [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) méthode
3. Chargez le document HTML à l'aide de la classe [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le document au format CSV en utilisant [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et inclure [Aspose.Words pour Java](https://words.aspose.com/words/java/installation/) et [Aspose.Cells pour Java](https://words.aspose.com/cells/java/ installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Avant de convertir WORD en CSV, vous pouvez supprimer les informations inutilisées du document WORD via [Aspose.Words for Java](https://products.aspose.com/words/java/). Parfois, vous devrez peut-être supprimer des informations inutilisées ou en double pour réduire la taille du document de sortie et le temps de traitement. La classe [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) vous permet de spécifier des options pour le nettoyage des documents. Pour supprimer les styles en double ou uniquement les styles ou listes inutilisés du document, vous pouvez utiliser la méthode [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Vous pouvez utiliser [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) et [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) pour détecter et supprimer les styles marqués comme « inutilisés ».  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}(https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions))
{{% blocks/products/pf/feature-page-section  h2="Supprimer les informations inutilisées d'un document WORD via Java" %}}
Après avoir converti WORD en CSV, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) vous permet d'enregistrer votre document pour le diffuser. Si vous devez enregistrer des fichiers dans un flux, vous devez créer un objet FileOutputStream, puis [enregistrer](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) le fichier à cet objet Stream en appelant la méthode de sauvegarde de [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objet. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-xlsm/" name="WORD Pour XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-xlt/" name="WORD Pour XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-ods/" name="WORD Pour ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-tsv/" name="WORD Pour TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-xls/" name="WORD Pour XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-xlsb/" name="WORD Pour XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-fods/" name="WORD Pour FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-dif/" name="WORD Pour DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-xltx/" name="WORD Pour XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-xlam/" name="WORD Pour XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-xlsx/" name="WORD Pour XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-xltm/" name="WORD Pour XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-sxc/" name="WORD Pour SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/word-to-excel/" name="WORD Pour EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}