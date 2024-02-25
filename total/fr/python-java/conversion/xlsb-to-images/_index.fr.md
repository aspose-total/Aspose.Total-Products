---
title: Convertir XLSB en image en utilisant Python
description: Conversion de XLSB en image TIFF BMP PNG JPEG GIF EMF SVG dans vos applications Python sans utiliser Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: XLSB
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir XLSB en image via Python" h2="Conversion d'images XLSB en JPG, TIFF, BMP, PNG, GIF dans vos applications Python sans installer Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pour un développeur Python, qui essaie d'ajouter une fonctionnalité de conversion d'images XLSB en PNG, BMP, TIFF, JPEG et GIF dans l'application. Comme il est parfois nécessaire d'intégrer des feuilles de calcul Excel dans les applications Web ou de bureau. Dans de tels cas, l'exportation de feuilles de calcul vers des images est la seule solution. L'API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) peut aider à exporter des fichiers Excel vers des images ainsi qu'à automatiser le processus de conversion. Il s'agit d'un package complet de diverses API traitant différents formats, y compris les formats Microsoft Excel via son API enfant [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/). Actuellement, l'API Python Excel to Image Converter prend en charge la conversion de fichiers Excel en EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM et EMF compatible Office ou vérifiez le [Formats](https://docs.aspose.com/cells/python-java/supported-file-formats/) pris en charge. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir XLSB en images en Python" %}}

- Créer un objet de classe [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) pour charger le fichier XLSB
- Utilisez la classe [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) et spécifiez les options pertinentes de l'image de sortie
- Obtenez l'accès à la feuille de calcul pour la conversion à l'aide de la méthode [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int))
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Enregistrez toutes les pages de la feuille de calcul sous forme d'image à l'aide de la méthode [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)). Maintenant, le fichier XLSB est converti en images au chemin spécifié

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}

- Pour la conversion XLSB en images (JPG, PNG, GIF, BMP, TIFF), référencez les API dans le projet directement depuis PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Ou utilisez la commande pip suivante ```pip install aspose.cells``` 
- De plus, téléchargez le package API à partir de la section [Téléchargements](https://releases.aspose.com/cells/python-java) 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Conversion XLSB en images via Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}