---
title: Convierte MOBI a XLT usando Python
description: Conversión de MOBI a XLT en sus aplicaciones de Python sin usar Microsoft Word o Excel 

family: total
platformtag: Python
feature: conversion
informat: MOBI
outformat: XLT
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir MOBI a XLT a través de Python" h2="Conversión de MOBI a XLT en sus aplicaciones Python sin instalar Microsoft Word<sup>&reg;</sup> o Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador de Python, que está tratando de agregar una función de conversión de MOBI a XLT dentro de la aplicación. La API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) puede ayudar a automatizar el proceso de conversión. Es un paquete completo de varias API que se ocupan de diferentes formatos.

Es principalmente en dos pasos. En primer lugar, use la API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) para convertir archivos MOBI a HTML. Después de eso, usando Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), guarde el HTML creado en el formato de Microsoft Excel deseado. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir MOBI a XLT en Python" %}}
- **Paso 1** Abra el archivo MOBI de origen usando la clase [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Guarde el archivo MOBI en HTML utilizando el método [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) proporcionando el nombre del archivo y la ruta del directorio deseado
-  **Paso 2** Cargue el archivo HTML con una instancia de la clase Workbook con el archivo y LoadOptions como parámetros
-  Llame al método `save` mientras especifica la ruta del archivo XLT de salida. Entonces su archivo MOBI se convierte a XLT en la ruta especificada

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

- Para la conversión de MOBI a XLT, se requiere Python 3.5 o posterior
- API de referencia dentro del proyecto directamente desde PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) y [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  O use los siguientes comandos pip ```pip install aspose.words``` y ```pip install aspose-cells-python``` 
-  Además, el sistema operativo basado en Microsoft Windows o Linux (ver más para [Words](https://docs.aspose.com/words/python-net/system-requirements/) y [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) y para Linux verifique los requisitos adicionales para gcc y libpython y siga [instrucciones paso a paso](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Guardar MOBI en HTML en Python - Paso 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Guardar HTML en XLT en Python - Paso 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}