---
title: Convierta PCL a SVGZ a través de la API de C#
description: Exporte PCL a SVGZ en sus aplicaciones .NET sin usar ninguna aplicación de terceros
url_ignore: /es/net/conversion/pcl-to-svgz/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: SVGZ
otherformats: SVGZ  EMZ DXF TGA IMAGE JPEG2000 WMF WMZ PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el archivo PCL a SVGZ a través de C#" h2="Exporte PCL a SVGZ dentro de aplicaciones .NET sin utilizar Adobe<sup>&reg;</sup> Acrobat Reader ni ninguna otra aplicación de terceros" >}}

{{% blocks/products/pf/feature-page-summary %}}
Con [Aspose.Total para .NET](https://products.aspose.com/total/net/) puede exportar fácilmente una imagen PCL a SVGZ dentro de cualquier aplicación .NET en dos sencillos pasos. En primer lugar, al usar [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede exportar PCL a JPEG. Después de eso, al usar [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) API de procesamiento de imágenes, puede convertir JPEG a SVGZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el archivo PCL a SVGZ a través de .NET" %}}
1. Abra el archivo PCL usando la clase [Documento](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Inicialice el objeto de clase [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) y renderice PCL a JPEG mediante [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) método
3. Cargue el archivo JPEG usando la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Guarde el documento en formato SVGZ usando el método [Guardar](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta un archivo PCL a SVGZ en un solo archivo a través de C#" %}}
Con la API, también puede convertir un archivo PCL a SVGZ en un solo archivo de imagen. Para convertir todas las páginas, primero puede convertir su documento PCL en un archivo TIFF y luego puede exportar el archivo TIFF a SVGZ. Puede abrir el archivo de entrada usando la clase [Documento](https://reference.aspose.com/pdf/net/aspose.pdf/document) y crear objetos de dispositivo Resolución, TiffSettings y TIFF. Puede obtener una sola imagen TIFF usando el método [Proceso](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) de [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) clase. Finalmente, puede cargar el archivo TIFF usando la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image)
y guárdelo en formato SVGZ usando el método [Guardar](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir y rotar archivos PCL a SVGZ a través de C#" %}}
Usando la API, también puede rotar la imagen SVGZ de salida según sus necesidades. El método Image.RotateFlip se puede usar para rotar la imagen 90/180/270 grados y voltear la imagen horizontal o verticalmente. Puede especificar el tipo de rotación y volteo para aplicar a la imagen. Para rotar y voltear la imagen, puede cargar la imagen JPEG convertida utilizando el método de fábrica expuesto por la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image) y llamar a la clase Imagen .RotateFlip al especificar el [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pcl-to-emz/" name="PCL Para EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pcl-to-tga/" name="PCL Para TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pcl-to-jpeg2000/" name="PCL Para JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pcl-to-image/" name="PCL Para IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pcl-to-psd/" name="PCL Para PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pcl-to-wmz/" name="PCL Para WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pcl-to-svgz/" name="PCL Para SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pcl-to/" name="PCL Para" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pcl-to-wmf/" name="PCL Para WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pcl-to-dxf/" name="PCL Para DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/pcl-to-dicom/" name="PCL Para DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}