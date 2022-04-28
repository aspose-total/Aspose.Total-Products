---
title: API Java pour convertir OTT en CSV
description: Convertir OTT en CSV via Java sans utiliser Microsoft Word ou Microsoft Excel
url: /fr/java/conversion/ott-to-csv/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: CSV
otherformats: SXC TSV XLSM XLTX DIF EXCEL XLTM XLAM XLSX XLSB XLT ODS FODS XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir OTT en CSV via Java" h2="API Java sur site pour convertir OTT en CSV sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion de OTT en CSV via [Aspose.Total pour Java](https://products.aspose.com/total/java/) est un processus simple en deux étapes. En utilisant l'API de manipulation et de conversion de documents riche en fonctionnalités [Aspose.Words pour Java](https://products.aspose.com/words/java/), vous pouvez exporter OTT vers HTML. Après cela, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez convertir HTML en CSV.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir OTT en CSV" %}}
1. Ouvrez le fichier OTT à l'aide de la classe [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Convertissez OTT en HTML en utilisant [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) méthode
3. Chargez le document HTML à l'aide de la classe [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le document au format CSV en utilisant [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et inclure [Aspose.Words pour Java](https://docs.aspose.com/words/java/installation/) et [Aspose.Cells pour Java](https://docs.aspose.com/cells/java/ installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}/Document
Avant de convertir OTT en CSV, vous pouvez supprimer les informations inutilisées du document OTT via [Aspose.Words for Java](https://products.aspose.com/words/java/). Parfois, vous devrez peut-être supprimer des informations inutilisées ou en double pour réduire la taille du document de sortie et le temps de traitement. La classe [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) vous permet de spécifier des options pour le nettoyage des documents. Pour supprimer les styles en double ou uniquement les styles ou listes inutilisés du document, vous pouvez utiliser la méthode [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Vous pouvez utiliser [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) et [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) pour détecter et supprimer les styles marqués comme « inutilisés ».  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Supprimer les informations inutilisées d'un document OTT via Java" %}}
Après avoir converti OTT en CSV, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) vous permet d'enregistrer votre document pour le diffuser. Si vous devez enregistrer des fichiers dans un flux, vous devez créer un objet FileOutputStream, puis [enregistrer](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) le fichier à cet objet Stream en appelant la méthode de sauvegarde de [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objet. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-xlsm/" name="OTT Pour XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-xlt/" name="OTT Pour XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-ods/" name="OTT Pour ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-tsv/" name="OTT Pour TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-xls/" name="OTT Pour XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-xlsb/" name="OTT Pour XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-fods/" name="OTT Pour FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-dif/" name="OTT Pour DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-xltx/" name="OTT Pour XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-xlam/" name="OTT Pour XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-xlsx/" name="OTT Pour XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-xltm/" name="OTT Pour XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-sxc/" name="OTT Pour SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/ott-to-excel/" name="OTT Pour EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}