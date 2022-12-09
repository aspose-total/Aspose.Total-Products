---
title: API Android pour convertir DOCM en DIF
description: Convertir DOCM en DIF dans Android via Java sans utiliser Microsoft Word ou Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: DIF
otherformats: FODS XLT TSV SXC XLAM XLSX XLTM EXCEL XLSB XLSM CSV XLTX XLS ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir DOCM en DIF dans les applications Android" h2="Exportez DOCM vers DIF dans Android via Java sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), vous pouvez intégrer la fonction de conversion DOCM en DIF dans vos applications Android. Premièrement, vous pouvez convertir DOCM en HTML en utilisant une API de manipulation et de conversion de docmuments riche en fonctionnalités [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Après cela, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), vous pouvez convertir HTML en DIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android pour convertir DOCM en DIF" %}}
1. Ouvrez le fichier DOCM à l'aide de la classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Convertissez DOCM en HTML en utilisant [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) méthode
3. Chargez le docmument HTML à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le docmument au format DIF en utilisant [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.MéthodeSaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total for Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.Cells for Android via Java](https://docms.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) et [Aspose.Words for Android via Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Supprimer les informations inutilisées d'un docmument DOCM dans Android via Java" %}}
Avant de convertir DOCM en DIF, vous pouvez supprimer les informations inutilisées du docmument DOCM via [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Parfois, vous devrez peut-être supprimer des informations inutilisées ou en double pour réduire la taille du docmument de sortie et le temps de traitement. La classe [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) vous permet de spécifier des options pour le nettoyage des docmuments. Pour supprimer les styles en double ou uniquement les styles ou listes inutilisés du docmument, vous pouvez utiliser la méthode [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Vous pouvez utiliser les [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) et [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) pour détecter et supprimer les styles marqués comme « inutilisés ».
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-docmument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Enregistrer le fichier DIF à diffuser dans Android via Java" %}}
Après avoir converti DOCM en DIF, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) vous permet d'enregistrer votre docmument pour le diffuser. Si vous devez enregistrer des fichiers dans un flux, vous devez créer un objet FileOutputStream, puis [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) le fichier à cet objet Stream en appelant la méthode d'enregistrement de [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objet.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-fods/" name="DOCM À FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-xlt/" name="DOCM À XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-tsv/" name="DOCM À TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-sxc/" name="DOCM À SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-xlam/" name="DOCM À XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-xlsx/" name="DOCM À XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-xltm/" name="DOCM À XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-excel/" name="DOCM À EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-xlsb/" name="DOCM À XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-xlsm/" name="DOCM À XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-dif/" name="DOCM À DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-xltx/" name="DOCM À XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-xls/" name="DOCM À XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/docm-to-ods/" name="DOCM À ODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}