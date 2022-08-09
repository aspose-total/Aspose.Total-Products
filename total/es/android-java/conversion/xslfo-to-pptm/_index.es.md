---
title: Exportar XSLFO a PPTM en Android
description: API de Android para convertir XSLFO a PPTM sin usar Microsoft Word
url: /es/android-java/conversion/xslfo-to-pptm/
family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPTM
otherformats: POT PPSX XAML PPS POTM ODP OTP POWERPOINT POTX PPT PPSM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta XSLFO a PPTM en Android a través de Java" h2="Transforme XSLFO a PPTM dentro de sus aplicaciones de Android sin usar Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede integrar la función de conversión de XSLFO a PPTM dentro de sus aplicaciones de Android siguiendo dos simples pasos. En el primer paso, puede exportar XSLFO a PPTX utilizando [Aspose.PDF para Android a través de Java](https://products.aspose.com/pdf/android-java/). Después de eso, usando [Aspose.Slides para Android a través de Java](https://products.aspose.com/slides/android-java/), puede convertir PPTX a PPTM. Ambas API se incluyen en el paquete [Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Android para exportar XSLFO a PPTM" %}}
1. Abra el archivo XSLFO usando la clase [Documento](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta XSLFO a PPTX usando el método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Cargue el documento PPTX usando la clase [Presentación](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Guarde el documento en formato PPTM usando el método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) y establezca ` Pptm` como formato guardado
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.PDF para Android a través de Java](https://docs.aspose.com/pdf/androidjava/installation/) y [Aspose.Slides para Android a través de Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Abrir archivo XSLFO protegido con contraseña en Android a través de Java" %}}
Al cargar el formato de archivo XSLFO, su documento puede estar protegido con contraseña. [Aspose.PDF para Android a través de Java](https://products.aspose.com/pdf/android-java/) también le permite abrir documentos cifrados. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Documento](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Cree una imagen en miniatura del archivo PPTM en aplicaciones de Android" %}}
Después de convertir XSLFO a PPTM, también puede crear imágenes en miniatura de su documento de salida. Mediante el uso de funciones ricas en [Aspose.Slides para Android a través de Java](https://products.aspose.com/slides/android-java/) puede generar imágenes en miniatura de las diapositivas creando una instancia de la [Presentación]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) clase. Después de eso, puede obtener la referencia de cualquier diapositiva deseada utilizando su ID o índice y obtener la imagen en miniatura de la diapositiva a la que se hace referencia en una escala específica.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("output.pptm");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-pot/" name="XSLFO A POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-ppsx/" name="XSLFO A PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-xaml/" name="XSLFO A XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-pps/" name="XSLFO A PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-potm/" name="XSLFO A POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-pptm/" name="XSLFO A PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-otp/" name="XSLFO A OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-powerpoint/" name="XSLFO A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-potx/" name="XSLFO A POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-ppt/" name="XSLFO A PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-ppsm/" name="XSLFO A PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xslfo-to-swf/" name="XSLFO A SWF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}