---
title: API .NET para convertir DOCX a CSV
description: API de C# para convertir DOCX a CSV sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/net/conversion/docx-to-csv/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: CSV
otherformats: TSV SXC XLTX XLS XLSX XLT XLTM DIF XLSB FODS EXCEL XLSM XLAM ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de C# para convertir DOCX a CSV" h2="Exporte DOCX a CSV a través de C# sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total para .NET](https://products.aspose.com/total/net/), puede incluir la función de conversión de DOCX a CSV dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET en dos sencillos pasos. En primer lugar, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede exportar DOCX a HTML. Después de eso, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API de programación de hojas de cálculo, puede convertir HTML a CSV.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir DOCX a CSV" %}}
1. Abra el archivo DOCX usando la clase [Documento](https://reference.aspose.com/words/net/aspose.words/document)
2. Convierta DOCX a HTML usando el método [Guardar](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Cargue el documento HTML utilizando la clase [Libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Guarde el documento en formato CSV usando el método [Guardar](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) y configure `CSV` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Cargar documento DOCX desde Stream a través de C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) también le permite cargar documentos DOCX a través de la transmisión. Para abrir un documento desde una secuencia, simplemente pase un objeto de secuencia que contenga el documento al constructor [Documento](https://reference.aspose.com/words/net/aspose.words/document). El siguiente ejemplo de código muestra cómo abrir un documento desde una secuencia:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Agregue propiedades personalizadas en un archivo CSV a través de C#" %}}
Al convertir DOCX a CSV, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) le permite agregar propiedades personalizadas en sus documentos CSV. Para agregar una propiedad personalizada, puede usar el método [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) para la [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) clase. El método Add agrega la propiedad al archivo de Excel y devuelve una referencia para la propiedad del nuevo documento como [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties /propiedaddocumento) objeto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-dif/" name="DOCX Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlsb/" name="DOCX Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-tsv/" name="DOCX Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-fods/" name="DOCX Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlt/" name="DOCX Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-excel/" name="DOCX Para EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlsx/" name="DOCX Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-ods/" name="DOCX Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-sxc/" name="DOCX Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlam/" name="DOCX Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xltm/" name="DOCX Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlsm/" name="DOCX Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xls/" name="DOCX Para XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xltx/" name="DOCX Para XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}