---
title: Exportar MD a SWF a través de la API de C#
description: .NET API para convertir MD a SWF sin usar Microsoft Word
url_ignore: /es/net/conversion/md-to-swf/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: SWF
otherformats: PPS PPSM PPSX OTP SWF POT PPTM POTX XAML POWERPOINT PPT POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar MD a SWF a través de .NET" h2="API .NET para exportar MD a SWF en Windows, macOS y Linux sin usar Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Con un paquete de potentes API de automatización de formato de archivo [Aspose.Total para .NET](https://products.aspose.com/total/net/), puede renderizar fácilmente MD a SWF en dos sencillos pasos. Mediante el uso de la API de procesamiento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede transformar el formato de archivo MD a PPTX. Después de eso, al usar la API de procesamiento de presentaciones [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puede convertir PPTX a SWF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir MD a SWF" %}}
1. Abra el archivo MD usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta MD a PPTX usando el método [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el archivo PPTX usando la clase [Presentación](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Guarde el documento en formato SWF usando el método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) y establezca `Swf` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenga metadatos XMP del archivo MD a través de .NET" %}}
Al convertir MD a SWF, es posible que necesite información de metadatos XMP adicional para priorizar su proceso de conversión por lotes. Por ejemplo, puede obtener y ordenar sus documentos de conversión según la fecha de creación y procesar los documentos en consecuencia. [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/) le permite acceder a los metadatos XMP de un archivo MD. Para obtener los metadatos de un archivo MD, puede crear un objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) y abrir el archivo MD de entrada. Después de eso, puede obtener los metadatos del archivo mediante la propiedad [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crear archivo SWF de solo lectura a través de .NET" %}}
Al utilizar la API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puede mejorar aún más las características de su aplicación de conversión. Una de las características puede ser crear su archivo de salida de solo lectura para aumentar la seguridad. La API le permite configurar su archivo SWF en Solo lectura, lo que significa que los usuarios (después de abrir la presentación) ven la recomendación de Solo lectura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.swf", SaveFormat.Swf);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos MD a SWF mediante programación: casos de uso" %}}
La conversión de archivos Markdown a formato SWF es necesaria para desbloquear las capacidades completas de tu capacidad presentacional.

Esta conversión permite que:

*   **Casos de Uso:**

  *   **Presentaciones Corporativas:** Convertir archivos Markdown para crear presentaciones enganchantes e interactivas, perfectas para eventos corporativos, reuniones y conferencias.
  *   **Creación de Contenido de Aprendizaje en Línea:** Utilizar el formato SWF para desarrollar módulos de aprendizaje inmersivos, simulaciones y tutoriales interactivos que mejoran la retención del conocimiento y el desarrollo de habilidades.
  *   **Desarrollo de Aplicaciones Móviles:** Convertir archivos Markdown en formato SWF para crear aplicaciones móviles con elementos interactivos, animaciones y contenido dinámico.
  *   **Juegos e Experiencias Interactivas:** Crear experiencias de juego y experiencias interactivas utilizando el formato SWF, permitiendo a los jugadores explorar entornos 2D y 3D de manera inmersiva de manera interactiva.
  *   **Publicación Digital y Revistas Digitales:** Convertir archivos Markdown en formato SWF para crear revistas digitales interactivas, cómics gráficos y novelas gráficas que se viven con animaciones, efectos sonoros y gráficos de movimiento.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}