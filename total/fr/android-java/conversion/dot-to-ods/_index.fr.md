---
title: API Android pour convertir DOT en ODS
description: Convertir DOT en ODS dans Android via Java sans utiliser Microsoft Word ou Microsoft Excel
url: /fr/android-java/conversion/dot-to-ods/
family: total
platformtag: cpp
feature: conversion
informat: DOT
outformat: ODS
otherformats: SXC TSV XLT XLTX XLTM XLAM FODS XLSB DIF XLSX EXCEL XLSM CSV XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir DOT en ODS dans les applications Android" h2="Exportez DOT vers ODS dans Android via Java sans utiliser Microsoft<sup>&reg;</sup> Word ou Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total pour Android via Java](https://products.aspose.com/total/android-java/), vous pouvez intégrer la fonction de conversion DOT en ODS dans vos applications Android. Premièrement, vous pouvez convertir DOT en HTML en utilisant une API de manipulation et de conversion de dotuments riche en fonctionnalités [Aspose.Words pour Android via Java](https://products.aspose.com/words/android-java/). Après cela, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), vous pouvez convertir HTML en ODS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API Android pour convertir DOT en ODS" %}}
1. Ouvrez le fichier DOT à l'aide de la classe [Dotument](https://reference.aspose.com/words/java/com.aspose.words/Dotument)
2. Convertissez DOT en HTML en utilisant [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,com.aspose.words.SaveOptions) ) méthode
3. Chargez le dotument HTML à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le dotument au format ODS en utilisant [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.MéthodeSaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Android via Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et installez [Aspose.Cells pour Android via Java](https://dots.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) et [Aspose.Words pour Android via Java](https://dots.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) dans vos applications.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Supprimer les informations inutilisées d'un dotument DOT dans Android via Java" %}}
Avant de convertir DOT en ODS, vous pouvez supprimer les informations inutilisées du dotument DOT via [Aspose.Words pour Android via Java](https://products.aspose.com/words/android-java/). Parfois, vous devrez peut-être supprimer des informations inutilisées ou en double pour réduire la taille du dotument de sortie et le temps de traitement. La classe [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) vous permet de spécifier des options pour le nettoyage des dotuments. Pour supprimer les styles en double ou uniquement les styles ou listes inutilisés du dotument, vous pouvez utiliser la méthode [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Dotument#cleanup()). Vous pouvez utiliser les [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) et [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) pour détecter et supprimer les styles marqués comme « inutilisés ».
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Enregistrer le fichier ODS à diffuser dans Android via Java" %}}
Après avoir converti DOT en ODS, [Aspose.Cells pour Android via Java](https://products.aspose.com/cells/android-java/) vous permet d'enregistrer votre dotument pour le diffuser. Si vous devez enregistrer des fichiers dans un flux, vous devez créer un objet FileOutputStream, puis [enregistrer](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) le fichier à cet objet Stream en appelant la méthode d'enregistrement de [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objet.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-sxc/" name="DOT À SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-tsv/" name="DOT À TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-xlt/" name="DOT À XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-xltx/" name="DOT À XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-xltm/" name="DOT À XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-xlam/" name="DOT À XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-fods/" name="DOT À FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-xlsb/" name="DOT À XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-dif/" name="DOT À DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-xlsx/" name="DOT À XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-excel/" name="DOT À EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-xlsm/" name="DOT À XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-ods/" name="DOT À ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/android-java/conversion/dot-to-xls/" name="DOT À XLS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}