---
title: Convierta CGM a TGA a través de la API de C#
description: Exporte CGM a TGA en sus aplicaciones .NET sin usar ninguna aplicación de terceros
url_ignore: /es/net/conversion/cgm-to-tga/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TGA
otherformats: EMZ TGA SVGZ IMAGE WMF  JPEG2000 WMZ DXF PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el archivo CGM a TGA a través de C#" h2="Exporte CGM a TGA dentro de aplicaciones .NET sin utilizar Adobe<sup>&reg;</sup> Acrobat Reader ni ninguna otra aplicación de terceros" >}}

{{% blocks/products/pf/feature-page-summary %}}
Con [Aspose.Total para .NET](https://products.aspose.com/total/net/) puede exportar fácilmente una imagen CGM a TGA dentro de cualquier aplicación .NET en dos sencillos pasos. En primer lugar, al usar [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede exportar CGM a JPEG. Después de eso, al usar [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) API de procesamiento de imágenes, puede convertir JPEG a TGA.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el archivo CGM a TGA a través de .NET" %}}
1. Abra el archivo CGM usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Inicialice el objeto de clase [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) y renderice CGM a JPEG mediante [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) método
3. Cargue el archivo JPEG usando la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Guarde el documento en formato TGA usando el método [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta un archivo CGM a TGA en un solo archivo a través de C#" %}}
Con la API, también puede convertir un archivo CGM a TGA en un solo archivo de imagen. Para convertir todas las páginas, primero puede convertir su documento CGM en un archivo TIFF y luego puede exportar el archivo TIFF a TGA. Puede abrir el archivo de entrada usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) y crear objetos de dispositivo Resolución, TiffSettings y TIFF. Puede obtener una sola imagen TIFF usando el método [Proceso](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) de [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) clase. Finalmente, puede cargar el archivo TIFF usando la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image)
y guárdelo en formato TGA usando el método [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir y rotar archivos CGM a TGA a través de C#" %}}
Usando la API, también puede rotar la imagen TGA de salida según sus necesidades. El método Image.RotateFlip se puede usar para rotar la imagen 90/180/270 grados y voltear la imagen horizontal o verticalmente. Puede especificar el tipo de rotación y volteo para aplicar a la imagen. Para rotar y voltear la imagen, puede cargar la imagen JPEG convertida utilizando el método de fábrica expuesto por la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image) y llamar a la clase Imagen .RotateFlip al especificar el [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a TGA mediante programación: casos de uso" %}}
La conversión de archivos CGM (Archivo Metafile de Graficas Computarizadas) a formatos TGA (Imagen de Imagen Verdadera del Fondo de Verdad) abre un mundo de posibilidades creativas, convirtiéndolos en una herramienta ideal para diversas aplicaciones. Sin embargo, al trabajar con contenido dinámico, los editores de imágenes como GIMP se convierten en esenciales para la edición y manipulación.

La conversión de archivos CGM a formatos TGA es necesaria para desbloquear el máximo potencial de tus capacidades de edición. Esta conversión te permite:

**Uso de Casos:**

*   **Edición de Imágenes**: Convierte archivos CGM para editar imágenes, ajustar la luminosidad, contraste y niveles de saturación.
*   **Diseño Gráfico**: Utiliza TGA para crear y manipular gráficos, logotipos, iconos y otros elementos visuales.
*   **Pintura Digital**: Convierte archivos CGM para pintura digital, creando arte vibrante con una amplia gama de colores y efectos.
*   **Visualización Arquitectónica**: Utiliza TGA para visualizar modelos 3D, creando imágenes fotorealistas para arquitectos, diseñadores y constructores.
*   **Análisis de Imágenes Médicas**: Convierte archivos CGM a análisis de imágenes médicas, examinando imágenes detalladas de órganos, tejidos y células.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}