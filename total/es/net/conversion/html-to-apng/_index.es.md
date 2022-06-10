---
title: Convierta HTML a APNG a través de la API de C#
description: Exporte HTML a APNG en sus aplicaciones .NET sin usar ninguna aplicación de terceros
url_ignore: /es/net/conversion/html-to-apng/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: APNG
otherformats: IMAGE DXF SVGZ JPEG2000 EMZ PSD WMF WMZ  TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el archivo HTML a APNG a través de C#" h2="Exporte HTML a APNG dentro de aplicaciones .NET sin utilizar Adobe<sup>&reg;</sup> Acrobat Reader ni ninguna otra aplicación de terceros" >}}

{{% blocks/products/pf/feature-page-summary %}}
Con [Aspose.Total para .NET](https://products.aspose.com/total/net/) puede exportar fácilmente una imagen HTML a APNG dentro de cualquier aplicación .NET en dos sencillos pasos. En primer lugar, al usar [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede exportar HTML a JPEG. Después de eso, al usar [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) API de procesamiento de imágenes, puede convertir JPEG a APNG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el archivo HTML a APNG a través de .NET" %}}
1. Abra el archivo HTML usando la clase [Documento](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Inicialice el objeto de clase [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) y renderice HTML a JPEG mediante [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) método
3. Cargue el archivo JPEG usando la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Guarde el documento en formato APNG usando el método [Guardar](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta un archivo HTML a APNG en un solo archivo a través de C#" %}}
Con la API, también puede convertir un archivo HTML a APNG en un solo archivo de imagen. Para convertir todas las páginas, primero puede convertir su documento HTML en un archivo TIFF y luego puede exportar el archivo TIFF a APNG. Puede abrir el archivo de entrada usando la clase [Documento](https://reference.aspose.com/pdf/net/aspose.pdf/document) y crear objetos de dispositivo Resolución, TiffSettings y TIFF. Puede obtener una sola imagen TIFF usando el método [Proceso](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) de [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) clase. Finalmente, puede cargar el archivo TIFF usando la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image)
y guárdelo en formato APNG usando el método [Guardar](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir y rotar archivos HTML a APNG a través de C#" %}}
Usando la API, también puede rotar la imagen APNG de salida según sus necesidades. El método Image.RotateFlip se puede usar para rotar la imagen 90/180/270 grados y voltear la imagen horizontal o verticalmente. Puede especificar el tipo de rotación y volteo para aplicar a la imagen. Para rotar y voltear la imagen, puede cargar la imagen JPEG convertida utilizando el método de fábrica expuesto por la clase [Imagen](https://reference.aspose.com/imaging/net/aspose.imaging/image) y llamar a la clase Imagen .RotateFlip al especificar el [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/html-to-emz/" name="HTML Para EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/html-to-tga/" name="HTML Para TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/html-to-jpeg2000/" name="HTML Para JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/html-to-image/" name="HTML Para IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/html-to-psd/" name="HTML Para PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/html-to-wmz/" name="HTML Para WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/html-to-svgz/" name="HTML Para SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/html-to/" name="HTML Para" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/html-to-wmf/" name="HTML Para WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/html-to-dxf/" name="HTML Para DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/html-to-dicom/" name="HTML Para DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}