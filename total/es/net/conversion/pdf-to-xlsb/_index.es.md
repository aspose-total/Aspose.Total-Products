---
title: Convierta PDF a XLSB a través de la API de C#
description: API C# para convertir archivos PDF a XLSB sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/net/conversion/pdf-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: XLSB
otherformats: XLSB DIF XLTX MD SXC ODS XLT XLAM XLTM TXT XLSM EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de C# para renderizar PDF a XLSB" h2="Exporte el archivo PDF a XLSB a través de C# sin usar Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total para .NET](https://products.aspose.com/total/net/) puede convertir fácilmente un archivo PDF a XLSB dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET. En primer lugar, al usar [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede exportar PDF a XLSX. Después de eso, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API de programación de hojas de cálculo, puede convertir XLSX a XLSB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir PDF a XLSB" %}}
1. Abra el archivo PDF usando la clase [Documento](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta PDF a XLSX usando el método [Guardar](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el documento XLSX usando la clase [Libro de trabajo](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. Guarde el documento en formato XLSB usando el método [Guardar](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) y configure `Xlsb` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta PDF protegido a XLSB a través de C#" %}}
Si su documento PDF está protegido con contraseña, no puede convertirlo a XLSB sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia de la clase [Documento](https://apireference.aspose.com/pdf/net/aspose.pdf/document) y pasar el nombre del archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir archivo PDF a XLSB con marca de agua a través de C#" %}}
Al convertir un archivo PDF a XLSB, también puede agregar una marca de agua a su formato de archivo XLSB de salida. Para agregar una marca de agua, puede crear un nuevo objeto Libro de trabajo y abrir el documento XLSX convertido, seleccionar Hoja de trabajo a través de su índice, crear una Forma y usar su función AddTextEffect. Después de eso, puede guardar su documento XLSX como XLSB con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-sxc/" name="PDF Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-xltx/" name="PDF Para XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-md/" name="PDF Para MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-tsv/" name="PDF Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-txt/" name="PDF Para TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-ods/" name="PDF Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-xlt/" name="PDF Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-xlsm/" name="PDF Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-xlam/" name="PDF Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-xltm/" name="PDF Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-dif/" name="PDF Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pdf-to-xlsb/" name="PDF Para XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}