---
title: Exportar PPSX a ODT en Andorid a través de Java
description: Convierta PPSX a ODT en aplicaciones móviles sin instalar ningún software

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: ODT
otherformats: DOTX WORD DOCM TEXT FLATOPC DOTM WORDML OTT DOCX RTF DOC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar PPSX a ODT en Andorid a través de Java" h2="API de formato de archivo para convertir PPSX a ODT dentro de las aplicaciones de Android sin depender de Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) permite manipular formatos de archivo dentro de las aplicaciones de Android. Al utilizar las API proporcionadas en el paquete, puede automatizar el proceso de conversión de PowerPoint PPSX a Word ODT en sus aplicaciones.
Puede convertir su odtumento dado en dos pasos. Puede usar [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) que es una API de PowerPoint para aplicaciones de Android para convertir PPSX en HTML. Después de eso, al usar la API de procesamiento de odtumentos [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), puede convertir el HTML a ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Representación de PPSX a ODT en Android" %}}
1. Abra el archivo PPSX usando la clase [Presentación](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convierta PPSX a HTML usando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) y establezca Html como SaveFormat
3. Cargue el archivo HTML convertido usando la clase [Odtumento](https://reference.aspose.com/words/java/com.aspose.words/Odtument)
4. Guarde el odtumento en formato ODT usando el método [save](https://reference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,int)) y configure Odt como Guardar formato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total for Android via Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.Slides for Android via Java](https://odts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) y [Aspose.Words para Andorid a través de Java](https://odts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en su aplicaciones

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("input.ppsx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Odtument
Odtument odtument = new Odtument("htmlOutput.html");
// save odtument in ODT format
odtument.save("output.odt",SaveFormat.Odt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-dotx/" name="PPSX A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-word/" name="PPSX A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-odtm/" name="PPSX A ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-text/" name="PPSX A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-flatopc/" name="PPSX A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-dotm/" name="PPSX A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-wordml/" name="PPSX A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-ott/" name="PPSX A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-odtx/" name="PPSX A ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-rtf/" name="PPSX A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-odt/" name="PPSX A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/ppsx-to-dot/" name="PPSX A DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}