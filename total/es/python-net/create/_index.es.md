---
title: Crear archivo usando Python 

description: Cree documentos de texto y Microsoft Word sin instalar Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Crear documentos usando Python" h2="Cree archivos de texto y Microsoft Word DOCX, DOC dentro de las aplicaciones de Python sin instalar Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
El almacenamiento de datos es la base de cualquier aplicación de software dependiendo de la naturaleza de la aplicación. La ubicación de almacenamiento puede ser la base de datos, XML, JSON, archivos de texto, informes de Excel o documentos de Microsoft Word. La E/S de archivos es parte de cualquier idioma y, en su mayoría, los idiomas, incluido Python, admiten la escritura de datos en archivos de texto. Consideremos el lenguaje Python. Escribir archivos de texto existentes usando Python, proporciona un método de apertura, escritura y cierre para estas tareas. En primer lugar, abra el archivo con la ruta de archivo relevante y agregue o escriba la característica como argumentos. Luego escriba el texto requerido en el archivo y, por último, cierre el archivo usando el método close(). 

Para crear documentos de Microsoft Word usando Python, usamos el paquete [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) APIs que tiene [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API como parte de su paquete. Esta API proporciona una solución completa de automatización de documentos para facturas, informes y artículos técnicos. El procedimiento de creación de documentos de Word se enumera a continuación.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Cómo crear un archivo de texto usando Python" %}}

Crear y escribir en archivos de texto es simple. Python proporciona el método open() con tres parámetros y tiene que usar uno de los parámetros junto con la ruta del archivo. Tres parámetros son "x", "a" y "w". Al proporcionar "x", se creará un nuevo archivo pero arrojará un error en caso de que el archivo ya exista. Al proporcionar "a", se creará un nuevo archivo de texto si no existe y, en caso de que exista, se agregará el contenido al final. Y, por último, al proporcionar "w", se creará un nuevo documento de texto y se sobrescribirá con el nuevo contenido en caso de que ya exista.

{{% blocks/products/pf/feature-page-code h3="Python - Crear archivo de texto" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crear documentos de Microsoft Word" %}}

Total Python Word API tiene múltiples funciones, incluida la creación de archivos de Microsoft Word, la inserción de imágenes y texto dentro de los documentos, la adición de tablas y listas dentro de los archivos, así como la modificación de documentos existentes con facilidad. Para crear un proceso de documentos de Microsoft Word, cree el objeto de las clases [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) y [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/). Agregue el texto, párrafo, listas y tablas requeridos dentro del documento y finalmente guárdelo.

{{% blocks/products/pf/feature-page-code h3="Python - Crear documentos de Microsoft Word" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}