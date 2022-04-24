---
title: API de Java para convertir ODT a XLTM
description: Convierta ODT a XLTM a través de Java sin usar Microsoft Word o Microsoft Excel
url: /es/java/conversion/odt-to-xltm/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: XLTM
otherformats: XLT XLSX FODS XLSM XLTX DIF XLS ODS EXCEL XLTM TSV SXC XLSB XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta ODT a XLTM a través de Java" h2="API de Java local para convertir ODT a XLTM sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Convertir ODT a XLTM a través de [Aspose.Total for Java](https://products.aspose.com/total/java/) es un proceso simple de dos pasos. Mediante el uso de la API de conversión y manipulación de odtumentos rica en funciones [Aspose.Words for Java](https://products.aspose.com/words/java/), puede exportar ODT a HTML. Después de eso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puede convertir HTML a XLTM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir ODT a XLTM" %}}
1. Abra el archivo ODT usando la clase [Odtumento] (https://apireference.aspose.com/words/java/com.aspose.words/Odtument)
2. Convierta ODT a HTML usando [Guardar](https://apireference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Cargue el odtumento HTML utilizando la clase [Libro de trabajo] (https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el odtumento en formato XLTM mediante [Guardar](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya [Aspose.Words para Java](https://odts.aspose.com/words/java/installation/) y [Aspose.Cells para Java](https://odts.aspose.com/cells/java/ instalación/) en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Antes de convertir ODT a XLTM, puede eliminar la información no utilizada del odtumento ODT a través de [Aspose.Words for Java](https://products.aspose.com/words/java/). En ocasiones, es posible que deba eliminar información no utilizada o duplicada para reducir el tamaño del odtumento de salida y el tiempo de procesamiento. La clase [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) le permite especificar opciones para la limpieza de odtumentos. Para eliminar estilos duplicados o simplemente estilos o listas no utilizados del odtumento, puede usar el método [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Odtument#cleanup()). Puede usar [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) y [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) para detectar y eliminar estilos marcados como "sin usar".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-odtument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Eliminar información no utilizada de un odtumento ODT a través de Java" %}}
Después de convertir ODT a XLTM, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) le permite guardar su odtumento para transmitir. Si necesita guardar archivos en un flujo, debe crear un objeto FileOutputStream y luego [guardar](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) el archivo a ese objeto Stream llamando al método de guardado de [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-xlsm/" name="ODT Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-xlt/" name="ODT Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-ods/" name="ODT Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-tsv/" name="ODT Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-xls/" name="ODT Para XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-xlsb/" name="ODT Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-fods/" name="ODT Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-dif/" name="ODT Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-xltx/" name="ODT Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-xlam/" name="ODT Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-xlsx/" name="ODT Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-xltm/" name="ODT Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-sxc/" name="ODT Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/odt-to-excel/" name="ODT Para EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}