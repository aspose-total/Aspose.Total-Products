---
title: Convierta CGM a TXT a través de la API de C#
description: API C# para convertir archivos CGM a TXT sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/net/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLSM XLTX FODS TSV XLT XLSB XLAM MD XLTM ODS TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de C# para renderizar CGM a TXT" h2="Exporte el archivo CGM a TXT a través de C# sin usar Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total para .NET](https://products.aspose.com/total/net/) puede convertir fácilmente un archivo CGM a TXT dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET. En primer lugar, al usar [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede exportar CGM a XLSX. Después de eso, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API de programación de hojas de cálculo, puede convertir XLSX a TXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir CGM a TXT" %}}
1. Abra el archivo CGM usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta CGM a XLSX usando el método [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el documento XLSX usando la clase [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Guarde el documento en formato TXT usando el método [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) y configure `Txt` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta CGM protegido a TXT a través de C#" %}}
Si su documento CGM está protegido con contraseña, no puede convertirlo a TXT sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia de la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) y pasar el nombre del archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir archivo CGM a TXT con marca de agua a través de C#" %}}
Al convertir un archivo CGM a TXT, también puede agregar una marca de agua a su formato de archivo TXT de salida. Para agregar una marca de agua, puede crear un nuevo objeto Libro de trabajo y abrir el documento XLSX convertido, seleccionar Hoja de trabajo a través de su índice, crear una Forma y usar su función AddTextEffect. Después de eso, puede guardar su documento XLSX como TXT con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a TXT mediante programación: casos de uso" %}}
CGM (Metafile de Gráficos Computacionales) se utilizan para almacenar información de gráficos vectoriales, lo que los hace ideales para crear gráficos estáticos y ilustraciones. Sin embargo, cuando trabajamos con datos dinámicos, editors de texto como Notepad se convierten en esenciales para la manipulación básica de texto e la documentación.

La conversión de archivos CGM a formatos de texto planos es necesaria para desbloquear las capacidades de edición de texto completas. Esta conversión te permite:

**Casos de Uso:**

*   **Documentación de Datos**: Convertir los archivos CGM para crear documentación humana-readable, lo que facilita la comprensión y la compartición de información gráfica.
*   **Manipulación de texto básica**: Usar Notepad para editar y manipular los datos de texto planos extraídos de los archivos CGM, haciendo que sean adecuados para tareas de edición de texto básicas.
*   **Creación de arte ASCII**: Convertir los archivos CGM a arte ASCII, creando representaciones simples, basadas en texto, de gráficos para fines artísticos o decorativos.
*   **Importación de datos de otros herramientas**: Usar la conversión de texto planos para importar datos gráficos a otros editors de texto o software procesadores de palabras, ampliando tus capacidades de manipulación de texto.
*   **Informes básicos y depuración**: Convertir los archivos CGM para crear informes básicos y registros de depuración, lo que ayuda en la identificación de errores y problemas durante el proceso de desarrollo.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}