---
title: API de Java para renderizar MD a FODS
description: Exporte MD a FODS a través de la API de Java sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/java/conversion/md-to-fods/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: FODS
otherformats: XLAM TSV SXC XLTX ODS FODS DIF XLSM XLTM XLSB TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar MD a FODS a través de Java" h2="Convierta el archivo MD a FODS utilizando la API de Java en las instalaciones dentro de cualquier aplicación Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total for Java](https://products.aspose.com/total/java/), puede integrar la función de conversión de MD a FODS en sus aplicaciones Java en un proceso de dos pasos. En primer lugar, al usar [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) puede renderizar MD a XLSX. En el segundo paso, puede convertir XLSX a FODS utilizando la API de programación de hojas de cálculo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir archivo MD a FODS a través de Java" %}}
1. Abra el archivo MD usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta MD a XLSX usando [SaveOptions](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
3. Cargue el documento XLSX usando la clase [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el documento en formato FODS usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/)df/java/installation/) y [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) en su pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Si su documento MD está protegido con contraseña, no puede convertirlo a FODS sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta MD protegido a FODS a través de Java" %}}
Al convertir un archivo MD a FODS, también puede agregar una marca de agua a su formato de archivo FODS de salida. Para agregar una marca de agua, cree un nuevo libro de trabajo para abrir el archivo XLSX convertido. Seleccione Hoja de trabajo a través de su índice, cree una Forma y use su función addTextEffect, establezca colores, transparencia y más. Después de eso, puede guardar su documento XLSX como FODS con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



La conversión de MD (Markdown) a FODS (Flat OpenDocument Spreadsheet) produce archivos de hojas de cálculo editables basados en XML, ideales para suites de oficina de código abierto. FODS conserva las estructuras de celdas, fórmulas y formato en un diseño totalmente basado en texto y compatible con versiones.



{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}



* Exportar conjuntos de datos de Markdown a formatos de hojas de cálculo de código abierto.

* Crear archivos FODS estructurados para usuarios de LibreOffice.

* Importar tablas de MD en hojas de cálculo XML planas para equipos de desarrollo.

* Mantener archivos de hojas de cálculo en forma legible por texto.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}



* Conversión por lotes a FODS para transparencia en el control de versiones.

* Integración de MD a FODS dentro de canalizaciones de ETL de código abierto.

* Creación automatizada de hojas de cálculo para documentación gubernamental o de ONG.

* Generación de FODS basada en desencadenadores en flujos de trabajo de documentación continua.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}