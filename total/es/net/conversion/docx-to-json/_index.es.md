---
title: Convierta el formato DOCX a JSON a través de .NET
description: Convierta DOCX a JSON en C# sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/net/conversion/docx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCX
outformat: JSON
otherformats: FODS XLTX XLSM XLS XLT XLSB ODS CSV TSV XLTM EXCEL SXC XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el formato DOCX a JSON a través de C#" h2="Analice DOCX a JSON a través de C# sin usar Microsoft<sup>&reg;</sup> Word o Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Al usar [Aspose.Total for .NET](https://products.aspose.com/total/net/) puede convertir el formato DOCX a JSON dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET en dos pasos simples En primer lugar, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede exportar DOCX a HTML. Después de eso, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API de programación de hojas de cálculo, puede convertir HTML a JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato DOCX a JSON a través de C#" %}}
1. Abra el archivo DOCX usando la clase [Documento](https://reference.aspose.com/words/net/aspose.words/document)
2. Convierta DOCX a HTML usando el método [Guardar](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Cargue el documento HTML utilizando la clase [Libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Guarde el documento en formato JSON usando el método [Guardar](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta DOCX protegido a formato JSON a través de C#" %}}
Usando la API, también puede abrir el documento protegido por contraseña. Si su documento DOCX de entrada está protegido con contraseña, no puede convertirlo al formato JSON sin usar la contraseña. La API le permite abrir el documento cifrado pasando la contraseña correcta en un objeto LoadOptions. El siguiente ejemplo de código muestra cómo intentar abrir un documento cifrado con una contraseña:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta DOCX a JSON en el rango a través de C#" %}}
Mientras convierte DOCX a JSON, también puede establecer el rango en su formato JSON de salida. Para establecer el rango, puede abrir el HTML convertido usando la clase Workbook, obtener CellsCollection de la hoja de trabajo que contiene los datos, crear un rango de CellsCollection especificando índices de fila y columna, y llamar al método ExportRangeToJson con referencias a los objetos Range y ExportRangeToJsonOptions. Finalmente, puede guardar los datos JSON en un archivo a través del método File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-csv/" name="DOCX Para CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlam/" name="DOCX Para XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-sxc/" name="DOCX Para SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-tsv/" name="DOCX Para TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlt/" name="DOCX Para XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-excel/" name="DOCX Para EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-dif/" name="DOCX Para DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlsm/" name="DOCX Para XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xltm/" name="DOCX Para XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlsx/" name="DOCX Para XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xlsb/" name="DOCX Para XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-fods/" name="DOCX Para FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-ods/" name="DOCX Para ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/docx-to-xltx/" name="DOCX Para XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}