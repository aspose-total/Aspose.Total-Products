---
title: Convierta EPUB a PPSM a través de la API de Java
description: API de Java para convertir EPUB a PPSM sin usar Microsoft Word
url_ignore: /es/java/conversion/epub-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPSM
otherformats: POTM POT OTP PPS XAML PPSX POWERPOINT PPT PPSM POTX PPTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de Java para exportar EPUB a PPSM" h2="Exporte EPUB a PPSM a través de la API Java local sin usar Microsoft<sup>&reg;</sup> PowerPoint o Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for Java](https://products.aspose.com/total/java/) puede convertir fácilmente EPUB a PPSM dentro de cualquier aplicación Java J2SE, J2EE, J2ME. En primer lugar, al usar [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), puede exportar EPUB a PPTX. Después de eso, al usar [Aspose.Slides for Java](https://products.aspose.com/slides/java/) API de procesamiento de PowerPoint, puede convertir PPTX a PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de Java para convertir EPUB a PPSM" %}}
1. Abra el archivo EPUB usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta EPUB a PPTX usando el método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Cargue el documento PPTX usando la clase [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Guarde el documento en formato PPSM usando el método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) y establezca ` Ppsm` como formato guardado
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/)df/java/installation/) y [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Al cargar el formato de archivo EPUB, su documento puede estar protegido con contraseña. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) también le permite abrir documentos cifrados. Para abrir el archivo cifrado, puede inicializar una nueva instancia del [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) class y pase el nombre de archivo y la contraseña como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Abrir archivo EPUB cifrado a través de Java" %}}
Después de convertir EPUB a PPSM, también puede agregar un tipo de vista predefinido para su presentación. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) proporciona una función para establecer el tipo de vista para la presentación generada cuando se abre en PowerPoint a través de [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) clase. La propiedad [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) se usa para establecer el tipo de vista mediante [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerador. 
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
{{< blocks/products/pf/agp/feature-section >}}  
Convertir **EPUB a PPSM (Presentación de PowerPoint habilitada para macros)** es esencial para generar **archivos de presentación interactivos** a partir de libros electrónicos. Los archivos PPSM permiten que las presentaciones incluyan macros para automatización, interactividad y actualizaciones de contenido dinámico, lo que las hace ideales para aplicaciones educativas, corporativas y de publicación. Al transformar EPUB en PPSM, las organizaciones pueden ofrecer presentaciones inteligentes que mejoran la participación y optimizan los flujos de trabajo de presentación.  

{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}  
- **Presentaciones académicas automatizadas** – Generar diapositivas de conferencias con elementos interactivos preconfigurados.  
- **Material de capacitación con macros** – Crear presentaciones instructivas con navegación o cálculos automatizados.  
- **Automatización de presentaciones corporativas** – Estandarizar y automatizar los flujos de trabajo de presentaciones empresariales.  
- **Vistas previas de publicación** – Ofrecer vistas previas interactivas del contenido del libro electrónico a clientes o partes interesadas.  
- **Reproducción de presentaciones de investigación** – Producir diapositivas habilitadas para macros para presentaciones de investigación dinámicas.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}  
- **Flujos de trabajo de EPUB a PPSM** – Automatizar la conversión de libros electrónicos en archivos de presentación habilitados para macros.  
- **Creación de presentaciones habilitadas para macros** – Incrustar interactividad y automatización directamente en las diapositivas.  
- **Automatización basada en metadatos** – Poblar las presentaciones utilizando datos estructurados del libro electrónico.  
- **Flujos de trabajo de presentaciones empresariales** – Optimizar la producción y distribución a gran escala de diapositivas interactivas.  
{{% /blocks/products/pf/agp/feature-section-col %}}  

{{< /blocks/products/pf/agp/feature-section >}}  
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}