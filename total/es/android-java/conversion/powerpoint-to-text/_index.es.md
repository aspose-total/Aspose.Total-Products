---
title: Exportar POWERPOINT a TEXT en Andorid a través de Java
description: Convierta POWERPOINT a TEXT en aplicaciones móviles sin instalar ningún software
url: /es/android-java/conversion/powerpoint-to-text/
family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: TEXT
otherformats: WORDML OTT DOT FLATOPC DOCM DOTX DOCX DOC ODT DOTM WORD RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar POWERPOINT a TEXT en Andorid a través de Java" h2="API de formato de archivo para convertir POWERPOINT a TEXT dentro de las aplicaciones de Android sin depender de Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/) permite manipular formatos de archivo dentro de las aplicaciones de Android. Al utilizar las API proporcionadas en el paquete, puede automatizar el proceso de conversión de PowerPoint POWERPOINT a Word TEXT en sus aplicaciones.
Puede convertir su textumento dado en dos pasos. Puede usar [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) que es una API de PowerPoint para aplicaciones de Android para convertir POWERPOINT en HTML. Después de eso, al usar la API de procesamiento de textumentos [Aspose.Words para Android a través de Java](https://products.aspose.com/words/android-java/), puede convertir el HTML a TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Representación de POWERPOINT a TEXT en Android" %}}
1. Abra el archivo POWERPOINT usando la clase [Presentación](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convierta POWERPOINT a HTML usando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) y establezca Html como SaveFormat
3. Cargue el archivo HTML convertido usando la clase [Textumento](https://reference.aspose.com/words/java/com.aspose.words/Textument)
4. Guarde el textumento en formato TEXT usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Textument#save(java.lang.String,int)) y configure Text como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.Slides para Android a través de Java](https://texts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) y [Aspose.Words para Andorid a través de Java](https://texts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en su aplicaciones

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Textument
Textument textument = new Textument("htmlOutput.html");
// save textument in TEXT format
textument.save("output.text",SaveFormat.Text);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-wordml/" name="PPTX A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-ott/" name="PPTX A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-dot/" name="PPTX A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-flatopc/" name="PPTX A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-textm/" name="PPTX A TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-dotx/" name="PPTX A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-textx/" name="PPTX A TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-text/" name="PPTX A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-odt/" name="PPTX A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-dotm/" name="PPTX A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-word/" name="PPTX A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptx-to-rtf/" name="PPTX A RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}