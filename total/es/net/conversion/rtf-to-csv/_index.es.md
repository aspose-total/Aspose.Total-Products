---
title: API .NET para convertir RTF a CSV
description: API de C# para convertir RTF a CSV sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/net/conversion/rtf-to-csv/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: CSV
otherformats: FODS XLSB XLTM XLS TSV XLAM DIF XLTX SXC XLT XLSM ODS XLSX EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de C# para convertir RTF a CSV" h2="Exporte RTF a CSV a través de C# sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Al utilizar [Aspose.Total para .NET](https://products.aspose.com/total/net/), puede incluir la función de conversión de RTF a CSV dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET en dos sencillos pasos. En primer lugar, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede exportar RTF a HTML. Después de eso, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API de programación de hojas de cálculo, puede convertir HTML a CSV.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir RTF a CSV" %}}
1. Abra el archivo RTF usando la clase [Documento](https://reference.aspose.com/words/net/aspose.words/Document)
2. Convierta RTF a HTML usando el método [Guardar](https://reference.aspose.com/words/net/aspose.words.Document/save/methods/4)
3. Cargue el Documento HTML utilizando la clase [Libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Guarde el Documento en formato CSV usando el método [Guardar](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) y configure `CSV` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Cargar Documento RTF desde Stream a través de C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) también le permite cargar Documentos RTF a través de la transmisión. Para abrir un Documento desde una secuencia, simplemente pase un objeto de secuencia que contenga el Documento al constructor [Documento](https://reference.aspose.com/words/net/aspose.words/Document). El siguiente ejemplo de código muestra cómo abrir un Documento desde una secuencia:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Agregue propiedades personalizadas en un archivo CSV a través de C#" %}}
Al convertir RTF a CSV, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) le permite agregar propiedades personalizadas en sus Documentos CSV. Para agregar una propiedad personalizada, puede usar el método [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection/methods/add/index) para la [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection) clase. El método Add agrega la propiedad al archivo de Excel y devuelve una referencia para la propiedad del nuevo Documento como [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties /propiedadDocumento) objeto. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-dif/" name="RTF Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xlsb/" name="RTF Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-tsv/" name="RTF Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-fods/" name="RTF Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xlt/" name="RTF Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-excel/" name="RTF Para EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xlsx/" name="RTF Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-ods/" name="RTF Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-sxc/" name="RTF Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xlam/" name="RTF Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xltm/" name="RTF Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xlsm/" name="RTF Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xls/" name="RTF Para XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/rtf-to-xltx/" name="RTF Para XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}