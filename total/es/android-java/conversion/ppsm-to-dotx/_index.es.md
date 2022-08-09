---
title: Exportar PPSM a DOTX en Andorid a través de Java
description: Convierta PPSM a DOTX en aplicaciones móviles sin instalar ningún software
url: /es/android-java/conversion/ppsm-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: DOTX
otherformats: DOT FLATOPC DOCM DOTM DOC WORD TEXT DOCX ODT WORDML RTF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar PPSM a DOTX en Andorid a través de Java" h2="API de formato de archivo para convertir PPSM a DOTX dentro de las aplicaciones de Android sin depender de Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/) permite manipular formatos de archivo dentro de las aplicaciones de Android. Al utilizar las API proporcionadas en el paquete, puede automatizar el proceso de conversión de PowerPoint PPSM a Word DOTX en sus aplicaciones.
Puede convertir su dotxumento dado en dos pasos. Puede usar [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) que es una API de PowerPoint para aplicaciones de Android para convertir PPSM en HTML. Después de eso, al usar la API de procesamiento de dotxumentos [Aspose.Words para Android a través de Java](https://products.aspose.com/words/android-java/), puede convertir el HTML a DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Representación de PPSM a DOTX en Android" %}}
1. Abra el archivo PPSM usando la clase [Presentación](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convierta PPSM a HTML usando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) y establezca Html como SaveFormat
3. Cargue el archivo HTML convertido usando la clase [Dotxumento](https://reference.aspose.com/words/java/com.aspose.words/Dotxument)
4. Guarde el dotxumento en formato DOTX usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,int)) y configure Dotx como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.Slides para Android a través de Java](https://dotxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) y [Aspose.Words para Andorid a través de Java](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en su aplicaciones

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("input.ppsm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotxument
Dotxument dotxument = new Dotxument("htmlOutput.html");
// save dotxument in DOTX format
dotxument.save("output.dotx",SaveFormat.Dotx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-dot/" name="PPSM A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-flatopc/" name="PPSM A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-dotxm/" name="PPSM A DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-dotm/" name="PPSM A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-dotx/" name="PPSM A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-word/" name="PPSM A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-text/" name="PPSM A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-dotxx/" name="PPSM A DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-odt/" name="PPSM A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-wordml/" name="PPSM A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-rtf/" name="PPSM A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsm-to-ott/" name="PPSM A OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}