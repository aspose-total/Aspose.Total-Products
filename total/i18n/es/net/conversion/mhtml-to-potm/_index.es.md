---
title: Exportar MHTML a POTM a través de la API de C#
description: .NET API para convertir MHTML a POTM sin usar Microsoft Word
url: /es/net/conversion/mhtml-to-potm/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: POTM
otherformats: SWF PPT POTM OTP PPS PPSX POT PPTM XAML POTX POWERPOINT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar MHTML a POTM a través de .NET" h2="API .NET para exportar MHTML a POTM en Windows, macOS y Linux sin usar Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Con un paquete de potentes API de automatización de formato de archivo [Aspose.Total para .NET] (https://products.aspose.com/total/net/), puede renderizar fácilmente MHTML a POTM en dos sencillos pasos. Mediante el uso de la API de procesamiento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede transformar el formato de archivo MHTML a PPTX. Después de eso, al usar la API de procesamiento de presentaciones [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puede convertir PPTX a POTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir MHTML a POTM" %}}
1. Abra el archivo MHTML usando la clase [Documento](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta MHTML a PPTX usando el método [Guardar](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el archivo PPTX usando la clase [Presentación](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. Guarde el documento en formato POTM usando el método [Guardar](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) y establezca `Potm` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.mhtml");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.potm", SaveFormat.Potm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenga metadatos XMP del archivo MHTML a través de .NET" %}}
Al convertir MHTML a POTM, es posible que necesite información de metadatos XMP adicional para priorizar su proceso de conversión por lotes. Por ejemplo, puede obtener y ordenar sus documentos de conversión según la fecha de creación y procesar los documentos en consecuencia. [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/) le permite acceder a los metadatos XMP de un archivo MHTML. Para obtener los metadatos de un archivo MHTML, puede crear un objeto [Documento](https://apireference.aspose.com/pdf/net/aspose.pdf/document) y abrir el archivo MHTML de entrada. Después de eso, puede obtener los metadatos del archivo mediante la propiedad [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.mhtml");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crear archivo POTM de solo lectura a través de .NET" %}}
Al utilizar la API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puede mejorar aún más las características de su aplicación de conversión. Una de las características puede ser crear su archivo de salida de solo lectura para aumentar la seguridad. La API le permite configurar su archivo POTM en Solo lectura, lo que significa que los usuarios (después de abrir la presentación) ven la recomendación de Solo lectura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potm", SaveFormat.Potm);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-pot/" name="MHTML Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-ppsx/" name="MHTML Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-swf/" name="MHTML Para SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-powerpoint/" name="MHTML Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-otp/" name="MHTML Para OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-potm/" name="MHTML Para POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-ppt/" name="MHTML Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-pps/" name="MHTML Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-potx/" name="MHTML Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-xaml/" name="MHTML Para XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-ppsm/" name="MHTML Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-pptm/" name="MHTML Para PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}