---
title: Convertir DOCM a XLSX en C++
description: API de C++ para convertir DOCM a XLSX sin usar Microsoft Word o Microsoft Excel
url: /es/cpp/conversion/docm-to-xlsx/
family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: XLSX
otherformats: ODS XLTM XLAM FODS DIF XLS XLSM TSV XLTX EXCEL XLSB SXC CSV XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para convertir DOCM a XLSX" h2="Exporte DOCM a XLSX a través de C++ sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede incluir fácilmente la función de conversión de DOCM a XLSX dentro de sus aplicaciones C++. Mediante el uso de la API de manipulación y conversión de docmumentos rica en funciones, potente y fácil de usar [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede exportar DOCM a HTML. Después de eso, usando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), puede convertir HTML a XLSX. Ambas API se incluyen en el paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir DOCM a XLSX" %}}
1. Abra el archivo DOCM usando la referencia de clase [Documento](https://reference.aspose.com/words/cpp/class/aspose.words.docmument)
2. Convierta DOCM a HTML usando la función miembro [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_string_saveformat)
3. Cargue el docmumento HTML utilizando la referencia de clase [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Guarde el docmumento en formato XLSX usando la función miembro [Guardar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Acceda a las propiedades del docmumento DOCM a través de C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) también le permite acceder a las propiedades del docmumento del archivo DOCM y le permite tomar una decisión informada antes del proceso de conversión. Para acceder a las propiedades del docmumento, puede usar [BuiltInDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_docmument_properties) para obtener propiedades integradas y [CustomDocumentProperties](https://https://reference.aspose.com/words/cpp/class/aspose.words.properties.custom_docmument_properties) para obtener propiedades personalizadas. El siguiente ejemplo de código muestra cómo enumerar todas las propiedades integradas y personalizadas en un docmumento.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-docmument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Guardar archivo XLSX para transmitir a través de C++" %}}
Después de convertir DOCM a XLSX, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) le permite guardar su docmumento para transmitir. Para guardar archivos en una secuencia, cree un objeto MemoryStream o FileStream y guarde el archivo en ese objeto de secuencia llamando al [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Guardar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) del objeto. Especifique el formato de archivo deseado usando la enumeración [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) al llamar a [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-ods/" name="DOCM A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-xltm/" name="DOCM A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-xlam/" name="DOCM A XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-fods/" name="DOCM A FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-dif/" name="DOCM A DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-xls/" name="DOCM A XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-xlsm/" name="DOCM A XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-tsv/" name="DOCM A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-xltx/" name="DOCM A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-excel/" name="DOCM A EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-xlsb/" name="DOCM A XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-sxc/" name="DOCM A SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-xlsx/" name="DOCM A XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/docm-to-xlt/" name="DOCM A XLT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}