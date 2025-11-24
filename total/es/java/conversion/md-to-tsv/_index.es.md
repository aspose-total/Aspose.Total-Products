---
title: API de Java para renderizar MD a TSV
description: Exporte MD a TSV a través de la API de Java sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/java/conversion/md-to-tsv/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: TSV
otherformats: XLT XLSB EXCEL XLAM TXT TSV SXC FODS XLSM DIF ODS XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar MD a TSV a través de Java" h2="Convierta el archivo MD a TSV utilizando la API de Java en las instalaciones dentro de cualquier aplicación Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total for Java](https://products.aspose.com/total/java/), puede integrar la función de conversión de MD a TSV en sus aplicaciones Java en un proceso de dos pasos. En primer lugar, al usar [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) puede renderizar MD a XLSX. En el segundo paso, puede convertir XLSX a TSV utilizando la API de programación de hojas de cálculo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir archivo MD a TSV a través de Java" %}}
1. Abra el archivo MD usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta MD a XLSX usando [SaveOptions](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
3. Cargue el documento XLSX usando la clase [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el documento en formato TSV usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/) e incluya [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) y [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) en su pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Si su documento MD está protegido con contraseña, no puede convertirlo a TSV sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta MD protegido a TSV a través de Java" %}}
Al convertir un archivo MD a TSV, también puede agregar una marca de agua a su formato de archivo TSV de salida. Para agregar una marca de agua, cree un nuevo libro de trabajo para abrir el archivo XLSX convertido. Seleccione Hoja de trabajo a través de su índice, cree una Forma y use su función addTextEffect, establezca colores, transparencia y más. Después de eso, puede guardar su documento XLSX como TSV con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Convertir Markdown (MD) a TSV (Valores Separados por Tabuladores) permite exportaciones de datos limpias y seguras con delimitadores ideales para desarrolladores, equipos de BI y pipelines de aprendizaje automático. Los archivos TSV conservan el espaciado y funcionan bien para conjuntos de datos que contienen comas.



{{% blocks/products/pf/agp/feature-section-col title="Casos de Uso Clave" %}}



* Exportar conjuntos de datos de Markdown a TSV para preprocesamiento de ML.

* Importar registros creados en MD en flujos de trabajo de ciencia de datos.

* Crear extractos de datos basados en TSV para el desarrollo de API.

* Convertir listas de verificación de Markdown en conjuntos de datos estructurados en pestañas.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Escenarios de Automatización" %}}



* Transformación impulsada por canalización de tablas de MD en TSV.

* Exportaciones por lotes para sistemas de ingestión de datos de IA.

* Generación regular de TSV para pruebas de integración en el backend.

* Feeds de TSV automatizados construidos a partir del contenido de Markdown del repositorio.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}