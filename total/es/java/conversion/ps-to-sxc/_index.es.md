---
title: API de Java para renderizar PS a SXC
description: Exporte PS a SXC a través de la API de Java sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/java/conversion/ps-to-sxc/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SXC
otherformats: FODS XLT SXC XLAM TXT XLTX XLSM XLTM MD EXCEL DIF ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar PS a SXC a través de Java" h2="Convierta el archivo PS a SXC utilizando la API de Java en las instalaciones dentro de cualquier aplicación Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total para Java](https://products.aspose.com/total/java/), puede integrar la función de conversión de PS a SXC en sus aplicaciones Java en un proceso de dos pasos. En primer lugar, al usar [Aspose.PDF para Java](https://products.aspose.com/pdf/java/) puede renderizar PS a XLSX. En el segundo paso, puede convertir XLSX a SXC utilizando la API de programación de hojas de cálculo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir archivo PS a SXC a través de Java" %}}
1. Abra el archivo PS usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta PS a XLSX usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Cargue el documento XLSX usando la clase [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el documento en formato SXC usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/) e incluya [Aspose.PDF para Java](https://docs.aspose.com/pdf/java/installation/) y [Aspose.Cells para Java](https://docs.aspose.com/cells/java/installation/) en su pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Si su documento PS está protegido con contraseña, no puede convertirlo a SXC sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta PS protegido a SXC a través de Java" %}}
Al convertir un archivo PS a SXC, también puede agregar una marca de agua a su formato de archivo SXC de salida. Para agregar una marca de agua, cree un nuevo libro de trabajo para abrir el archivo XLSX convertido. Seleccione Hoja de trabajo a través de su índice, cree una Forma y use su función addTextEffect, establezca colores, transparencia y más. Después de eso, puede guardar su documento XLSX como SXC con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

Convertir archivos PS (PostScript) a SXC (Hoja de cálculo StarOffice/Calc) permite utilizar tablas y gráficos estructurados de PostScript en aplicaciones heredadas de OpenOffice o StarOffice. Esto garantiza la portabilidad de datos en entornos de hojas de cálculo de código abierto más antiguos.

{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}

* Extraer tablas financieras u operativas de informes PS en hojas de cálculo SXC.
* Convertir datos de ingeniería o experimentales de gráficos PostScript para su análisis.
* Preparar archivos de hojas de cálculo compatibles con versiones antiguas a partir de diseños PS.
* Transformar documentos PS en plantillas de hojas de cálculo reutilizables para herramientas de código abierto.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}

* Conversión por lotes de PS a SXC para uso en archivos o sistemas heredados.
* Integración en canalizaciones ETL para análisis estructurado de hojas de cálculo.
* Extracción automatizada de tablas y gráficos de diseños PS.
* Conversión basada en la nube para entornos colaborativos de hojas de cálculo.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}