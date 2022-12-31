---
title: Convierte CSV a PPT usando Python
description: Conversión de CSV a PPT en sus aplicaciones de Python sin usar Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: CSV
outformat: PPT
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir CSV a PPT a través de Python" h2="Conversión de CSV a PPT en sus aplicaciones Python sin instalar Microsoft Excel<sup>&reg;</sup> o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador de Python, que está tratando de agregar una función de conversión de CSV a PPT dentro de la aplicación, La API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) puede ayudar a automatizar el proceso de conversión. Es un paquete completo de varias API que manejan diferentes formatos, incluidos archivos CSV y PPT..

Es principalmente en dos pasos.. Primero use [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API para convertir archivos CSV a PDF. Después de eso, usando la API de PowerPoint Python [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/), guarde el PDF creado en el formato de Microsoft PowerPoint deseado. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir CSV a PPT en Python" %}}
- **Paso 1** Use la instancia de clase Workbook para abrir el archivo CSV de origen 
- Guarde el archivo CSV en PDF utilizando el método save proporcionando el nombre del archivo y la ruta del directorio deseado
-  **Paso 2** Cargue el archivo PDF usando la clase [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Llame al método [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) mientras especifica la ruta del archivo PPT de salida. Entonces su archivo CSV se convierte a PPT en la ruta especificada

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

- Para la conversión de CSV a PPT, se requiere Python 3.5 o posterior
- API de referencia dentro del proyecto directamente desde PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) y [Aspose.Slides](https://pypi.org/project/Aspose.Slides/))
-  O use los siguientes comandos pip ```pip install aspose-cells-python``` y ```pip install aspose.slides```
-  Además, SO basado en Microsoft Windows o Linux (ver más para [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) y [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Guardar CSV a PDF en Python - Paso 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Guardar PDF a PPT en Python - Paso 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}