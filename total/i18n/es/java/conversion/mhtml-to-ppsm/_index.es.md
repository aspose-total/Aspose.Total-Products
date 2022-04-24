---
title: Convierta MHTML a PPSM a través de la API de Java
description: API de Java para convertir MHTML a PPSM sin usar Microsoft Word
url: /es/java/conversion/mhtml-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: PPSM
otherformats: PPT POWERPOINT POTM OTP PPSM POTX PPSX PPS XAML POT PPTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de Java para exportar MHTML a PPSM" h2="Exporte MHTML a PPSM a través de la API Java local sin usar Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total para Java](https://products.aspose.com/total/java/) puede convertir fácilmente MHTML a PPSM dentro de cualquier aplicación Java J2SE, J2EE, J2ME. En primer lugar, al usar [Aspose.PDF para Java](https://products.aspose.com/pdf/java/), puede exportar MHTML a PPTX. Después de eso, al usar [Aspose.Slides for Java](https://products.aspose.com/slides/java/) API de procesamiento de PowerPoint, puede convertir PPTX a PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Java para convertir MHTML a PPSM" %}}
1. Abra el archivo MHTML usando la clase [Documento](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta MHTML a PPTX usando el método [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Cargue el documento PPTX usando la clase [Presentación](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Guarde el documento en formato PPSM usando el método [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) y establezca ` Ppsm` como formato guardado
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya [Aspose.PDF para Java](https://docs.aspose.com/pdf/java/installation/) y [Aspose.Slides para Java](https://docs.aspose.com/slides/java/ instalación/) en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Al cargar el formato de archivo MHTML, su documento puede estar protegido con contraseña. [Aspose.PDF para Java](https://products.aspose.com/pdf/java/) también le permite abrir documentos cifrados. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Documento] (https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java .lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open MHTML document
Document doc = new Document("input.mhtml", "Your@Password");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir archivo MHTML cifrado a través de Java" %}}
Después de convertir MHTML a PPSM, también puede agregar un tipo de vista predefinido para su presentación. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) proporciona una función para establecer el tipo de vista para la presentación generada cuando se abre en PowerPoint a través de [ViewProperties](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) clase. La propiedad [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) se usa para establecer el tipo de vista mediante [ViewType](https:/ /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerador. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-pps/" name="MHTML Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-swf/" name="MHTML Para SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-potx/" name="MHTML Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-ppsx/" name="MHTML Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-potm/" name="MHTML Para POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-ppt/" name="MHTML Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-ppsm/" name="MHTML Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-xaml/" name="MHTML Para XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-otp/" name="MHTML Para OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-pptm/" name="MHTML Para PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-pot/" name="MHTML Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/mhtml-to-powerpoint/" name="MHTML Para POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}