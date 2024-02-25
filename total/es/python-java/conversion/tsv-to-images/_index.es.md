---
title: Convierta TSV a imagen usando Python
description: Conversión de TSV a imagen TIFF BMP PNG JPEG GIF EMF SVG en sus aplicaciones de Python sin usar Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: TSV
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta TSV a imagen a través de Python" h2="Conversión de imágenes TSV a JPG, TIFF, BMP, PNG, GIF en sus aplicaciones de Python sin instalar Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador de Python, que está tratando de agregar una función de conversión de imagen TSV a PNG, BMP, TIFF, JPEG y GIF dentro de la aplicación. Como a veces es necesario incrustar hojas de cálculo de Excel en las aplicaciones web o de escritorio. En tales casos, exportar hojas de cálculo a imágenes es la única solución. La API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) puede ayudar a exportar archivos de Excel a imágenes, así como a automatizar el proceso de conversión. Es un paquete completo de varias API que manejan diferentes formatos, incluidos los formatos de Microsoft Excel a través de su API secundaria [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/). Actualmente, Python Excel to Image Converter API admite la conversión de archivos de Excel a EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM y EMF compatibles con Office o verifique el [Formatos](https://docs.aspose.com/cells/python-java/supported-file-formats/) compatible. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir TSV a imágenes en Python" %}}

- Cree un objeto de clase [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) para cargar el archivo TSV
- Use la clase [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) y especifique las opciones relevantes de la imagen de salida
- Obtenga acceso a la hoja de trabajo para la conversión usando el método [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int))
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Guarde todas las páginas de la hoja de trabajo como una imagen usando el método [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)). Ahora el archivo TSV se convierte en imágenes en la ruta especificada

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

- Para la conversión de TSV a imágenes (JPG, PNG, GIF, BMP, TIFF), haga referencia a las API dentro del proyecto directamente desde PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- O use el siguiente comando pip ```pip install aspose.cells``` 
- Además, descargue el paquete API de la sección [Descargas](https://releases.aspose.com/cells/python-java) 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Conversión de TSV a imágenes a través de Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}