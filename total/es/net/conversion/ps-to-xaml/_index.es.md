---
title: Exportar PS a XAML a través de la API de C#
description: .NET API para convertir PS a XAML sin usar Microsoft Word
url_ignore: /es/net/conversion/ps-to-xaml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XAML
otherformats: XAML OTP POT SWF POTM PPSM POTX PPT PPSX PPS PPTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar PS a XAML a través de .NET" h2="API .NET para exportar PS a XAML en Windows, macOS y Linux sin usar Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Con un paquete de potentes API de automatización de formato de archivo [Aspose.Total para .NET](https://products.aspose.com/total/net/), puede renderizar fácilmente PS a XAML en dos sencillos pasos. Mediante el uso de la API de procesamiento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede transformar el formato de archivo PS a PPTX. Después de eso, al usar la API de procesamiento de presentaciones [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puede convertir PPTX a XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para convertir PS a XAML" %}}
1. Abra el archivo PS usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta PS a PPTX usando el método [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el archivo PPTX usando la clase [Presentación](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Guarde el documento en formato XAML usando el método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) y establezca `Xaml` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenga metadatos XMP del archivo PS a través de .NET" %}}
Al convertir PS a XAML, es posible que necesite información de metadatos XMP adicional para priorizar su proceso de conversión por lotes. Por ejemplo, puede obtener y ordenar sus documentos de conversión según la fecha de creación y procesar los documentos en consecuencia. [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/) le permite acceder a los metadatos XMP de un archivo PS. Para obtener los metadatos de un archivo PS, puede crear un objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) y abrir el archivo PS de entrada. Después de eso, puede obtener los metadatos del archivo mediante la propiedad [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crear archivo XAML de solo lectura a través de .NET" %}}
Al utilizar la API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puede mejorar aún más las características de su aplicación de conversión. Una de las características puede ser crear su archivo de salida de solo lectura para aumentar la seguridad. La API le permite configurar su archivo XAML en Solo lectura, lo que significa que los usuarios (después de abrir la presentación) ven la recomendación de Solo lectura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos PS a XAML mediante programación: casos de uso" %}}
Archivos de formato Portable Document (PS) se utilizan para almacenar información gráfica vectorial, lo que los hace ideales para crear gráficos estáticos, logotipos e ilustraciones. Sin embargo, cuando se trabaja con datos dinámicos, el lenguaje XAML (Lengua de Marcado Extensible de Aplicaciones) es esencial para construir interfaz de usuario y aplicaciones.

La conversión de archivos PS a formatos de XAML es necesaria para desbloquear las capacidades de desarrollo de aplicaciones totales. Esta conversión permite:

**Uso Caso:**

*   **Desarrollo de Aplicaciones Móviles**: Convertir archivos PS para crear aplicaciones móviles nativas con interfaces de usuario intuitivas, aprovechando el poder de XAML para una experiencia de usuario suave.
*   **Desarrollo de Aplicaciones de Pantalla Desplegable**: Utilizar XAML para construir aplicaciones de pantalla desplegable robustas y escalables, aprovechando las fortalezas del lenguaje en la unión de datos, animaciones y plantillas.
*   **Bibliotecas de Componentes de UI**: Convertir archivos PS para crear componentes de interfaz de usuario reutilizables, como botones, campos de texto e menús, utilizando XAML para diseño eficiente y mantenible.
*   **Gráficos 3D y Animación**: Utilizar XAML para traer gráficos 3D y animaciones a la vida en tus aplicaciones, combinando el poder de las gráficas vectoriales con la flexibilidad del lenguaje de marcado.
*   **Accesibilidad y Personalización**: Convertir archivos PS para crear elementos de interfaz UI accesibles e personalizables, asegurándote de que tus aplicaciones se adapten a las necesidades y preferencias de los usuarios.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}