---
title: Exportar POTM a WORD en Andorid a través de Java
description: Convierta POTM a WORD en aplicaciones móviles sin instalar ningún software

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: DOCX
otherformats: WORDML DOCM FLATOPC DOT TEXT ODT RTF DOTX DOC DOCX OTT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar POTM a WORD en Andorid a través de Java" h2="API de formato de archivo para convertir POTM a WORD dentro de las aplicaciones de Android sin depender de Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) permite manipular formatos de archivo dentro de las aplicaciones de Android. Al utilizar las API proporcionadas en el paquete, puede automatizar el proceso de conversión de PowerPoint POTM a Word WORD en sus aplicaciones.
Puede convertir su wordumento dado en dos pasos. Puede usar [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) que es una API de PowerPoint para aplicaciones de Android para convertir POTM en HTML. Después de eso, al usar la API de procesamiento de wordumentos [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), puede convertir el HTML a WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Representación de POTM a WORD en Android" %}}
1. Abra el archivo POTM usando la clase [Presentación](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convierta POTM a HTML usando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) y establezca Html como SaveFormat
3. Cargue el archivo HTML convertido usando la clase [Wordumento](https://reference.aspose.com/words/java/com.aspose.words/Wordument)
4. Guarde el wordumento en formato WORD usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,int)) y configure Word como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total for Android via Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.Slides for Android via Java](https://words.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) y [Aspose.Words para Andorid a través de Java](https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en su aplicaciones

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Wordument
Wordument wordument = new Wordument("htmlOutput.html");
// save wordument in WORDX format
wordument.save("output.wordx",SaveFormat.Wordx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-wordml/" name="POTM A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-wordm/" name="POTM A WORDM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-flatopc/" name="POTM A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-dot/" name="POTM A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-text/" name="POTM A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-odt/" name="POTM A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-rtf/" name="POTM A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-dotx/" name="POTM A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-word/" name="POTM A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-wordx/" name="POTM A WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-ott/" name="POTM A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/potm-to-dotm/" name="POTM A DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}