---
title: Convierta el formato JSON a POTX a través de .NET
description: Analice JSON a POTX en C# sin usar Microsoft PowerPoint
url_ignore: /es/net/conversion/json-to-potx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POTX
otherformats: PPSX OTP POTM PPS POWERPOINT PPTM POTX PPT POT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el formato JSON a POTX a través de C#" h2="API C# para analizar JSON a POTX sin usar Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede convertir JSON a POTX dentro de cualquier aplicación .NET, C#, ASP.NET y VB.NET en dos sencillos pasos. En primer lugar, al usar [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), puede analizar JSON a PPTX. Después de eso, usando [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puede convertir PPTX a POTX. Ambas API se incluyen en el paquete [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato JSON a POTX a través de C#" %}}
1. Cree un nuevo objeto [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) y lea los datos JSON válidos del archivo.
2. Importe el archivo JSON a la hoja de trabajo usando la clase [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) y [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) como PPTX
3. Cargue el documento PPTX usando la clase [Presentación](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Guarde el documento en formato POTX usando el método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Establezca el diseño y convierta el formato JSON a POTX a través de C#" %}}
Mientras analiza JSON a POTX, también puede establecer opciones de diseño para su formato JSON mediante [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Le permite procesar una matriz como una tabla, ignorar nulos, ignorar el título de la matriz, ignorar el título del objeto, convertir una cadena en un número o fecha, establecer el formato de fecha y número y establecer el estilo del título. Todas estas opciones le permiten presentar sus datos según sus necesidades. El siguiente fragmento de código le muestra cómo configurar las opciones de diseño.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta el formato JSON a POTX con marca de agua" %}}
Usando la API, también puede convertir JSON a POTX con marca de agua. Para agregar una marca de agua a su documento POTX, primero puede analizar JSON a PPTX y agregarle una marca de agua. Para agregar una marca de agua, cargue el archivo PPTX recién creado usando la clase [Presentación](https://reference.aspose.com/slides/net/aspose.slides/presentation), seleccione la presentación maestra, agregue el tipo de forma usando AddAutoShape y agregue texto de marca de agua usando AddTextFrame. Después de agregar la marca de agua, puede guardar el documento en POTX. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}