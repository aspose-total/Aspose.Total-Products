---
title: Convierta XSLFO a TSV a través de la API de C#
description: API C# para convertir archivos XSLFO a TSV sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/net/conversion/xslfo-to-tsv/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: TSV
otherformats: XLSM DIF XLSB SXC MD FODS XLAM XLT XLTX TSV ODS TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de C# para renderizar XSLFO a TSV" h2="Exporte el archivo XSLFO a TSV a través de C# sin usar Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total para .NET](https://products.aspose.com/total/net/) puede convertir fácilmente un archivo XSLFO a TSV dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET. En primer lugar, al usar [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede exportar XSLFO a XLSX. Después de eso, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API de programación de hojas de cálculo, puede convertir XLSX a TSV.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir XSLFO a TSV" %}}
1. Abra el archivo XSLFO usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta XSLFO a XLSX usando el método [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el documento XLSX usando la clase [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Guarde el documento en formato TSV usando el método [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) y configure `Tsv` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta XSLFO protegido a TSV a través de C#" %}}
Si su documento XSLFO está protegido con contraseña, no puede convertirlo a TSV sin la contraseña. Con la API, primero puede abrir el documento protegido con una contraseña válida y convertirlo después. Para abrir el archivo cifrado, puede inicializar una nueva instancia de la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) y pasar el nombre del archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir archivo XSLFO a TSV con marca de agua a través de C#" %}}
Al convertir un archivo XSLFO a TSV, también puede agregar una marca de agua a su formato de archivo TSV de salida. Para agregar una marca de agua, puede crear un nuevo objeto Libro de trabajo y abrir el documento XLSX convertido, seleccionar Hoja de trabajo a través de su índice, crear una Forma y usar su función AddTextEffect. Después de eso, puede guardar su documento XLSX como TSV con marca de agua. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}