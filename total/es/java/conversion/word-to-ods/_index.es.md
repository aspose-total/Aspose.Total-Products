---
title: API de Java para convertir WORD a ODS
description: Convierta WORD a ODS a través de Java sin usar Microsoft Word o Microsoft Excel
url: /es/java/conversion/word-to-ods/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: ODS
otherformats: SXC XLSX XLS DIF XLSB XLT XLAM TSV XLTM XLSM EXCEL XLTX FODS ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta WORD a ODS a través de Java" h2="API de Java local para convertir WORD a ODS sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Convertir WORD a ODS a través de [Aspose.Total for Java](https://products.aspose.com/total/java/) es un proceso simple de dos pasos. Mediante el uso de la API de conversión y manipulación de wordumentos rica en funciones [Aspose.Words for Java](https://products.aspose.com/words/java/), puede exportar WORD a HTML. Después de eso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puede convertir HTML a ODS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir WORD a ODS" %}}
1. Abra el archivo WORD usando la clase [Wordumento](https://apireference.aspose.com/words/java/com.aspose.words/Wordument)
2. Convierta WORD a HTML usando [Guardar](https://apireference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Cargue el wordumento HTML utilizando la clase [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el wordumento en formato ODS mediante [Guardar](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya [Aspose.Words para Java](https://words.aspose.com/words/java/installation/) y [Aspose.Cells para Java](https://words.aspose.com/cells/java/ instalación/) en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Antes de convertir WORD a ODS, puede eliminar la información no utilizada del wordumento WORD a través de [Aspose.Words for Java](https://products.aspose.com/words/java/). En ocasiones, es posible que deba eliminar información no utilizada o duplicada para reducir el tamaño del wordumento de salida y el tiempo de procesamiento. La clase [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) le permite especificar opciones para la limpieza de wordumentos. Para eliminar estilos duplicados o simplemente estilos o listas no utilizados del wordumento, puede usar el método [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Wordument#cleanup()). Puede usar [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) y [UnusedBuiltinStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) para detectar y eliminar estilos marcados como "sin usar".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-wordument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Eliminar información no utilizada de un wordumento WORD a través de Java" %}}
Después de convertir WORD a ODS, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) le permite guardar su wordumento para transmitir. Si necesita guardar archivos en un flujo, debe crear un objeto FileOutputStream y luego [guardar](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) el archivo a ese objeto Stream llamando al método de guardado de [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-xlsm/" name="WORD Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-xlt/" name="WORD Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-ods/" name="WORD Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-tsv/" name="WORD Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-xls/" name="WORD Para XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-xlsb/" name="WORD Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-fods/" name="WORD Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-dif/" name="WORD Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-xltx/" name="WORD Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-xlam/" name="WORD Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-xlsx/" name="WORD Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-xltm/" name="WORD Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-sxc/" name="WORD Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/word-to-excel/" name="WORD Para EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}