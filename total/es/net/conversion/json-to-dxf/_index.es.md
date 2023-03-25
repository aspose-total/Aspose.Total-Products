---
title: Convierta el formato JSON a DXF a través de .NET
description: Analice JSON a DXF en C# sin usar dependencias de terceros
url_ignore: /es/net/conversion/json-to-dxf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DXF
otherformats: JPEG2000 WMZ DICOM SVGZ PSD WMF DXF EMZ IMAGE TGA
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el formato JSON a DXF a través de C#" h2="API C# para analizar JSON a DXF sin usar dependencias de terceros" >}}

{{% blocks/products/pf/feature-page-summary %}}
Al usar [Aspose.Total for .NET](https://products.aspose.com/total/net/) puede analizar JSON a DXF dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET en dos simples pasos. En primer lugar, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), puede exportar JSON a JPEG. Después de eso, usando [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), puede convertir JPEG a DXF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato JSON a DXF a través de C#" %}}
1. Cree un nuevo objeto [Libro de trabajo](https://reference.aspose.com/cells/net/aspose.cells/workbook) y lea los datos JSON del archivo.
2. Convierta JSON a JPEG utilizando el método [Guardar](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. Cargue el documento JPEG usando la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Guarde el documento en formato DXF usando el método [Guardar](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Establezca el diseño y convierta el formato JSON a DXF a través de C#" %}}
Mientras analiza JSON a DXF, también puede establecer opciones de diseño para su JSON mediante [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Le permite procesar Array como una tabla, ignorar nulos, ignorar el título de la matriz, ignorar el título del objeto, convertir cadenas en números o fechas, establecer el formato de fecha y número y establecer el estilo del título. Todas estas opciones le permiten presentar sus datos según sus necesidades. El siguiente fragmento de código le muestra cómo configurar las opciones de diseño.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Analizar formato JSON a DXF con marca de agua" %}}
Usando la API, también puede convertir JSON a DXF con marca de agua en su documento DXF. Para agregar una marca de agua, primero puede renderizar su documento JSON a JPEG y agregarle una marca de agua. Para demostrar la operación, puede cargar su imagen JPEG convertida, agregar transformaciones usando un objeto de la clase Matrix y dibujar una cadena como marca de agua en la superficie de la imagen usando [Gráficos](https://reference.aspose.com/imaging/ net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) método. Después de agregarle la marca de agua, puede guardar el JPEG como formato DXF. A continuación se muestra un ejemplo de código que demuestra cómo agregar una marca de agua diagonal a su documento. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}