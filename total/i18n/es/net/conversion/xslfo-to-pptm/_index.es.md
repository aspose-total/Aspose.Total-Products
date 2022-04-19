---
title: Exportar XSLFO a PPTM a través de la API de C#
description: .NET API para convertir XSLFO a PPTM sin usar Microsoft Word
url: /es/net/conversion/xslfo-to-pptm/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: PPTM
otherformats: PPSX SWF PPTM PPT XAML PPS PPSM POT OTP POTM POTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar XSLFO a PPTM a través de .NET" h2="API .NET para exportar XSLFO a PPTM en Windows, macOS y Linux sin usar Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Con un paquete de potentes API de automatización de formato de archivo [Aspose.Total para .NET] (https://products.aspose.com/total/net/), puede renderizar fácilmente XSLFO a PPTM en dos sencillos pasos. Mediante el uso de la API de procesamiento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede transformar el formato de archivo XSLFO a PPTX. Después de eso, al usar la API de procesamiento de presentaciones [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puede convertir PPTX a PPTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir XSLFO a PPTM" %}}
1. Abra el archivo XSLFO usando la clase [Documento](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta XSLFO a PPTX usando el método [Guardar](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el archivo PPTX usando la clase [Presentación](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Guarde el documento en formato PPTM usando el método [Guardar](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) y establezca `Pptm` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.xslfo");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.pptm", SaveFormat.Pptm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenga metadatos XMP del archivo XSLFO a través de .NET" %}}
Al convertir XSLFO a PPTM, es posible que necesite información de metadatos XMP adicional para priorizar su proceso de conversión por lotes. Por ejemplo, puede obtener y ordenar sus documentos de conversión según la fecha de creación y procesar los documentos en consecuencia. [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/) le permite acceder a los metadatos XMP de un archivo XSLFO. Para obtener los metadatos de un archivo XSLFO, puede crear un objeto [Documento](https://apireference.aspose.com/pdf/net/aspose.pdf/document) y abrir el archivo XSLFO de entrada. Después de eso, puede obtener los metadatos del archivo mediante la propiedad [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.xslfo");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crear archivo PPTM de solo lectura a través de .NET" %}}
Al utilizar la API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puede mejorar aún más las características de su aplicación de conversión. Una de las características puede ser crear su archivo de salida de solo lectura para aumentar la seguridad. La API le permite configurar su archivo PPTM en Solo lectura, lo que significa que los usuarios (después de abrir la presentación) ven la recomendación de Solo lectura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pptm", SaveFormat.Pptm);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-pot/" name="XSLFO Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-ppsx/" name="XSLFO Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-swf/" name="XSLFO Para SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-powerpoint/" name="XSLFO Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-otp/" name="XSLFO Para OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-potm/" name="XSLFO Para POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-ppt/" name="XSLFO Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-pps/" name="XSLFO Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-potx/" name="XSLFO Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-xaml/" name="XSLFO Para XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-ppsm/" name="XSLFO Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xslfo-to-pptm/" name="XSLFO Para PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}