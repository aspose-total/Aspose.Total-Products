---
title: Actualizar archivo XLSB usando Python
description: Modifique el documento XLSB en aplicaciones de Python sin usar Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Actualizar archivo XLSB a través de Python" h2="Modifique hojas de cálculo XLSB a través de sus aplicaciones de Python sin instalar Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador, ¿quién intenta actualizar archivos XLSB a través de la aplicación Python? La API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) puede ayudar a automatizar el proceso de actualización. Es un paquete completo de varias API que se ocupan de diferentes formatos, incluidos los archivos de Microsoft Excel. La API ASPOSE.CELL que forma parte del paquete [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) facilita este proceso de modificación. A continuación se muestra el proceso de actualización del documento XLSB.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo actualizar el archivo XLSB en Python" %}}

- Cree un nuevo objeto de clase [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) que tenga el archivo XLSB de origen como parámetro
- Acceso a la hoja de trabajo relevante utilizando el método [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Inserte nuevos datos en la celda a la que accedió usando el método [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Guarde el archivo como archivo .xlsb usando el método save () pasando el archivo con la ruta como parámetro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de modificación" %}}

- Para la modificación de XLSB, haga referencia a las API dentro del proyecto directamente desde PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- O use el siguiente comando pip ```pip install aspose.cells``` 
- Además, descargue el paquete API de la sección [Descargas](https://releases.aspose.com/cells/python-java)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código - Actualizar archivo XLSB en Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}