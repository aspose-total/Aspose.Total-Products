---
title: API de Java para renderizar MHTML a TXT
description: Exporte MHTML a TXT a través de la API de Java sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/java/conversion/mhtml-to-txt/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: TXT
otherformats: XLTM TSV ODS SXC TXT DIF XLAM MD XLT EXCEL XLSB XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar MHTML a TXT a través de Java" h2="Convierta el archivo MHTML a TXT utilizando la API de Java en las instalaciones dentro de cualquier aplicación Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total for Java](https://products.aspose.com/total/java/), puede integrar la función de conversión de MHTML a TXT en sus aplicaciones Java en un proceso de dos pasos. En primer lugar, al usar [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) puede renderizar MHTML a XLSX. En el segundo paso, puede convertir XLSX a TXT utilizando la API de programación de hojas de cálculo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir archivo MHTML a TXT a través de Java" %}}
1. Abra el archivo MHTML usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta MHTML a XLSX usando [SaveOptions](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
3. Cargue el documento XLSX usando la clase [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el documento en formato TXT usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/)df/java/installation/) y [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) en su pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Si su documento MHTML está protegido con contraseña, no puede convertirlo a TXT sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta MHTML protegido a TXT a través de Java" %}}
Al convertir un archivo MHTML a TXT, también puede agregar una marca de agua a su formato de archivo TXT de salida. Para agregar una marca de agua, cree un nuevo libro de trabajo para abrir el archivo XLSX convertido. Seleccione Hoja de trabajo a través de su índice, cree una Forma y use su función addTextEffect, establezca colores, transparencia y más. Después de eso, puede guardar su documento XLSX como TXT con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Convertir MHTML a TXT (texto plano) extrae todo el contenido textual de los archivos web mientras elimina el formato. Los archivos TXT son ligeros, ampliamente compatibles e ideales para la indexación de búsqueda, análisis de texto o propósitos de archivo.



{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}



* Archivar contenido web como texto plano para lectura sin conexión.

* Extraer informes textuales de páginas MHTML para análisis.

* Convertir artículos en línea o tutoriales en TXT para referencia rápida.

* Preparar contenido para procesamiento basado en texto, NLP o herramientas de IA.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}



* Conversión por lotes de MHTML a TXT para archivado web a gran escala.

* Extracción programada de datos textuales de páginas web para análisis.

* Integración con tuberías de IA/ML para procesamiento automático de texto.

* Conversión activada para monitoreo y reporte de contenido web en tiempo real.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}