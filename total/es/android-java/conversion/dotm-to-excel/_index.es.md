---
title: API de Android para convertir DOTM a EXCEL
description: Convierta DOTM a EXCEL en Android a través de Java sin usar Microsoft Word o Microsoft Excel
url: /es/android-java/conversion/dotm-to-excel/
family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: XLSX
otherformats: XLS SXC XLT XLSX TSV XLTM XLAM FODS XLSB XLTX XLSM CSV DIF ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta DOTM a EXCEL en aplicaciones de Android" h2="Exporte DOTM a EXCEL en Android a través de Java sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/), puede integrar la función de conversión de DOTM a EXCEL dentro de sus aplicaciones de Android. En primer lugar, puede convertir DOTM a HTML utilizando la API de conversión y manipulación de dotmumentos rica en funciones [Aspose.Words para Android a través de Java](https://products.aspose.com/words/android-java/). Después de eso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), puede convertir HTML a EXCEL. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Android para convertir DOTM a EXCEL" %}}
1. Abra el archivo DOTM usando la clase [Dotmumento](https://reference.aspose.com/words/java/com.aspose.words/Dotmument)
2. Convierta DOTM a HTML usando [Guardar](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Cargue el dotmumento HTML utilizando la clase [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el dotmumento en formato EXCEL mediante [Guardar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.Cells para Android mediante Java](https://dotms.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) y [Aspose.Words para Android vía Java](https://dotms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Eliminar información no utilizada de un dotmumento DOTM en Android a través de Java" %}}
Antes de convertir DOTM a EXCEL, puede eliminar la información no utilizada del dotmumento DOTM a través de [Aspose.Words para Android a través de Java](https://products.aspose.com/words/android-java/). En ocasiones, es posible que deba eliminar información no utilizada o duplicada para reducir el tamaño del dotmumento de salida y el tiempo de procesamiento. La clase [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) le permite especificar opciones para la limpieza de dotmumentos. Para eliminar estilos duplicados o simplemente estilos o listas no utilizados del dotmumento, puede usar el método [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#cleanup()). Puede usar [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) y [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) para detectar y eliminar estilos marcados como "sin usar".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotmument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Guarde el archivo EXCEL para transmitir en Android a través de Java" %}}
Después de convertir DOTM a EXCEL, [Aspose.Cells para Android a través de Java](https://products.aspose.com/cells/android-java/) le permite guardar su dotmumento para transmitir. Si necesita guardar archivos en un Stream, debe crear un objeto FileOutputStream y luego [guardar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) el archivo a ese objeto Stream llamando al método de guardado de [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-xls/" name="DOTM A XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-sxc/" name="DOTM A SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-xlt/" name="DOTM A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-xlsx/" name="DOTM A XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-tsv/" name="DOTM A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-xltm/" name="DOTM A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-xlam/" name="DOTM A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-fods/" name="DOTM A FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-xlsb/" name="DOTM A XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-xltx/" name="DOTM A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-xlsm/" name="DOTM A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-excel/" name="DOTM A EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-dif/" name="DOTM A DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotm-to-ods/" name="DOTM A ODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}