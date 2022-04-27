---
title: API Java pour convertir DOCM en TSV
description: Convertir DOCM en TSV via Java sans utiliser Microsoft Word ou Microsoft Excel
url: /fr/java/conversion/docm-to-tsv/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: TSV
otherformats: TSV SXC FODS XLSB XLAM XLTX XLSX ODS XLS XLSM DIF XLTM EXCEL XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir DOCM en TSV via Java" h2="API Java sur site pour convertir DOCM en TSV sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion de DOCM en TSV via [Aspose.Total pour Java](https://products.aspose.com/total/java/) est un processus simple en deux étapes. En utilisant l'API de manipulation et de conversion de document riche en fonctionnalités [Aspose.Words pour Java](https://products.aspose.com/words/java/), vous pouvez exporter DOCM vers HTML. Après cela, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez convertir HTML en TSV.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir DOCM en TSV" %}}
1. Ouvrez le fichier DOCM à l'aide de la classe [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Convertissez DOCM en HTML en utilisant [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) méthode
3. Chargez le documentHTML à l'aide de la classe [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le documentau format TSV en utilisant [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et inclure [Aspose.Words pour Java](https://docms.aspose.com/words/java/installation/) et [Aspose.Cells pour Java](https://docms.aspose.com/cells/java/ installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}Document
Avant de convertir DOCM en TSV, vous pouvez supprimer les informations inutilisées du documentDOCM via [Aspose.Words for Java](https://products.aspose.com/words/java/). Parfois, vous devrez peut-être supprimer des informations inutilisées ou en double pour réduire la taille du ddocumente sortie et le temps de traitement. La classe [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) vous permet de spécifier des options pour le nettoyage des dodocumentPour supprimer les styles en double ou uniquement les styles ou listes inutilisés du docdocumentus pouvez utiliser la méthode [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Docmument#cleanup()). Vous pouvez utiliser [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) et [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) pour détecter et supprimer les styles marqués comme « inutilisés ».  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-documentjava" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Supprimer les informations inutilisées d'un documentDOCM via Java" %}}
Après avoir converti DOCM en TSV, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) vous permet d'enregistrer votre documentpour le diffuser. Si vous devez enregistrer des fichiers dans un flux, vous devez créer un objet FileOutputStream, puis [enregistrer](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) le fichier à cet objet Stream en appelant la méthode de sauvegarde de [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objet. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-xlsm/" name="DOCM Pour XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-xlt/" name="DOCM Pour XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-ods/" name="DOCM Pour ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-tsv/" name="DOCM Pour TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-xls/" name="DOCM Pour XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-xlsb/" name="DOCM Pour XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-fods/" name="DOCM Pour FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-dif/" name="DOCM Pour DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-xltx/" name="DOCM Pour XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-xlam/" name="DOCM Pour XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-xlsx/" name="DOCM Pour XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-xltm/" name="DOCM Pour XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-sxc/" name="DOCM Pour SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/docm-to-excel/" name="DOCM Pour EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}