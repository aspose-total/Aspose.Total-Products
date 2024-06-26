---
title: Crear TSV en Python
description: Genere un archivo TSV usando aplicaciones de Python sin usar Microsoft Office. 

family: total
platformtag: Python
feature: create
informat: TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Crear TSV usando Python" h2="Genere TSV a través de sus aplicaciones Python sin instalar Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador, ¿quién intenta crear archivos TSV a través de la aplicación Python? La API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) puede ayudar a automatizar el proceso de creación. Es un paquete completo de varias API que manejan diferentes formatos, incluidos archivos e imágenes de Microsoft Office. La API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) que forma parte del paquete [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) facilita este proceso de generación. A continuación se muestra el proceso de creación. Además, los desarrolladores pueden mejorar fácilmente la aplicación para modificar el archivo TSV. Actualizar el archivo TSV utilizando el proceso de Python es el mismo, excepto que requiere un archivo existente como parámetro al crear el objeto Libro de trabajo.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo crear un archivo TSV en Python" %}}

- Cree un nuevo objeto de clase [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) que tenga ExpedienteFormatType como parámetro
- Obtenga el acceso de [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet) requerido usando el método [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Insertar datos en la celda a la que se accede utilizando el método [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Guarde el documento como archivo .tsv usando [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String)) pasando el archivo con la ruta como parámetro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de creación" %}}

- Para la generación de TSV, haga referencia a las API dentro del proyecto directamente desde PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- O use el siguiente comando pip ```pip install aspose.cells``` 
- Además, descargue el paquete API de la sección [downloads](https://releases.aspose.com/cells/python-java) 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Crear TSV en Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}