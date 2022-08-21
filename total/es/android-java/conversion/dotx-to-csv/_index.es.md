---
title: API de Android para convertir DOTX a CSV
description: Convierta DOTX a CSV en Android a través de Java sin usar Microsoft Word o Microsoft Excel
url: /es/android-java/conversion/dotx-to-csv/
family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: CSV
otherformats: XLSX SXC TSV XLSB XLAM XLSM EXCEL XLS XLT XLTM FODS ODS XLTX DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta DOTX a CSV en aplicaciones de Android" h2="Exporte DOTX a CSV en Android a través de Java sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), puede integrar la función de conversión de DOTX a CSV dentro de sus aplicaciones de Android. En primer lugar, puede convertir DOTX a HTML utilizando la API de conversión y manipulación de dotxumentos rica en funciones [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Después de eso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), puede convertir HTML a CSV. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Android para convertir DOTX a CSV" %}}
1. Abra el archivo DOTX usando la clase [Dotxumento](https://reference.aspose.com/words/java/com.aspose.words/Dotxument)
2. Convierta DOTX a HTML usando [Guardar](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,com.aspose.words.SaveOptions) ) método
3. Cargue el dotxumento HTML utilizando la clase [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el dotxumento en formato CSV mediante [Guardar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total for Android via Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.Cells para Android mediante Java](https://dotxs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) y [Aspose.Words para Android vía Java](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Eliminar información no utilizada de un dotxumento DOTX en Android a través de Java" %}}
Antes de convertir DOTX a CSV, puede eliminar la información no utilizada del dotxumento DOTX a través de [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). En ocasiones, es posible que deba eliminar información no utilizada o duplicada para reducir el tamaño del dotxumento de salida y el tiempo de procesamiento. La clase [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) le permite especificar opciones para la limpieza de dotxumentos. Para eliminar estilos duplicados o simplemente estilos o listas no utilizados del dotxumento, puede usar el método [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#cleanup()). Puede usar [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) y [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) para detectar y eliminar estilos marcados como "sin usar".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotxument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Guarde el archivo CSV para transmitir en Android a través de Java" %}}
Después de convertir DOTX a CSV, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) le permite guardar su dotxumento para transmitir. Si necesita guardar archivos en un Stream, debe crear un objeto FileOutputStream y luego [guardar](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) el archivo a ese objeto Stream llamando al método de guardado de [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) objeto.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-xlsx/" name="DOTX A XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-sxc/" name="DOTX A SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-tsv/" name="DOTX A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-xlsb/" name="DOTX A XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-xlam/" name="DOTX A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-xlsm/" name="DOTX A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-excel/" name="DOTX A EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-xls/" name="DOTX A XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-xlt/" name="DOTX A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-xltm/" name="DOTX A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-fods/" name="DOTX A FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-ods/" name="DOTX A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-xltx/" name="DOTX A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/dotx-to-dif/" name="DOTX A DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}