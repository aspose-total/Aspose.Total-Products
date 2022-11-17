---
title: API de Android para convertir WORD a XLSX
description: Convierta WORD a XLSX en Android a través de Java sin usar Microsoft Word o Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: XLSX
otherformats: SXC XLAM XLT TSV FODS CSV DIF XLTX XLSM ODS XLSB XLS EXCEL XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta WORD a XLSX en aplicaciones de Android" h2="Exporte WORD a XLSX en Android a través de Java sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), puede integrar la función de conversión de WORD a XLSX dentro de sus aplicaciones de Android. En primer lugar, puede convertir WORD a HTML utilizando la API de conversión y manipulación de wordumentos rica en funciones [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Después de eso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), puede convertir HTML a XLSX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Android para convertir WORD a XLSX" %}}
1. Abra el archivo WORD usando la clase [Wordumento](https://reference.aspose.com/words/java/com.aspose.words/Wordument)
2. Convierta WORD a HTML usando [Guardar](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Cargue el wordumento HTML utilizando la clase [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el wordumento en formato XLSX mediante [Guardar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total for Android via Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.Cells para Android mediante Java](https://words.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) y [Aspose.Words para Android vía Java](https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Eliminar información no utilizada de un wordumento WORD en Android a través de Java" %}}
Antes de convertir WORD a XLSX, puede eliminar la información no utilizada del wordumento WORD a través de [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). En ocasiones, es posible que deba eliminar información no utilizada o duplicada para reducir el tamaño del wordumento de salida y el tiempo de procesamiento. La clase [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) le permite especificar opciones para la limpieza de wordumentos. Para eliminar estilos duplicados o simplemente estilos o listas no utilizados del wordumento, puede usar el método [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Wordument#cleanup()). Puede usar [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) y [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) para detectar y eliminar estilos marcados como "sin usar".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-wordument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Guarde el archivo XLSX para transmitir en Android a través de Java" %}}
Después de convertir WORD a XLSX, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) le permite guardar su wordumento para transmitir. Si necesita guardar archivos en un Stream, debe crear un objeto FileOutputStream y luego [guardar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) el archivo a ese objeto Stream llamando al método de guardado de [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-sxc/" name="WORD A SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-xlam/" name="WORD A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-xlt/" name="WORD A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-tsv/" name="WORD A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-fods/" name="WORD A FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-xlsx/" name="WORD A XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-dif/" name="WORD A DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-xltx/" name="WORD A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-xlsm/" name="WORD A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-ods/" name="WORD A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-xlsb/" name="WORD A XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-xls/" name="WORD A XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-excel/" name="WORD A EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/word-to-xltm/" name="WORD A XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}