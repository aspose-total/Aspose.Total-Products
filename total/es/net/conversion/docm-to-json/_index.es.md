---
title: Convierta el formato DOCM a JSON a través de .NET
description: Convierta DOCM a JSON en C# sin usar Microsoft Excel o Adobe Reader
url_ignore: /es/net/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: ODS XLTM XLAM FODS DIF XLS XLSM TSV XLTX EXCEL XLSB SXC CSV XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el formato DOCM a JSON a través de C#" h2="Analice DOCM a JSON a través de C# sin usar Microsoft<sup>&reg;</sup> Word o Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Al usar [Aspose.Total for .NET](https://products.aspose.com/total/net/) puede convertir el formato DOCM a JSON dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET en dos pasos simples En primer lugar, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede exportar DOCM a HTML. Después de eso, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API de programación de hojas de cálculo, puede convertir HTML a JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato DOCM a JSON a través de C#" %}}
1. Abra el archivo DOCM usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document
2. Convierta DOCM a HTML usando el método [Save](https://reference.aspose.com/words/net/aspose.words.documentsave/methods/4)
3. Cargue el document HTML utilizando la clase [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Guarde el document en formato JSON usando el método [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta DOCM protegido a formato JSON a través de C#" %}}
Usando la API, también puede abrir el document protegido por contraseña. Si su ddocumentDOCM de entrada está protegido con contraseña, no puede convertirlo al formato JSON sin usar la contraseña. La API le permite abrir el dodocumentifrado pasando la contraseña correcta en un objeto LoadOptions. El siguiente ejemplo de código muestra cómo intentar abrir un docdocumentfrado con una contraseña:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta DOCM a JSON en el rango a través de C#" %}}
Mientras convierte DOCM a JSON, también puede establecer el rango en su formato JSON de salida. Para establecer el rango, puede abrir el HTML convertido usando la clase Workbook, obtener CellsCollection de la hoja de trabajo que contiene los datos, crear un rango de CellsCollection especificando índices de fila y columna, y llamar al método ExportRangeToJson con referencias a los objetos Range y ExportRangeToJsonOptions. Finalmente, puede guardar los datos JSON en un archivo a través del método File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}