---
title: Exportar XPS a PPSX en Android
description: API de Android para convertir XPS a PPSX sin usar Microsoft Word
url: /es/android-java/conversion/xps-to-ppsx/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: PPSX
otherformats: ODP PPS SWF POWERPOINT PPSM PPTM POTX PPT OTP POTM XAML POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta XPS a PPSX en Android a través de Java" h2="Transforme XPS a PPSX dentro de sus aplicaciones de Android sin usar Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede integrar la función de conversión de XPS a PPSX dentro de sus aplicaciones de Android siguiendo dos simples pasos. En el primer paso, puede exportar XPS a PPTX utilizando [Aspose.PDF para Android a través de Java](https://products.aspose.com/pdf/android-java/). Después de eso, usando [Aspose.Slides para Android a través de Java](https://products.aspose.com/slides/android-java/), puede convertir PPTX a PPSX. Ambas API se incluyen en el paquete [Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Android para exportar XPS a PPSX" %}}
1. Abra el archivo XPS usando la clase [Documento](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta XPS a PPTX usando el método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Cargue el documento PPTX usando la clase [Presentación](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Guarde el documento en formato PPSX usando el método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) y establezca ` Ppsx` como formato guardado
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.PDF para Android a través de Java](https://docs.aspose.com/pdf/androidjava/installation/) y [Aspose.Slides para Android a través de Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Abrir archivo XPS protegido con contraseña en Android a través de Java" %}}
Al cargar el formato de archivo XPS, su documento puede estar protegido con contraseña. [Aspose.PDF para Android a través de Java](https://products.aspose.com/pdf/android-java/) también le permite abrir documentos cifrados. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Documento](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Cree una imagen en miniatura del archivo PPSX en aplicaciones de Android" %}}
Después de convertir XPS a PPSX, también puede crear imágenes en miniatura de su documento de salida. Mediante el uso de funciones ricas en [Aspose.Slides para Android a través de Java](https://products.aspose.com/slides/android-java/) puede generar imágenes en miniatura de las diapositivas creando una instancia de la [Presentación]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) clase. Después de eso, puede obtener la referencia de cualquier diapositiva deseada utilizando su ID o índice y obtener la imagen en miniatura de la diapositiva a la que se hace referencia en una escala específica.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("output.ppsx");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-ppsx/" name="XPS A PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-pps/" name="XPS A PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-swf/" name="XPS A SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-powerpoint/" name="XPS A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-ppsm/" name="XPS A PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-pptm/" name="XPS A PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-potx/" name="XPS A POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-ppt/" name="XPS A PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-otp/" name="XPS A OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-potm/" name="XPS A POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-xaml/" name="XPS A XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xps-to-pot/" name="XPS A POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}