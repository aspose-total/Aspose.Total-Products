---
title: Convierta XSLFO a TGA a través de Java
description: Exporte el archivo XSLFO a TGA en sus aplicaciones Java sin usar ninguna aplicación de terceros
url_ignore: /es/java/conversion/xslfo-to-tga/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: TGA
otherformats: DXF EMZ WMZ JPEG2000  TGA IMAGE PSD SVGZ WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta XSLFO a TGA a través de Java" h2="Exporte un archivo XSLFO a TGA dentro de cualquier aplicación Java J2SE, J2EE, J2ME sin usar Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puede convertir un archivo xslfo a una imagen TGA en Java en dos simples pasos. En primer lugar, al usar [Aspose.PDF para Java](https://products.aspose.com/pdf/java/), puede exportar XSLFO a JPEG. Después de eso, al usar [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) API de procesamiento de imágenes, puede convertir JPEG a TGA. Ambas API se incluyen en el paquete [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportar XSLFO a TGA a través de Java" %}}
1. Abra el archivo XSLFO usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inicialice el objeto de clase y renderice XSLFO a JPEG mediante [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. método aspose.pdf.Page-java.io.OutputStream-)
3. Cargue el archivo JPEG usando la clase [Imagen](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Guarde el documento en formato TGA usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/)

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Convierta XSLFO a TGA en un solo archivo a través de Java" %}}
La API también le permite exportar archivos XSLFO a TGA a un solo archivo. Para convertir todas las páginas, primero puede convertir su documento XSLFO en un archivo TIFF y luego puede exportar el archivo TIFF a TGA. Puede abrir el archivo de entrada usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) y crear objetos de dispositivo Resolución, TiffSettings y TIFF. Puede obtener una sola imagen TIFF usando [proceso](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- método java.io.OutputStream-) de la clase [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Finalmente, puede cargar el archivo TIFF usando la clase [Imagen](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) y guardarlo en formato TGA usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta XSLFO a TGA con marca de agua a través de Java" %}}
Con la API, también puede exportar un archivo XSLFO a TGA con marca de agua en su documento TGA. Para agregarle una marca de agua, primero puede convertir XSLFO a JPEG y agregarle una marca de agua. Para agregar una marca de agua, cargue un archivo de imagen usando la clase [Imagen](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), cree un objeto de [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) e inicialícela con el objeto Image, cree una nueva [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) y configure la traducción y transformación al ángulo deseado y agregue una marca de agua usando [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# método drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Después de agregar la marca de agua en su imagen, puede guardar el JPEG como formato TGA. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir y rotar archivos XSLFO a TGA a través de Java" %}}
Usando la API, también puede rotar la imagen TGA de salida según sus necesidades. El método Image.rotateFlip se puede utilizar para rotar la imagen 90/180/270 grados y voltear la imagen horizontal o verticalmente. La biblioteca proporciona métodos simples para realizar operaciones complejas mientras encapsula todos los detalles desagradables. Puede especificar el tipo de rotación y volteo para aplicar a la imagen. Para rotar y voltear la imagen, puede cargar la imagen JPEG convertida usando la clase [Imagen](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) y llamar a la imagen. giratorio mientras especifica el [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



La conversión de XSLFO a **TGA (Imagen Targa)** ofrece gráficos rasterizados de alta calidad que se utilizan frecuentemente en juegos, simulaciones y visualizaciones de alta resolución.



{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}



* Preparación de visuales generados por XSLFO para simulaciones o análisis de juegos.

* Archivo de gráficos detallados con pérdida mínima de compresión.

* Generación de gráficos rasterizados para publicaciones profesionales.

* Conversión de paneles operativos a TGA para flujos de trabajo de diseño.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}



* Conversión por lotes de XSLFO a TGA para informes de alta resolución.

* Exportación programada para flujos de visualización profesionales.

* Generación de TGA desencadenada a partir de análisis recurrentes de XSLFO.

* Integración con flujos de trabajo de diseño automatizados.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}