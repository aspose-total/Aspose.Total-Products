---
title: API de Java para convertir DOCX a ODS o con el convertidor en línea gratuito
description: Convierta DOCX a ODS a través de Java o aplicación en línea sin usar Microsoft Word o Microsoft Excel o en línea. Pruebe el convertidor en línea gratuito de DOCX a ODS rápidamente antes de integrar el código. 
url_ignore: /es/java/conversion/docx-to-ods/
family: total
platformtag: net
feature: conversion
informat: DOCX
outformat: ODS
otherformats: EXCEL XLAM FODS XLSB XLT XLSM SXC ODS DIF XLSX XLS TSV XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta DOCX a ODS a través de Java o aplicación en línea" h2="API de Java local para convertir DOCX a ODS sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Convertir DOCX a ODS a través de [Aspose.Total for Java](https://products.aspose.com/total/java/) es un proceso simple de dos pasos. Mediante el uso de la API de conversión y manipulación de documentos rica en funciones [Aspose.Words for Java](https://products.aspose.com/words/java/), puede exportar DOCX a HTML. Después de eso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puede convertir HTML a ODS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Java para convertir DOCX a ODS" %}}
1. Abra el archivo DOCX usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Convierta DOCX a HTML usando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) método
3. Cargue el documento HTML utilizando la clase [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el documento en formato ODS mediante [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/)m/words/java/installation/) y [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Convertidor en línea gratuito para DOCX a ODS</h3>

<iframe title="Herramienta de conversión de ods a docx" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ods&from=docx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}document
Antes de convertir DOCX a ODS, puede eliminar la información no utilizada del Documento DOCX a través de [Aspose.Words for Java](https://products.aspose.com/words/java/). En ocasiones, es posible que deba eliminar información no utilizada o duplicada para reducir el tamaño del Documento de salida y el tiempo de procesamiento. La clase [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) le permite especificar opciones para la limpieza de Documentos. Para eliminar estilos duplicados o simplemente estilos o listas no utilizados del Documento, puede usar el método [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Puede usar [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) y [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) para detectar y eliminar estilos marcados como "sin usar".  
{{% blocks/products/pf/feature-page-code %}}
document
{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-Document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}document
{{% /blocks/products/pf/feature-page-section %}}document
{{% blocks/products/pf/feature-page-section  h2="Eliminar información no utilizada de un Documento DOCX a través de Java" %}}
Después de convertir DOCX a ODS, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) le permite guardar su Documento para transmitir. Si necesita guardar archivos en un flujo, debe crear un objeto FileOutputStream y luego [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) el archivo a ese objeto Stream llamando al método de guardado de [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}