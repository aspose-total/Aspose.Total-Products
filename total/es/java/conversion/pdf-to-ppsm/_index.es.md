---
title: Conversión de PDF a PPSM en línea o desarrollo de una aplicación basada en Java para convertir archivos PDF
description: Aplicación gratuita en línea para convertir archivos PDF a PPSM. Código de biblioteca de conversión Java para documentos PDF. 

family: total
platformtag: Java
feature: conversion
informat: PDF
outformat: PPSM
otherformats: XAML OTP PPSM PPT POTM SWF POT PPSX POTX POWERPOINT PPTM PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aplicación de conversión de PDF a PPSM en línea y código Java para convertir archivos PDF" h2="Desarrollar una potente aplicación de conversión y exportación PDF basada en Java. Convierta archivos PDF individuales o múltiples a PPSM y otros formatos a través de la API de automatización de Java. Convierta libremente archivos PDF en línea a través de la aplicación con descarga instantánea." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Aplicación gratuita de conversión de PDF a PPSM en línea" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=ppsm&from=pdf" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierte archivos PDF a PPSM en línea usando la aplicación" %}}

1. Subir archivos PDF para convertir
1. Espere unos segundos o más según el tamaño de PDF
1. Esté atento a la barra de estado de carga
1. Haga clic en el botón "Convertir"
1. PDF se convertirá en un documento PPSM
1. Descargue el archivo PPSM convertido

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Convertir PDF a PPSM mediante la API de automatización de Java" %}}


1. Abra el archivo PDF usando la clase [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convierta PDF a PPTX usando el método [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Cargue el documento PPTX usando la clase [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Guarde el documento en formato PPSM usando el método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) y establezca ` Ppsm` como formato guardado



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código Java para la conversión de PDF a PPSM" offSpacer="" %}}
{{< gist "aspose-com-gists" "48b55393e52dd85032905dea500a496b" "convert-pdf-to-powerpoint.java" >}}
{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Algunos casos más para guardar PDF en PPSM con otras funciones como Requisitos de conversión, Abrir archivo PDF cifrado a través de Java.

{{% blocks/products/pf/feature-page-code %}}


```java
// open PDF document
Document doc = new Document("input.pdf", "Your@Password");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);    
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Desarrollar una aplicación de conversión de archivos PDF utilizando Java</h2>

¿Necesita desarrollar una aplicación de software basada en Java para guardar y exportar fácilmente archivos PDF a documentos PPSM? Con [Aspose.Total for Java](https://products.aspose.com/total/es/java/), cualquier desarrollador Java puede integrar el código API anterior para programar la aplicación de conversión en una variedad de formatos, incluidos Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, archivos de correo electrónico, imágenes (JPG, PNG, BMP, GIF) y otros formatos. Potente biblioteca Java para conversión de documentos, admite muchos formatos populares, incluido el formato PDF. Al exportar y renderizar documentos a otros formatos, los programadores pueden utilizar las API secundarias Aspose.Total for Java, incluidas [Aspose.Words for Java](https://products.aspose.com/words/es/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/es/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/es/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/es/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/es/java/) y más.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Biblioteca de conversión PDF para Java" %}}

Existen opciones alternativas para integrar Aspose.Total for Java en su sistema. Elija uno que se asemeje a sus necesidades y siga las instrucciones paso a paso:<br /><br />

- Utilice Aspose.Total for Java directamente desde un proyecto basado en Maven e incluya la API secundaria relevante en pom.xml.
- Alternativamente, se puede obtener un archivo ZIP de [Descargas](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de la aplicación para guardar PDF en PPSM" %}}

Cualquier sistema operativo que pueda ejecutar Java Runtime Environment (JRE) puede ejecutar Aspose.Total for Java. A continuación se enumeran la mayoría de los sistemas operativos compatibles, pero no todos. <br /><br />
- Microsoft Windows
- Linux: Ubuntu, OpenSUSE, CentOS y otros
- macOS: 10.9 (Mavericks) y posteriores
- Móvil: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}