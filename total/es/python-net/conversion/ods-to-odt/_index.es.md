---
title: Convierte ODS a ODT usando Python
description: Conversión de ODS a ODT en sus aplicaciones de Python sin usar Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: ODS
outformat: ODT
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir ODS a ODT a través de Python" h2="Conversión de ODS a ODT en sus aplicaciones Python sin instalar Microsoft Excel<sup>&reg;</sup> o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador de Python, que está tratando de agregar una función de conversión de ODS a ODT dentro de la aplicación. La API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) puede ayudar a automatizar el proceso de conversión. Es un paquete completo de varias API que manejan diferentes formatos, incluidos archivos ODS y ODT.

Es principalmente en dos pasos. En primer lugar, use la API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) para convertir el archivo ODS a HTML. Después de eso, usando la API de Word Python [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), guarde el HTML creado en el formato de Microsoft Word deseado. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir ODS a ODT en Python" %}}
- **Paso 1** Abra el archivo ODS de origen usando la clase Workbook
- Guarde el archivo ODS en HTML utilizando el método save(file, SaveFormat.HTML) proporcionando el nombre del archivo y la ruta del directorio deseado
-  **Paso 2** Cargue un archivo HTML con una instancia de la clase [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Llame al método `save` mientras especifica la ruta del archivo ODT de salida. Entonces su archivo ODS se convierte a ODT en la ruta especificada

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

- Para la conversión de ODS a ODT, se requiere Python 3.5 o posterior
- API de referencia dentro del proyecto directamente desde PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) y [Aspose.Words](https://pypi.org/project/aspose-words/))
-  O use los siguientes comandos pip ```pip install aspose-cells-python``` y ```pip install aspose.words```
-  Además, el sistema operativo basado en Microsoft Windows o Linux (ver más para [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) y [Words](https://docs.aspose.com/words/python-net/system-requirements/)) y para Linux verifique los requisitos adicionales para gcc y libpython y siga [instrucciones paso a paso](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Guardar ODS en HTML en Python - Paso 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Guardar HTML en ODT en Python - Paso 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-word/" name="ODS A WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-doc/" name="ODS A DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-docx/" name="ODS A DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-docm/" name="ODS A DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-dot/" name="ODS A DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-dotm/" name="ODS A DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-dotx/" name="ODS A DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-mobi/" name="ODS A MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-odt/" name="ODS A ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-ott/" name="ODS A OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-rtf/" name="ODS A RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/python-net/conversion/ods-to-wordml/" name="ODS A WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}