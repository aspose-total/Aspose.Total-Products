---
title: Convertir PDF a MHTML en Python
description: Formato de archivo web PDF a mhtml y conversión de archivos HtmlFixed en sus aplicaciones de Python sin usar Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta PDF a MHTML usando Python" h2="Conversión de PDF a MHTML, HtmlFixed y HTML en sus aplicaciones Python sin instalar Microsoft Word<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un desarrollador de Python, que está tratando de agregar una función de conversión de PDF a MHTML (formato de archivo web) o HtmlFixed significa que desea guardar el documento en formato HTML utilizando elementos absolutamente posicionados dentro de la aplicación. La API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) puede ayudar a automatizar el proceso de conversión. Es un paquete completo de varias API que se ocupan de diferentes formatos. 

Usamos la API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) que forma parte del paquete [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) para agregar la función de conversión de PDF a MHTML. En caso de que el archivo PDF sea simple, son solo dos líneas de código. Cargue el archivo PDF y llame al método de guardado con la ruta de archivo adecuada junto con la enumeración SaveFormat como MHTML o HTML_FIXED. Pero en caso de que sea necesario restaurar el modelo del documento lo más cerca posible del original, entonces es necesario guardar información adicional dentro del documento resultante llamado información de ida y vuelta.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo Convertir PDF a MHTML en Python" %}}
- Cargue el archivo PDF de origen usando la clase [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Cree la instancia de [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)
- Establezca export_roundtrip_information como Verdadero
- Especifique [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) como MHTML
- Llame al método `save` mientras especifica la ruta del archivo de salida y SaveFormat como parámetros. Entonces su archivo PDF se convierte a MHTML en la ruta especificada.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}

- Para la conversión de formato PDF a MHTML o HtmlFixed, se requiere Python 3.5 o posterior
- API de referencia dentro del proyecto directamente desde PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
- O use los siguientes comandos pip ```pip install aspose.words```
- Además, el sistema operativo basado en Microsoft Windows o Linux (ver más para [Words](https://docs.aspose.com/words/python-net/system-requirements/)) y para Linux verifique los requisitos adicionales para gcc y libpython y siga las instrucciones paso a paso [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Guardar PDF en MHTML en Python - Simple" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-mhtml-simple.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Conversión de PDF a MHTML en Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "pdf-to-mhtml-conversion-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}