---
title: Exportar XML a POTX en Android
description: API de Android para convertir XML a POTX sin usar Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: POTX
otherformats: PPSM PPSX ODP XAML POT POTM OTP PPT PPS SWF POWERPOINT PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta XML a POTX en Android a través de Java" h2="Transforme XML a POTX dentro de sus aplicaciones de Android sin usar Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede integrar la función de conversión de XML a POTX dentro de sus aplicaciones de Android siguiendo dos simples pasos. En el primer paso, puede exportar XML a PPTX utilizando [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Después de eso, usando [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), puede convertir PPTX a POTX. Ambas API se incluyen en el paquete [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Android para exportar XML a POTX" %}}
1. Abra el archivo XML usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta XML a PPTX usando el método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Cargue el documento PPTX usando la clase [Presentación](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Guarde el documento en formato POTX usando el método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) y establezca ` Potx` como formato guardado
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total for Android via Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) y [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Abrir archivo XML protegido con contraseña en Android a través de Java" %}}
Al cargar el formato de archivo XML, su documento puede estar protegido con contraseña. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) también le permite abrir documentos cifrados. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Cree una imagen en miniatura del archivo POTX en aplicaciones de Android" %}}
Después de convertir XML a POTX, también puede crear imágenes en miniatura de su documento de salida. Mediante el uso de funciones ricas en [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) puede generar imágenes en miniatura de las diapositivas creando una instancia de la [Presentación](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) clase. Después de eso, puede obtener la referencia de cualquier diapositiva deseada utilizando su ID o índice y obtener la imagen en miniatura de la diapositiva a la que se hace referencia en una escala específica.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("output.potx");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-ppsm/" name="XML A PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-ppsx/" name="XML A PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-potx/" name="XML A POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-xaml/" name="XML A XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-pot/" name="XML A POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-potm/" name="XML A POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-otp/" name="XML A OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-ppt/" name="XML A PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-pps/" name="XML A PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-swf/" name="XML A SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-powerpoint/" name="XML A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/xml-to-pptm/" name="XML A PPTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}