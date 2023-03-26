---
title: Convertir le format JSON en POT via C++
description: Analyser JSON en POT en C++ sans utiliser Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POT
otherformats: OTP ODP PPSX PPT POTM PPS PPTM POTX PPSM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir le format JSON en POT via C++" h2="API C++ pour analyser JSON vers POT sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Vous pouvez convertir JSON en POT dans n'importe quelle application C++ en deux étapes simples. Tout d'abord, en utilisant [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), vous pouvez analyser JSON en PPTX. Après cela, en utilisant [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), vous pouvez convertir PPTX en POT. Les deux API relèvent du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en POT via C++" %}}
1. Créez un nouvel objet [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) et lisez les données JSON valides du fichier
2. Enregistrez JSON au format PPTX à l'aide de la méthode [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Chargez le document PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Enregistrez le document au format POT à l'aide de la méthode [Enregistrer](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en POT via C++" %}}
Lors de l'analyse de JSON vers POT, vous pouvez également définir la taille des lignes et des colonnes en chargeant JSON avec la classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Si vous devez définir la même hauteur de ligne pour toutes les lignes de la feuille de calcul, vous pouvez le faire en utilisant [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) méthode de la collection [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). De même, pour définir la même largeur de colonne pour toutes les colonnes de la feuille de calcul, utilisez la méthode [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) de la collection ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir le format JSON en POT avec filigrane en C++" %}}
À l'aide de l'API, vous pouvez également convertir JSON en POT avec filigrane. Afin d'ajouter un filigrane à votre document POT, vous pouvez d'abord analyser JSON en PPTX et y ajouter un filigrane. Pour ajouter un filigrane, chargez le fichier PPTX nouvellement créé à l'aide de la classe [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), obtenez la première diapositive, ajoutez un AutoShape de type Rectangle, ajoutez TextFrame au Rectangle, créez l'objet Paragraph pour un cadre de texte, créez l'objet Portion pour le paragraphe, ajoutez un filigrane à l'aide de set_Text() et pouvez enregistrer le document dans POT.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}