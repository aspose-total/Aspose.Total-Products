---
title: Convierta CGM a DXF a través de la API de C#
description: Exporte CGM a DXF en sus aplicaciones .NET sin usar ninguna aplicación de terceros
url_ignore: /es/net/conversion/cgm-to-dxf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DXF
otherformats: WMF PSD DXF  JPEG2000 SVGZ EMZ WMZ IMAGE TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el archivo CGM a DXF a través de C#" h2="Exporte CGM a DXF dentro de aplicaciones .NET sin utilizar Adobe<sup>&reg;</sup> Acrobat Reader ni ninguna otra aplicación de terceros" >}}

{{% blocks/products/pf/feature-page-summary %}}
Con [Aspose.Total para .NET](https://products.aspose.com/total/net/) puede exportar fácilmente una imagen CGM a DXF dentro de cualquier aplicación .NET en dos sencillos pasos. En primer lugar, al usar [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede exportar CGM a JPEG. Después de eso, al usar [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) API de procesamiento de imágenes, puede convertir JPEG a DXF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el archivo CGM a DXF a través de .NET" %}}
1. Abra el archivo CGM usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Inicialice el objeto de clase [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) y renderice CGM a JPEG mediante [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) método
3. Cargue el archivo JPEG usando la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Guarde el documento en formato DXF usando el método [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta un archivo CGM a DXF en un solo archivo a través de C#" %}}
Con la API, también puede convertir un archivo CGM a DXF en un solo archivo de imagen. Para convertir todas las páginas, primero puede convertir su documento CGM en un archivo TIFF y luego puede exportar el archivo TIFF a DXF. Puede abrir el archivo de entrada usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) y crear objetos de dispositivo Resolución, TiffSettings y TIFF. Puede obtener una sola imagen TIFF usando el método [Proceso](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) de [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) clase. Finalmente, puede cargar el archivo TIFF usando la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image)
y guárdelo en formato DXF usando el método [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir y rotar archivos CGM a DXF a través de C#" %}}
Usando la API, también puede rotar la imagen DXF de salida según sus necesidades. El método Image.RotateFlip se puede usar para rotar la imagen 90/180/270 grados y voltear la imagen horizontal o verticalmente. Puede especificar el tipo de rotación y volteo para aplicar a la imagen. Para rotar y voltear la imagen, puede cargar la imagen JPEG convertida utilizando el método de fábrica expuesto por la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image) y llamar a la clase Imagen .RotateFlip al especificar el [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a DXF mediante programación: casos de uso" %}}
La conversión de archivos CGM (Arquitectura de Metafile de Gráficos Computacionales) a archivos DXF (Formato de Interambio de Bases de Dibujos) es fundamental para desbloquear las capacidades plenas de su diseño de CAD y sus posibilidades de fabricación. Esta conversión permite utilizar:

**Casos de Uso:**

*   **Integración con Software de Diseño en 3D**: Convertir archivos CGM para integrarse con software de diseño en 3D, lo que facilita la colaboración de diseño y el intercambio de datos.
*   **Optimización del Proceso de Fabricación**: Utilizar archivos DXF para optimizar los procesos de fabricación, reducir costos de producción y mejorar la calidad de los productos.
*   **Diseño para Fabricabilidad (DFM)**: Convertir archivos CGM para crear diseños DFM, teniendo en cuenta factores como las propiedades del material, los requisitos de herramienta y las limitaciones de ensamblado.
*   **Comunicación de Datos con Máquinas CNC**: Utilizar archivos DXF para comunicar datos de diseño con máquinas CNC, asegurando una precisión en el corte y la fabricación de piezas.
*   **Desarrollo de Productos e Pruebas**: Convertir archivos CGM para crear prototipos, probar diseños y validar la funcionalidad de los productos antes de su producción.

Nota: He utilizado el mismo patrón que se describió para convertir formato de fuente :CGM a formato objetivo:Dxf.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}