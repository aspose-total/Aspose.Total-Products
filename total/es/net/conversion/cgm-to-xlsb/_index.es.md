---
title: Convierta CGM a XLSB a través de la API de C#
description: API C# para convertir archivos CGM a XLSB sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/net/conversion/cgm-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLSB
otherformats: XLSB TSV XLTX ODS XLSM XLT XLTM EXCEL SXC TXT FODS MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de C# para renderizar CGM a XLSB" h2="Exporte el archivo CGM a XLSB a través de C# sin usar Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total para .NET](https://products.aspose.com/total/net/) puede convertir fácilmente un archivo CGM a XLSB dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET. En primer lugar, al usar [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede exportar CGM a XLSX. Después de eso, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API de programación de hojas de cálculo, puede convertir XLSX a XLSB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir CGM a XLSB" %}}
1. Abra el archivo CGM usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta CGM a XLSX usando el método [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el documento XLSX usando la clase [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Guarde el documento en formato XLSB usando el método [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) y configure `Xlsb` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta CGM protegido a XLSB a través de C#" %}}
Si su documento CGM está protegido con contraseña, no puede convertirlo a XLSB sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia de la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) y pasar el nombre del archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir archivo CGM a XLSB con marca de agua a través de C#" %}}
Al convertir un archivo CGM a XLSB, también puede agregar una marca de agua a su formato de archivo XLSB de salida. Para agregar una marca de agua, puede crear un nuevo objeto Libro de trabajo y abrir el documento XLSX convertido, seleccionar Hoja de trabajo a través de su índice, crear una Forma y usar su función AddTextEffect. Después de eso, puede guardar su documento XLSX como XLSB con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a XLSB mediante programación: casos de uso" %}}
Los archivos de metafile de gráficos computarizados (CGM) se utilizan para almacenar información de gráficos vectoriales, lo que los hace ideales para crear gráficas estáticas y ilustraciones.

Sin embargo, cuando se trabaja con datos dinámicos, hojas de cálculo como Excel se vuelven esenciales para la visualización y análisis de datos.

La conversión de archivos de CGM a formatos de Excel es necesaria para desbloquear las capacidades completas de tu capacidad de visualización de datos e análisis. Esta conversión permite:

**Casos de uso:**

*   **Rediseñado de gráficos estáticos**: Convirtir archivos de CGM para crear gráficos estáticos optimizados, logotipos y iconos con control preciso sobre los colores, formas y tamaños.
*   Edición de gráficos y ilustraciones vectoriales: Utilizar Excel para editar gráficos vectoriales, combinar imágenes y agregar texto o efectos para mejorar el contenido visual.
*   Diseño de folleto e ajuste de diseño: Convirtir archivos de CGM para crear diseños interactivos de folletos, organizar contenido y ajustar la disposición con facilidad.
*   Creación de infografías: Utilizar Excel para diseñar gráficas atractivas, organizar datos y visualizar información compleja de manera clara y concisa.
*   Generación de informes estáticos: Convirtir archivos de CGM para generar informes interactivos, seguir indicadores clave de rendimiento (KPIs) y producir visualizaciones de alta calidad para visión de negocios.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}