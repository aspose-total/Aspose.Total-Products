---
title: API Java pour convertir DOT en SXC
description: Convertir DOT en SXC via Java sans utiliser Microsoft Word ou Microsoft Excel
url: /fr/java/conversion/dot-to-sxc/
family: total
platformtag: net
feature: conversion
informat: DOT
outformat: SXC
otherformats: ODS FODS XLT EXCEL XLSB DIF XLSX SXC XLS XLSM XLTM XLAM XLTX TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir DOT en SXC via Java" h2="API Java sur site pour convertir DOT en SXC sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversion de DOT en SXC via [Aspose.Total pour Java](https://products.aspose.com/total/java/) est un processus simple en deux étapes. En utilisant l'API de manipulation et de conversion de dotuments riche en fonctionnalités [Aspose.Words pour Java](https://products.aspose.com/words/java/), vous pouvez exporter DOT vers HTML. Après cela, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez convertir HTML en SXC.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ pour convertir DOT en SXC" %}}
1. Ouvrez le fichier DOT à l'aide de la classe [Dotument](https://apireference.aspose.com/words/java/com.aspose.words/Dotument)
2. Convertissez DOT en HTML en utilisant [Save](https://apireference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,com.aspose.words.SaveOptions) ) méthode
3. Chargez le dotument HTML à l'aide de la classe [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le dotument au format SXC en utilisant [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et inclure [Aspose.Words pour Java](https://docs.aspose.com/words/java/installation/) et [Aspose.Cells pour Java](https://docs.aspose.com/cells/java/ installation/) dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Avant de convertir DOT en SXC, vous pouvez supprimer les informations inutilisées du dotument DOT via [Aspose.Words for Java](https://products.aspose.com/words/java/). Parfois, vous devrez peut-être supprimer des informations inutilisées ou en double pour réduire la taille du dotument de sortie et le temps de traitement. La classe [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) vous permet de spécifier des options pour le nettoyage des dotuments. Pour supprimer les styles en double ou uniquement les styles ou listes inutilisés du dotument, vous pouvez utiliser la méthode [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Dotument#cleanup()). Vous pouvez utiliser [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) et [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) pour détecter et supprimer les styles marqués comme « inutilisés ».  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Supprimer les informations inutilisées d'un dotument DOT via Java" %}}
Après avoir converti DOT en SXC, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) vous permet d'enregistrer votre dotument pour le diffuser. Si vous devez enregistrer des fichiers dans un flux, vous devez créer un objet FileOutputStream, puis [enregistrer](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) le fichier à cet objet Stream en appelant la méthode de sauvegarde de [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objet. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-xlsm/" name="DOT Pour XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-xlt/" name="DOT Pour XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-ods/" name="DOT Pour ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-tsv/" name="DOT Pour TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-xls/" name="DOT Pour XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-xlsb/" name="DOT Pour XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-fods/" name="DOT Pour FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-dif/" name="DOT Pour DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-xltx/" name="DOT Pour XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-xlam/" name="DOT Pour XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-xlsx/" name="DOT Pour XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-xltm/" name="DOT Pour XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-sxc/" name="DOT Pour SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/dot-to-excel/" name="DOT Pour EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}