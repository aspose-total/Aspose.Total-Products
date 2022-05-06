---
title: Convierta EPUB a APNG a través de Java
description: Exporte el archivo EPUB a APNG en sus aplicaciones Java sin usar ninguna aplicación de terceros
url_ignore: /es/java/conversion/epub-to-apng/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: APNG
otherformats: DXF  PSD SVGZ EMZ JPEG2000 TGA WMZ WMF IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta EPUB a APNG a través de Java" h2="Exporte un archivo EPUB a APNG dentro de cualquier aplicación Java J2SE, J2EE, J2ME sin usar Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puede convertir un archivo epub a una imagen APNG en Java en dos simples pasos. En primer lugar, al usar [Aspose.PDF para Java](https://products.aspose.com/pdf/java/), puede exportar EPUB a JPEG. Después de eso, al usar [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) API de procesamiento de imágenes, puede convertir JPEG a APNG. Ambas API se incluyen en el paquete [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportar EPUB a APNG a través de Java" %}}
1. Abra el archivo EPUB usando la clase [Documento](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inicialice el objeto de clase y renderice EPUB a JPEG mediante [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. método aspose.pdf.Page-java.io.OutputStream-)
3. Cargue el archivo JPEG usando la clase [Imagen](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Guarde el documento en formato APNG usando [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Convierta EPUB a APNG en un solo archivo a través de Java" %}}
La API también le permite exportar archivos EPUB a APNG a un solo archivo. Para convertir todas las páginas, primero puede convertir su documento EPUB en un archivo TIFF y luego puede exportar el archivo TIFF a APNG. Puede abrir el archivo de entrada usando la clase [Documento](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) y crear objetos de dispositivo Resolución, TiffSettings y TIFF. Puede obtener una sola imagen TIFF usando [proceso](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- método java.io.OutputStream-) de la clase [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Finalmente, puede cargar el archivo TIFF usando la clase [Imagen](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) y guardarlo en formato APNG usando [guardar](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta EPUB a APNG con marca de agua a través de Java" %}}
Con la API, también puede exportar un archivo EPUB a APNG con marca de agua en su documento APNG. Para agregarle una marca de agua, primero puede convertir EPUB a JPEG y agregarle una marca de agua. Para agregar una marca de agua, cargue un archivo de imagen usando la clase [Imagen](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), cree un objeto de [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) e inicialícela con el objeto Image, cree una nueva [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) y configure la traducción y transformación al ángulo deseado y agregue una marca de agua usando [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics# método drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Después de agregar la marca de agua en su imagen, puede guardar el JPEG como formato APNG. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir y rotar archivos EPUB a APNG a través de Java" %}}
Usando la API, también puede rotar la imagen APNG de salida según sus necesidades. El método Image.rotateFlip se puede utilizar para rotar la imagen 90/180/270 grados y voltear la imagen horizontal o verticalmente. La biblioteca proporciona métodos simples para realizar operaciones complejas mientras encapsula todos los detalles desagradables. Puede especificar el tipo de rotación y volteo para aplicar a la imagen. Para rotar y voltear la imagen, puede cargar la imagen JPEG convertida usando la clase [Imagen](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) y llamar a la imagen. giratorio mientras especifica el [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/epub-to-emz/" name="EPUB Para EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/epub-to-tga/" name="EPUB Para TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/epub-to-jpeg2000/" name="EPUB Para JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/epub-to-image/" name="EPUB Para IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/epub-to-psd/" name="EPUB Para PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/epub-to-wmz/" name="EPUB Para WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/epub-to-svgz/" name="EPUB Para SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/epub-to/" name="EPUB Para" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/epub-to-wmf/" name="EPUB Para WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/epub-to-dxf/" name="EPUB Para DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/epub-to-dicom/" name="EPUB Para DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}