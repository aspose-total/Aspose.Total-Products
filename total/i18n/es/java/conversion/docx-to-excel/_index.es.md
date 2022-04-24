---
title: API de Java para convertir DOCX a EXCEL
description: Convierta DOCX a EXCEL a través de Java sin usar Microsoft Word o Microsoft Excel
url: /es/java/conversion/docx-to-excel/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: XLSX
otherformats: EXCEL SXC XLT XLSM XLSB XLTX XLS EXCEL TSV ODS XLAM XLTM FODS DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta DOCX a EXCEL a través de Java" h2="API de Java local para convertir DOCX a EXCEL sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Convertir DOCX a EXCEL a través de [Aspose.Total for Java](https://products.aspose.com/total/java/) es un proceso simple de dos pasos. Mediante el uso de la API de conversión y manipulación de documentos rica en funciones [Aspose.Words for Java](https://products.aspose.com/words/java/), puede exportar DOCX a HTML. Después de eso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puede convertir HTML a EXCEL.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir DOCX a EXCEL" %}}
1. Abra el archivo DOCX usando la clase [Documento] (https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Convierta DOCX a HTML usando [Guardar](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Cargue el documento HTML utilizando la clase [Libro de trabajo] (https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el documento en formato EXCEL mediante [Guardar](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya [Aspose.Words para Java](https://docxs.aspose.com/words/java/installation/) y [Aspose.Cells para Java](https://docxs.aspose.com/cells/java/ instalación/) en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}documentdocumentdocumentdocument
Antes de convertir DOCX a EXCEL, puede eliminar la información no utilizada del docxumento DOCX a través de [Aspose.Words for Java](https://products.aspose.com/words/java/). En ocasiones, es posible que deba eliminar información no utilizada o duplicada para reducir el tamaño del docxumento de salida y el tiempo de procesamiento. La clase [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) le permite especificar opciones para la limpieza de docxumentos. Para eliminar estilos duplicados o simplemente estilos o listas no utilizados del docxumento, puede usar el método [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Document#cleanup()). Puede usar [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) y [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) para detectar y eliminar estilos marcados como "sin usar".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}document
{{% /blocks/products/pf/feature-page-section %}}document
{{% blocks/products/pf/feature-page-section  h2="Eliminar información no utilizada de un docxumento DOCX a través de Java" %}}
Después de convertir DOCX a EXCEL, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) le permite guardar su docxumento para transmitir. Si necesita guardar archivos en un flujo, debe crear un objeto FileOutputStream y luego [guardar](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) el archivo a ese objeto Stream llamando al método de guardado de [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlsm/" name="DOCX Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlt/" name="DOCX Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-ods/" name="DOCX Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-tsv/" name="DOCX Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xls/" name="DOCX Para XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlsb/" name="DOCX Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-fods/" name="DOCX Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-dif/" name="DOCX Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xltx/" name="DOCX Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlam/" name="DOCX Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlsx/" name="DOCX Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xltm/" name="DOCX Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-sxc/" name="DOCX Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-excel/" name="DOCX Para EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}