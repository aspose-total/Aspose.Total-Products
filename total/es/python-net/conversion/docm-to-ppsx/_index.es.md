---
title: Convertir DOCM a PPSX en Python
description: Conversión de DOCM a PPSX en sus aplicaciones de Python sin usar Microsoft Word o PowerPoint 
url: /es/python-net/conversion/docm-to-ppsx/
family: total
platformtag: Python
feature: conversion
informat: DOCM
outformat: PPSX
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierte DOCM a PPSX usando Python" h2="Conversión de DOCM a PPSX en sus aplicaciones Python sin instalar Microsoft Word<sup>&reg;</sup> o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador de Python, ¿quién está tratando de agregar una función de conversión de DOCM a PPSX dentro de la aplicación? La API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) puede ayudar a automatizar el proceso de conversión. Es un paquete completo de varias API que se ocupan de diferentes formatos. Asi que **¿Cómo convertir DOCM a PPSX en Python?**

Es principalmente en dos pasos. En primer lugar, use la API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) para convertir archivos DOCM a PDF. Después de eso, usando [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) de la API de Python de PowerPoint, guarde el PDF creado en la presentación como formato PPSX. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir DOCM a PPSX en Python" %}}
- **Paso 1** Abra el archivo DOCM de origen utilizando la clase [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Guarde el archivo DOCM en PDF utilizando el método [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) proporcionando el nombre del archivo y la ruta del directorio deseado.
-  **Paso 2** Cargue un archivo PDF con una instancia de la clase [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Llame al método `save` mientras especifica la ruta del archivo de salida y SaveFormat.PPSX como parámetros. Entonces, su archivo DOCM se convierte a PPSX en la ruta especificada.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

- Para la conversión de DOCM a PPSX, se requiere Python 3.5 o posterior
- Haga referencia a las API dentro del proyecto directamente desde PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) y [Aspose.Words](https://pypi.org/project/aspose-words/)) o
- Utilice los siguientes comandos pip ```pip install aspose.slides``` y ```pip install aspose.words```. Es más,
- Sistema operativo basado en Microsoft Windows o Linux (ver más para [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) y [Words](https://docs.aspose.com/words/python-net/system-requirements/)) y para Linux verifique los requisitos adicionales para gcc y libpython y siga las instrucciones paso a paso [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Guardar DOCM a PDF en Python - Paso 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Guardar PDF a PPSX en Python - Paso 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}