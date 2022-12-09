---
title: Convierta XML a FODS a través de la API de C#
description: API C# para convertir archivos XML a FODS sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/net/conversion/xml-to-fods/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: FODS
otherformats: FODS XLAM XLSM EXCEL TSV MD DIF XLT SXC XLTM XLSB TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de C# para renderizar XML a FODS" h2="Exporte el archivo XML a FODS a través de C# sin usar Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total para .NET](https://products.aspose.com/total/net/) puede convertir fácilmente un archivo XML a FODS dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET. En primer lugar, al usar [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede exportar XML a XLSX. Después de eso, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API de programación de hojas de cálculo, puede convertir XLSX a FODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir XML a FODS" %}}
1. Abra el archivo XML usando la clase [Documento](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta XML a XLSX usando el método [Guardar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el documento XLSX usando la clase [Libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Guarde el documento en formato FODS usando el método [Guardar](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) y configure `Fods` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta XML protegido a FODS a través de C#" %}}
Si su documento XML está protegido con contraseña, no puede convertirlo a FODS sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia de la clase [Documento](https://reference.aspose.com/pdf/net/aspose.pdf/document) y pasar el nombre del archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir archivo XML a FODS con marca de agua a través de C#" %}}
Al convertir un archivo XML a FODS, también puede agregar una marca de agua a su formato de archivo FODS de salida. Para agregar una marca de agua, puede crear un nuevo objeto Libro de trabajo y abrir el documento XLSX convertido, seleccionar Hoja de trabajo a través de su índice, crear una Forma y usar su función AddTextEffect. Después de eso, puede guardar su documento XLSX como FODS con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-sxc/" name="XML Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-xltx/" name="XML Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-md/" name="XML Para MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-tsv/" name="XML Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-txt/" name="XML Para TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-ods/" name="XML Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-xlt/" name="XML Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-xlsm/" name="XML Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-xlam/" name="XML Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-xltm/" name="XML Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-dif/" name="XML Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xml-to-xlsb/" name="XML Para XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}