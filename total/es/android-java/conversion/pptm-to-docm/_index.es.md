---
title: Exportar PPTM a DOCM en Andorid a través de Java
description: Convierta PPTM a DOCM en aplicaciones móviles sin instalar ningún software
url: /es/android-java/conversion/pptm-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: DOCM
otherformats: TEXT DOCX WORD DOTM RTF WORDML DOT DOTX OTT FLATOPC DOC ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar PPTM a DOCM en Andorid a través de Java" h2="API de formato de archivo para convertir PPTM a DOCM dentro de las aplicaciones de Android sin depender de Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/) permite manipular formatos de archivo dentro de las aplicaciones de Android. Al utilizar las API proporcionadas en el paquete, puede automatizar el proceso de conversión de PowerPoint PPTM a Word DOCM en sus aplicaciones.
Puede convertir su docmumento dado en dos pasos. Puede usar [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) que es una API de PowerPoint para aplicaciones de Android para convertir PPTM en HTML. Después de eso, al usar la API de procesamiento de docmumentos [Aspose.Words para Android a través de Java](https://products.aspose.com/words/android-java/), puede convertir el HTML a DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Representación de PPTM a DOCM en Android" %}}
1. Abra el archivo PPTM usando la clase [Presentación](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convierta PPTM a HTML usando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) y establezca Html como SaveFormat
3. Cargue el archivo HTML convertido usando la clase [Docmumento](https://reference.aspose.com/words/java/com.aspose.words/Docmument)
4. Guarde el docmumento en formato DOCM usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Docmument#save(java.lang.String,int)) y configure Docm como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.Slides para Android a través de Java](https://docms.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) y [Aspose.Words para Andorid a través de Java](https://docms.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en su aplicaciones

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("input.pptm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Docmument
Docmument docmument = new Docmument("htmlOutput.html");
// save docmument in DOCM format
docmument.save("output.docm",SaveFormat.Docmm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-text/" name="PPTM A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-docmx/" name="PPTM A DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-word/" name="PPTM A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-dotm/" name="PPTM A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-rtf/" name="PPTM A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-wordml/" name="PPTM A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-dot/" name="PPTM A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-dotx/" name="PPTM A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-ott/" name="PPTM A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-flatopc/" name="PPTM A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-docm/" name="PPTM A DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/pptm-to-odt/" name="PPTM A ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}