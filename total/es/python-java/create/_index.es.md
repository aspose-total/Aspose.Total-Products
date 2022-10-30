---
title: Crear y actualizar archivos de Microsoft Excel usando Python 
url: /es/python-java/create/
description: Cree informes de hojas de cálculo de Microsoft Excel sin instalar Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Crear informes de Excel usando Python" h2="Cree y actualice documentos de Microsoft Excel SpreadSheets XLS, XLSX dentro de las aplicaciones de Python sin instalar Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) es una API de Python para crear, leer y escribir documentos en formatos de Microsoft Excel, incluidos XLS y XLSX. Esta API es parte del paquete [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/). Además, Develpors puede escribir fácilmente código para insertar datos, imágenes, gráficos, tablas dinámicas dentro de hojas de trabajo y muchas otras funcionalidades. La API de Python también admite funciones como configurar varios [fórmulas](https://docs.aspose.com/cells/python-java/supported-formula-functions/), convertir texto en columnas, marcador inteligente y opciones de fórmula dinámica. A continuación se muestran algunos códigos de ejemplo para crear y modificar hojas de cálculo.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Cómo crear archivos de Excel usando Python" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API proporciona la clase Workbook que maneja la creación de archivos. El proceso es simple. Cree el objeto de la clase Workbook y acceda a la hoja de trabajo correspondiente proporcionando su índice. Use el método putValue para agregar el contenido en la celda a la que se accede y finalmente llame al método save() para guardar el documento con un nombre específico.

{{% blocks/products/pf/feature-page-code h3="Código 1: crear un archivo de Excel simple" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Código 2: insertar imágenes en documentos de Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Cómo actualizar archivos de Microsoft Excel usando Python" %}}

El proceso de creación y actualización del archivo de Excel es casi el mismo, excepto por la única diferencia. La diferencia es que, durante el proceso de creación, se crea el objeto Libro de trabajo vacío, mientras que durante el proceso de actualización, se necesita un archivo de Excel existente. Así que pase el archivo existente como parámetro a la clase Workbook. Resto el procedimiento es el mismo

{{% blocks/products/pf/feature-page-code h3="Código 3 - Actualizar documentos de Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}