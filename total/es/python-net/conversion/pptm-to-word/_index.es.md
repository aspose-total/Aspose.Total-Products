---
title: Convertir PPTM a WORD en Python
description: Conversión de PPTM a WORD en sus aplicaciones de Python sin usar Microsoft Word o PowerPoint 
url: /es/python-net/conversion/pptm-to-word/
family: total
platformtag: Python
feature: conversion
informat: PPTM
outformat: WORD
otherformats: Word DOC DOT DOCX DOCM DOTX DOTM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierte PPTM a WORD usando Python" h2="Conversión de PPTM a WORD en sus aplicaciones Python sin instalar Microsoft Word<sup>&reg;</sup> o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador de Python, ¿quién está tratando de agregar una función de conversión de PPTM a WORD dentro de la aplicación? La API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) puede ayudar a automatizar el proceso de conversión. Es un paquete completo de varias API que se ocupan de diferentes formatos. Asi que **¿Cómo convertir PPTM a WORD en Python?**

Es principalmente en dos pasos. En primer lugar, use la API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) para convertir archivos PPTM a PDF. Después de eso, usando Microsoft Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), guarde el PDF creado en Microsoft Word como formato WORD. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir PPTM a WORD en Python" %}}
-  **Paso 1** Cargue un archivo PDF con una instancia de la clase [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Llame al método `save` mientras especifica la ruta del archivo de salida y SaveFormat.PDF como parámetros. Entonces su archivo PPTM se convierte a PDF en la ruta especificada.
- **Paso 2** Abra el archivo PDF usando la clase [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Guarde el archivo PDF en un archivo WORD utilizando el método [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) proporcionando el nombre del archivo y la ruta del directorio deseado.
- Aquí hay otro fragmento de código para la conversión de PowerPoint Presentation to Word (Microsoft Powerpoint to Word)[https://products.aspose.com/total/python-net/conversion/].

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

- Para la conversión de PPTM a WORD, se requiere Python 3.5 o posterior
- Haga referencia a las API dentro del proyecto directamente desde PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) y [Aspose.Words](https://pypi.org/project/aspose-words/)) o
- Utilice los siguientes comandos pip ```pip install aspose.slides``` y ```pip install aspose.words```. Es más,
- Sistema operativo basado en Microsoft Windows o Linux (ver más para [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) y [Words](https://docs.aspose.com/words/python-net/system-requirements/)) y para Linux verifique los requisitos adicionales para gcc y libpython y siga las instrucciones paso a paso [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Guardar PPTM a PDF en Python - Paso 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-slides-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Guardar PDF a WORD en Python - Paso 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-files-to-microsoft-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}