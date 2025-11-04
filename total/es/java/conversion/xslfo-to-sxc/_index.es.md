---
title: API de Java para renderizar XSLFO a SXC
description: Exporte XSLFO a SXC a través de la API de Java sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/java/conversion/xslfo-to-sxc/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: SXC
otherformats: XLSB XLTM SXC XLTX EXCEL ODS TSV MD DIF XLAM XLT TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar XSLFO a SXC a través de Java" h2="Convierta el archivo XSLFO a SXC utilizando la API de Java en las instalaciones dentro de cualquier aplicación Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total para Java](https://products.aspose.com/total/java/), puede integrar la función de conversión de XSLFO a SXC en sus aplicaciones Java en un proceso de dos pasos. En primer lugar, al usar [Aspose.PDF para Java](https://products.aspose.com/pdf/java/) puede renderizar XSLFO a XLSX. En el segundo paso, puede convertir XLSX a SXC utilizando la API de programación de hojas de cálculo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir archivo XSLFO a SXC a través de Java" %}}
1. Abra el archivo XSLFO usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta XSLFO a XLSX usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Cargue el documento XLSX usando la clase [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el documento en formato SXC usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/)pdf/java/installation/) y [Aspose.Cells para Java](https://docs.aspose.com/cells/java/installation/) en su pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Si su documento XSLFO está protegido con contraseña, no puede convertirlo a SXC sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta XSLFO protegido a SXC a través de Java" %}}
Al convertir un archivo XSLFO a SXC, también puede agregar una marca de agua a su formato de archivo SXC de salida. Para agregar una marca de agua, cree un nuevo libro de trabajo para abrir el archivo XLSX convertido. Seleccione Hoja de trabajo a través de su índice, cree una Forma y use su función addTextEffect, establezca colores, transparencia y más. Después de eso, puede guardar su documento XLSX como SXC con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



La conversión de XSLFO al formato **SXC (StarOffice Spreadsheet)** permite una interoperabilidad perfecta con las herramientas heredadas de StarOffice y OpenOffice. SXC conserva la estructura y el formato para flujos de trabajo de archivo e informes corporativos.



{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}



* Archivar programaciones de proyectos basadas en XSLFO en SXC para sistemas heredados.

* Preparar hojas de cálculo SXC para socios internacionales que utilizan StarOffice.

* Convertir datos tabulares XSLFO para fines de capacitación y documentación.

* Compartir KPI mensuales en SXC para informes de cumplimiento.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}



* Conversión automatizada por lotes de XSLFO a SXC para proyectos de archivo.

* Integración en flujos de trabajo de oficina heredados que admiten formatos de StarOffice.

* Generación programada de informes SXC a partir de archivos XSLFO.

* Conversión activada para paneles de control de gestión recurrentes.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}