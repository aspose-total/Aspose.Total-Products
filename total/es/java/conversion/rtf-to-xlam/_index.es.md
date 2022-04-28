---
title: API de Java para convertir RTF a XLAM
description: Convierta RTF a XLAM a través de Java sin usar Microsoft Word o Microsoft Excel
url: /es/java/conversion/rtf-to-xlam/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: XLAM
otherformats: DIF XLSX XLSM XLTM XLS XLAM XLTX TSV SXC ODS XLSB FODS XLT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta RTF a XLAM a través de Java" h2="API de Java local para convertir RTF a XLAM sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Convertir RTF a XLAM a través de [Aspose.Total for Java](https://products.aspose.com/total/java/) es un proceso simple de dos pasos. Mediante el uso de la API de conversión y manipulación de rtfumentos rica en funciones [Aspose.Words for Java](https://products.aspose.com/words/java/), puede exportar RTF a HTML. Después de eso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puede convertir HTML a XLAM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir RTF a XLAM" %}}
1. Abra el archivo RTF usando la clase [Rtfumento](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument)
2. Convierta RTF a HTML usando [Guardar](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Cargue el rtfumento HTML utilizando la clase [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el rtfumento en formato XLAM mediante [Guardar](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya [Aspose.Words para Java](https://rtfs.aspose.com/words/java/installation/) y [Aspose.Cells para Java](https://rtfs.aspose.com/cells/java/ instalación/) en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Antes de convertir RTF a XLAM, puede eliminar la información no utilizada del rtfumento RTF a través de [Aspose.Words for Java](https://products.aspose.com/words/java/). En ocasiones, es posible que deba eliminar información no utilizada o duplicada para reducir el tamaño del rtfumento de salida y el tiempo de procesamiento. La clase [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) le permite especificar opciones para la limpieza de rtfumentos. Para eliminar estilos duplicados o simplemente estilos o listas no utilizados del rtfumento, puede usar el método [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#cleanup()). Puede usar [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) y [UnusedBuiltinStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) para detectar y eliminar estilos marcados como "sin usar".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-rtfument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Eliminar información no utilizada de un rtfumento RTF a través de Java" %}}
Después de convertir RTF a XLAM, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) le permite guardar su rtfumento para transmitir. Si necesita guardar archivos en un flujo, debe crear un objeto FileOutputStream y luego [guardar](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) el archivo a ese objeto Stream llamando al método de guardado de [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xlsm/" name="RTF Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xlt/" name="RTF Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-ods/" name="RTF Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-tsv/" name="RTF Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xls/" name="RTF Para XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xlsb/" name="RTF Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-fods/" name="RTF Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-dif/" name="RTF Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xltx/" name="RTF Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xlam/" name="RTF Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xlsx/" name="RTF Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xltm/" name="RTF Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-sxc/" name="RTF Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-excel/" name="RTF Para EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}