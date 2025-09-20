---
title: Convierta HTML a SVGZ a través de Java
description: Exporte el archivo HTML a SVGZ en sus aplicaciones Java sin usar ninguna aplicación de terceros
url_ignore: /es/java/conversion/html-to-svgz/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: SVGZ
otherformats: EMZ JPEG2000 PSD WMF TGA IMAGE WMZ DXF SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta HTML a SVGZ a través de Java" h2="Exporte un archivo HTML a SVGZ dentro de cualquier aplicación Java J2SE, J2EE, J2ME sin usar Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puede convertir un archivo html a una imagen SVGZ en Java en dos simples pasos. En primer lugar, al usar [Aspose.PDF para Java](https://products.aspose.com/pdf/java/), puede exportar HTML a JPEG. Después de eso, al usar [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) API de procesamiento de imágenes, puede convertir JPEG a SVGZ. Ambas API se incluyen en el paquete [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Exportar HTML a SVGZ a través de Java" %}}
1. Abra el archivo HTML usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inicialice el objeto de clase y renderice HTML a JPEG mediante [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com. método aspose.pdf.Page-java.io.OutputStream-)
3. Cargue el archivo JPEG usando la clase [Imagen](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Guarde el documento en formato SVGZ usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/)

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Convierta HTML a SVGZ en un solo archivo a través de Java" %}}
La API también le permite exportar archivos HTML a SVGZ a un solo archivo. Para convertir todas las páginas, primero puede convertir su documento HTML en un archivo TIFF y luego puede exportar el archivo TIFF a SVGZ. Puede abrir el archivo de entrada usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) y crear objetos de dispositivo Resolución, TiffSettings y TIFF. Puede obtener una sola imagen TIFF usando [proceso](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- método java.io.OutputStream-) de la clase [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Finalmente, puede cargar el archivo TIFF usando la clase [Imagen](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) y guardarlo en formato SVGZ usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta HTML a SVGZ con marca de agua a través de Java" %}}
Con la API, también puede exportar un archivo HTML a SVGZ con marca de agua en su documento SVGZ. Para agregarle una marca de agua, primero puede convertir HTML a JPEG y agregarle una marca de agua. Para agregar una marca de agua, cargue un archivo de imagen usando la clase [Imagen](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), cree un objeto de [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) e inicialícela con el objeto Image, cree una nueva [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) y configure la traducción y transformación al ángulo deseado y agregue una marca de agua usando [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# método drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Después de agregar la marca de agua en su imagen, puede guardar el JPEG como formato SVGZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir y rotar archivos HTML a SVGZ a través de Java" %}}
Usando la API, también puede rotar la imagen SVGZ de salida según sus necesidades. El método Image.rotateFlip se puede utilizar para rotar la imagen 90/180/270 grados y voltear la imagen horizontal o verticalmente. La biblioteca proporciona métodos simples para realizar operaciones complejas mientras encapsula todos los detalles desagradables. Puede especificar el tipo de rotación y volteo para aplicar a la imagen. Para rotar y voltear la imagen, puede cargar la imagen JPEG convertida usando la clase [Imagen](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) y llamar a la imagen. giratorio mientras especifica el [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
La conversión de **HTML a SVGZ (SVG comprimido)** es esencial para generar **gráficos vectoriales escalables y comprimidos** a partir de páginas web. SVGZ mantiene la claridad y escalabilidad de los gráficos vectoriales mientras reduce significativamente el tamaño de los archivos, lo que lo hace ideal para diseños responsivos, visuales listos para web y contenido digital interactivo. Al transformar el contenido HTML en SVGZ, las organizaciones pueden optimizar el rendimiento, mejorar los tiempos de carga y gestionar eficientemente los activos vectoriales en todas las plataformas.

{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}

* **Infografías** – Crear gráficos vectoriales visualmente nítidos y compactos para representación de datos.
* **Diagramas listos para web** – Generar diagramas escalables que se integren perfectamente en sitios web.
* **Publicación ligera** – Reducir el tamaño de los archivos para una entrega más rápida en publicaciones digitales.
* **Activos visuales aptos para dispositivos móviles** – Garantizar gráficos nítidos en cualquier resolución de pantalla o dispositivo.
* **Diseños interactivos** – Admitir animaciones e interactividad manteniendo tamaños de archivo pequeños.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}

* **Tuberías de HTML a SVGZ** – Automatizar la conversión de contenido web en gráficos vectoriales comprimidos.
* **Compresión de vectores automatizada** – Producir archivos SVGZ optimizados de manera consistente para uso web y móvil.
* **Flujos de trabajo de diagramas a granel** – Procesar eficientemente múltiples activos vectoriales para proyectos grandes.
* **Publicación ligera a nivel empresarial** – Integrar la generación de SVGZ en flujos de trabajo escalables de publicación digital.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}