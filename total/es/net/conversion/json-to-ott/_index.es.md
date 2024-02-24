---
title: Convierta el formato JSON a OTT a través de .NET
description: Analice JSON a OTT en C# sin usar Microsoft Word
url_ignore: /es/net/conversion/json-to-ott/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: OTT
otherformats: OTT DOT PS DOTX EPUB FLATOPC WORD RTF DOC PCL WORDML DOCM ODT MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el formato JSON a OTT a través de C#" h2="API C# para analizar JSON a OTT sin usar Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Al usar [Aspose.Total for .NET](https://products.aspose.com/total/net/) puede analizar JSON a OTT dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET en dos simples pasos. En primer lugar, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), puede exportar JSON a PDF. Después de eso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede convertir PDF a OTT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato JSON a OTT a través de C#" %}}
1. Cree un nuevo objeto [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) y lea los datos JSON válidos del archivo.
2. Importe el archivo JSON a la hoja de trabajo usando la clase [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) y [Save](https://reference.aspose.com/ cell/net/aspose.cells.workbook/save/methods/4) como PDF
3. Cargue el documento PDF usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Guarde el documento en formato OTT usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Establezca el diseño y convierta el formato JSON a OTT a través de C#" %}}
Mientras analiza JSON a OTT, también puede establecer opciones de diseño para su JSON mediante [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Le permite procesar Array como una tabla, ignorar nulos, ignorar el título de la matriz, ignorar el título del objeto, convertir cadenas en números o fechas, establecer el formato de fecha y número y establecer el estilo del título. Todas estas opciones le permiten presentar sus datos según sus necesidades. El siguiente fragmento de código le muestra cómo configurar las opciones de diseño.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analizar formato JSON a OTT con marca de agua" %}}
Usando la API, también puede convertir JSON a OTT con marca de agua. Para agregar una marca de agua a su documento OTT, primero puede analizar el archivo JSON en PDF y agregarle una marca de agua. Para agregar una marca de agua, cargue el archivo PDF recién creado usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document), cree una instancia de TextWatermarkOptions y establezca sus propiedades, Llame al método Watermark.SetText y pase el texto y el objeto de la marca de agua de TextWatermarkOptions. Después de agregar la marca de agua, puede guardar el documento en OTT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}