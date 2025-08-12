---
title: API de Java para renderizar CGM a TXT
description: Exporte CGM a TXT a través de la API de Java sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/java/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLAM FODS XLTM ODS MD DIF EXCEL TXT XLTX XLT SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar CGM a TXT a través de Java" h2="Convierta el archivo CGM a TXT utilizando la API de Java en las instalaciones dentro de cualquier aplicación Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total for Java](https://products.aspose.com/total/java/), puede integrar la función de conversión de CGM a TXT en sus aplicaciones Java en un proceso de dos pasos. En primer lugar, al usar [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) puede renderizar CGM a XLSX. En el segundo paso, puede convertir XLSX a TXT utilizando la API de programación de hojas de cálculo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir archivo CGM a TXT a través de Java" %}}
1. Abra el archivo CGM usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta CGM a XLSX usando [SaveOptions](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
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
Si su documento CGM está protegido con contraseña, no puede convertirlo a TXT sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta CGM protegido a TXT a través de Java" %}}
Al convertir un archivo CGM a TXT, también puede agregar una marca de agua a su formato de archivo TXT de salida. Para agregar una marca de agua, cree un nuevo libro de trabajo para abrir el archivo XLSX convertido. Seleccione Hoja de trabajo a través de su índice, cree una Forma y use su función addTextEffect, establezca colores, transparencia y más. Después de eso, puede guardar su documento XLSX como TXT con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## Conversión de archivos **Computer Graphics Metafile (CGM)** a formato **TXT (Texto sin formato)**

La conversión de archivos **Computer Graphics Metafile (CGM)** a formato **TXT (Texto sin formato)** es valiosa para extraer, documentar y procesar información gráfica vectorial en una forma ligera y legible por humanos. En los **pipelines de procesamiento de datos impulsados por Java**, esta conversión permite transformar diagramas CGM en representaciones basadas en texto para registro, almacenamiento de metadatos o análisis posteriores. Al capturar los elementos descriptivos de los archivos CGM en TXT, las organizaciones pueden simplificar la integración con otros sistemas, habilitar búsquedas e indexaciones rápidas y mantener la compatibilidad a largo plazo.

## ✅ Casos de uso clave

- **Registro basado en texto de diagramas**  
  Almacene la información de los diagramas CGM como texto sin formato para auditorías, depuración o fines de archivo.

- **Extracción de descripciones gráficas vectoriales**  
  Convierta las estructuras CGM en TXT para análisis, indexación de búsquedas o integración con herramientas de análisis.

- **Documentación de metadatos de ingeniería**  
  Documente datos de ingeniería relacionados con CGM en archivos TXT para referencia rápida y almacenamiento ligero.

## ⚙️ Escenarios de automatización

- **Bibliotecas de E/S de Java para conversión**  
  Utilice las API estándar de manejo de archivos de Java junto con analizadores de CGM para extraer y escribir contenido en archivos TXT.

- **Servicios de vigilancia de archivos**  
  Automatice la conversión de CGM a TXT monitoreando directorios con `WatchService` de Java para eventos de nuevos archivos.

- **Trabajos de conversión por lotes**  
  Procese grandes volúmenes de archivos CGM en trabajos programados de Java, exportando representaciones textuales para archivo o análisis.

- **Exportadores de texto sin formato en pipelines de ETL**  
  Integre el análisis de CGM y la exportación de TXT en flujos de trabajo de Extracción-Transformación-Carga basados en Java para el procesamiento de datos estructurados.
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}