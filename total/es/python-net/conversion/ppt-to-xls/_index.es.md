---
title: Convierte PPT a XLS usando Python
description: Conversión de PPT a XLS en sus aplicaciones de Python sin usar Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPT
outformat: XLS
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir PPT a XLS a través de Python" h2="Conversión de PPT a XLS en sus aplicaciones Python sin instalar Microsoft PowerPoint<sup>&reg;</sup> o Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador de Python, que está tratando de agregar una función de conversión de PPT a XLS dentro de la aplicación. La API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) puede ayudar a automatizar el proceso de conversión. Es un paquete completo de varias API que manejan diferentes formatos, incluidos archivos PPT y XLS.

Es principalmente en dos pasos. En primer lugar, use la API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) para convertir el archivo PPT a HTML. Después de eso, usando Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), guarde el HTML creado en el formato de Microsoft Excel deseado. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir PPT a XLS en Python" %}}
- **Paso 1** Use la instancia de clase [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) para abrir el archivo PPT de origen 
- Guarde el archivo PPT en HTML utilizando el método [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) proporcionando el nombre del archivo y la ruta del directorio deseado
-  **Paso 2** Cargue un archivo HTML con una instancia de la clase Workbook
-  Llame al método `save` mientras especifica la ruta del archivo XLS de salida. Entonces su archivo PPT se convierte a XLS en la ruta especificada

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

- Para la conversión de PPT a XLS, se requiere Python 3.5 o posterior
- API de referencia dentro del proyecto directamente desde PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) y [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  O use los siguientes comandos pip ```pip install aspose.slides``` y ```pip install aspose-cells-python```
-  Además, SO basado en Microsoft Windows o Linux (ver más para [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) y [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Guardar PPT en HTML en Python - Paso 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Guardar HTML en XLS en Python - Paso 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}