---
title: API de Java para renderizar PDF a XLSM
description: Exporte PDF a XLSM a través de la API de Java sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/java/conversion/pdf-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: XLSM
otherformats: DIF ODS SXC FODS XLSB EXCEL MD XLT XLSM XLTM XLAM TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar PDF a XLSM a través de Java" h2="Convierta el archivo PDF a XLSM utilizando la API de Java en las instalaciones dentro de cualquier aplicación Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total for Java](https://products.aspose.com/total/java/), puede integrar la función de conversión de PDF a XLSM en sus aplicaciones Java en un proceso de dos pasos. En primer lugar, al usar [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) puede renderizar PDF a XLSX. En el segundo paso, puede convertir XLSX a XLSM utilizando la API de programación de hojas de cálculo [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir archivo PDF a XLSM a través de Java" %}}
1. Abra el archivo PDF usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta PDF a XLSX usando [SaveOptions](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) método
3. Cargue el documento XLSX usando la clase [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el documento en formato XLSM usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/) e incluya [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) y [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) en su pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Si su documento PDF está protegido con contraseña, no puede convertirlo a XLSM sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta PDF protegido a XLSM a través de Java" %}}
Al convertir un archivo PDF a XLSM, también puede agregar una marca de agua a su formato de archivo XLSM de salida. Para agregar una marca de agua, cree un nuevo libro de trabajo para abrir el archivo XLSX convertido. Seleccione Hoja de trabajo a través de su índice, cree una Forma y use su función addTextEffect, establezca colores, transparencia y más. Después de eso, puede guardar su documento XLSX como XLSM con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
Convertir **PDF a XLSM** permite a las organizaciones generar hojas de cálculo de Excel con macros directamente a partir de datos en PDF. Las herramientas en línea y la automatización de PDF a XLSM capacitan a las empresas para integrar cálculos avanzados, scripts y flujos de trabajo en archivos de Excel.
{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}
- Modelos automatizados de pronóstico financiero  
- Conjuntos de datos de investigación con scripts reutilizables  
- Verificaciones de cumplimiento con macros integradas  
- Paneles de inteligencia empresarial  
- Automatización de hojas de cálculo a nivel empresarial
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}
- Tuberías automatizadas de PDF a XLSM para informes  
- Generación por lotes de XLSM con macros  
- Conversión de modelos financieros a partir de informes en PDF  
- Automatización de flujos de trabajo con Excel habilitado para macros  
- Integración de macros a nivel empresarial
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}