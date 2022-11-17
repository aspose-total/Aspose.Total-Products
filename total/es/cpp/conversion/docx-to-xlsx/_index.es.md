---
title: Convertir DOCX a XLSX en C++
description: API de C++ para convertir DOCX a XLSX sin usar Microsoft Word o Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: XLSX
otherformats: FODS XLTX XLSM XLS XLT XLSB ODS CSV TSV XLTM EXCEL SXC XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para convertir DOCX a XLSX" h2="Exporte DOCX a XLSX a través de C++ sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede incluir fácilmente la función de conversión de DOCX a XLSX dentro de sus aplicaciones C++. Mediante el uso de la API de manipulación y conversión de documentos rica en funciones, potente y fácil de usar [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede exportar DOCX a HTML. Después de eso, usando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), puede convertir HTML a XLSX. Ambas API se incluyen en el paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir DOCX a XLSX" %}}
1. Abra el archivo DOCX usando la referencia de clase [Documento](https://reference.aspose.com/words/cpp/class/aspose.words.document)
2. Convierta DOCX a HTML usando la función miembro [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
3. Cargue el documento HTML utilizando la referencia de clase [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Guarde el documento en formato XLSX usando la función miembro [Guardar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Acceda a las propiedades del documento DOCX a través de C++" %}}DocumentDocument
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) también le permite acceder a las propiedades del documento del archivo DOCX y le permite tomar una decisión informada antes del proceso de conversión. Para acceder a las propiedades del documento, puede usar [BuiltInDocxumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties) para obtener propiedades integradas y [CustomDocxumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties) para obtener propiedades personalizadas. El siguiente ejemplo de código muestra cómo enumerar todas las propiedades integradas y personalizadas en un documento.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Guardar archivo XLSX para transmitir a través de C++" %}}
Después de convertir DOCX a XLSX, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) le permite guardar su documento para transmitir. Para guardar archivos en una secuencia, cree un objeto MemoryStream o FileStream y guarde el archivo en ese objeto de secuencia llamando al [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Guardar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) del objeto. Especifique el formato de archivo deseado usando la enumeración [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) al llamar a [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-fods/" name="DOCX A FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-xltx/" name="DOCX A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-xlsm/" name="DOCX A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-xls/" name="DOCX A XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-xlt/" name="DOCX A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-xlsb/" name="DOCX A XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-ods/" name="DOCX A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-xlsx/" name="DOCX A XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-tsv/" name="DOCX A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-xltm/" name="DOCX A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-excel/" name="DOCX A EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-sxc/" name="DOCX A SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-xlam/" name="DOCX A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docx-to-dif/" name="DOCX A DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}