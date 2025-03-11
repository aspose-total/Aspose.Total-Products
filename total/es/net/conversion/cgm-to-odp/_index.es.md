---
title: Exportar CGM a ODP a través de la API de C#
description: .NET API para convertir CGM a ODP sin usar Microsoft Word
url_ignore: /es/net/conversion/cgm-to-odp/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODP
otherformats: POT PPSX SWF POWERPOINT OTP POTM PPT PPS POTX XAML PPSM PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar CGM a ODP a través de .NET" h2="API .NET para exportar CGM a ODP en Windows, macOS y Linux sin usar Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Con un paquete de potentes API de automatización de formato de archivo [Aspose.Total para .NET](https://products.aspose.com/total/net/), puede renderizar fácilmente CGM a ODP en dos sencillos pasos. Mediante el uso de la API de procesamiento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede transformar el formato de archivo CGM a PPTX. Después de eso, al usar la API de procesamiento de presentaciones [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puede convertir PPTX a ODP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir CGM a ODP" %}}
1. Abra el archivo CGM usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta CGM a PPTX usando el método [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el archivo PPTX usando la clase [Presentación](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Guarde el documento en formato ODP usando el método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) y establezca `Odp` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenga metadatos XMP del archivo CGM a través de .NET" %}}
Al convertir CGM a ODP, es posible que necesite información de metadatos XMP adicional para priorizar su proceso de conversión por lotes. Por ejemplo, puede obtener y ordenar sus documentos de conversión según la fecha de creación y procesar los documentos en consecuencia. [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/) le permite acceder a los metadatos XMP de un archivo CGM. Para obtener los metadatos de un archivo CGM, puede crear un objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) y abrir el archivo CGM de entrada. Después de eso, puede obtener los metadatos del archivo mediante la propiedad [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crear archivo ODP de solo lectura a través de .NET" %}}
Al utilizar la API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puede mejorar aún más las características de su aplicación de conversión. Una de las características puede ser crear su archivo de salida de solo lectura para aumentar la seguridad. La API le permite configurar su archivo ODP en Solo lectura, lo que significa que los usuarios (después de abrir la presentación) ven la recomendación de Solo lectura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.odp", SaveFormat.Odp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a ODP mediante programación: casos de uso" %}}
Los archivos de metafile de gráficos computarizados (CGM) se utilizan para almacenar información de gráficos vectoriales, lo que los hace ideales para crear gráficos estáticos e ilustraciones. Sin embargo, cuando trabajamos con datos dinámicos, formatos como Presentación Abierta Documental (ODP) se vuelven esenciales para presentaciones y visualizaciones.

La conversión de archivos CGM a formatos ODP es necesaria para desbloquear las capacidades completas de tu capacidad de presentación y visualización. Esta conversión te permite:

Uso de casos:

*   Diseño de presentaciones: Convierte archivos CGM para crear presentaciones interactivas, pósteres, y animaciones en formato ODP.
*   Renderizado de gráficos vectoriales: Usa ODP para renderizar gráficos vectoriales, diagramas e ilustraciones con control preciso sobre la formato y la disposición.
*   Presentaciones basadas en datos: Convierte archivos CGM para crear presentaciones basadas en datos, incluyendo gráficos, gráficas y infografías, en formato ODP.
*   Colaboración y compartir: Usa ODP para colaborar con otros en presentaciones, compartir diseños y rastrear cambios en tiempo real.
*   Publicación profesional: Convierte archivos CGM para crear publicaciones de alta calidad, carteles, y revistas profesionales en formato ODP.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}