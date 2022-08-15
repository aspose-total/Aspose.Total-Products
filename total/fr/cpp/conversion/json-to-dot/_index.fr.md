---
title: Convertir le format JSON en DOT via C++
description: API C++ pour analyser JSON vers DOT sans utiliser Microsoft Word
url: /fr/cpp/conversion/json-to-dot/
family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOT
otherformats: CHM WORDML OTT ODT PS MOBI WORD DOTX RTF DOC DOCM FLATOPC EPUB PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir le format JSON en DOT via C++" h2="Analyse JSON vers DOT dans les applications C++ sans utiliser Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total pour C++](https://products.aspose.com/total/cpp/), vous pouvez analyser JSON en DOT dans vos applications C++ en deux étapes simples. Tout d'abord, en utilisant [Aspose.Cells pour C++](https://products.aspose.com/cells/cpp/), vous pouvez exporter JSON au format PDF. Après cela, en utilisant [Aspose.Words pour C++](https://products.aspose.com/words/cppp/), vous pouvez convertir un PDF en DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en DOT en C++" %}}
1. Créez un nouvel objet [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) et lisez les données JSON valides du fichier
2. Enregistrez JSON au format PDF à l'aide de la méthode [Enregistrer](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Chargez le document PDF en utilisant la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Enregistrez le document au format DOT à l'aide de la méthode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en DOT en C++" %}}
Lors de l'analyse de JSON vers DOT, vous pouvez également définir la taille des lignes et des colonnes en chargeant JSON avec la classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Si vous devez définir la même hauteur de ligne pour toutes les lignes de la feuille de calcul, vous pouvez le faire en utilisant [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) méthode de la collection [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). De même, pour définir la même largeur de colonne pour toutes les colonnes de la feuille de calcul, utilisez la méthode [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) de la collection ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir le format JSON en DOT avec filigrane en C++" %}}
À l'aide de l'API, vous pouvez également analyser JSON en DOT avec filigrane. Afin d'ajouter un filigrane à votre document DOT, vous pouvez d'abord convertir JSON en PDF et y ajouter un filigrane. Pour ajouter un filigrane, chargez le fichier PDF nouvellement créé à l'aide de la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), définissez différentes propriétés pour le filigrane de texte,
appelez la méthode SetText et passez le texte et l'objet du filigrane de TextWatermarkOptions. Après avoir ajouté le filigrane, vous pouvez enregistrer le document sur DOT.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-dot/" name="JSON À DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-wordml/" name="JSON À WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-ott/" name="JSON À OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-odt/" name="JSON À ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-ps/" name="JSON À PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-mobi/" name="JSON À MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-word/" name="JSON À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-dotx/" name="JSON À DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-rtf/" name="JSON À RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-doc/" name="JSON À DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-docm/" name="JSON À DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-flatopc/" name="JSON À FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-epub/" name="JSON À EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/json-to-pcl/" name="JSON À PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}