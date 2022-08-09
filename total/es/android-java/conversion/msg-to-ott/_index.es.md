---
title: Renderizar MSG a OTT en la aplicación Andorid
description: Exporte MSG a OTT sin usar Microsoft Word o Outlook en sus aplicaciones Andorid
url: /es/android-java/conversion/msg-to-ott/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: OTT
otherformats: SVG GIF DOCX PDF BMP TEXT PCL DOTX DOTM PS DOT FLATOPC MD RTF WORDML ODT JPEG PNG DOC XPS EMF TIFF EPUB DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transforma MSG a OTT en Andorid Apps" h2="Diseño de aplicaciones de Andorid para exportar MSG a OTT usando Andorid a través de la API de Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Las aplicaciones de Andorid son fáciles de usar para los usuarios finales a diario. Día a día, el número de usuarios de teléfonos Andorid está aumentando. Usando las potentes bibliotecas de automatización de formato de archivo [Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/), puede desarrollar aplicaciones de manipulación y conversión de correo electrónico. Puede convertir MSG a OTT mediante la combinación de [Aspose.Msg for Android Java](https://products.aspose.com/msg/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Con la primera API, puede convertir el formato de archivo de MSG a HTML y, con la segunda API, puede representar HTML como OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir MSG a OTT en Andorid" %}}
1. Abra el archivo MSG usando la clase [MailMessage](https://reference.aspose.com/msg/java/com.aspose.msg/mailmessage)
2. Convierta CORREO ELECTRÓNICO a HTML usando [guardar](https://reference.aspose.com/msg/java/com.aspose.msg/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions )) método
3. Cargue HTML usando la clase [Documento](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Guarde el documento en formato OTT utilizando [guardar](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) método y establecer OTT como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.Msg para Android a través de Java](https://docs.aspose.com/msg/androidjava/installation/) y [Aspose.Words para Andorid a través de Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.OTT
document.save("output.ott", SaveFormat.OTT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-svg/" name="MSG A SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-gif/" name="MSG A GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-docx/" name="MSG A DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-pdf/" name="MSG A PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-ott/" name="MSG A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-text/" name="MSG A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-pcl/" name="MSG A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-dotx/" name="MSG A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-dotm/" name="MSG A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-ps/" name="MSG A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-dot/" name="MSG A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-flatopc/" name="MSG A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-md/" name="MSG A MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-rtf/" name="MSG A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-wordml/" name="MSG A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-odt/" name="MSG A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-jpeg/" name="MSG A JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-png/" name="MSG A PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-doc/" name="MSG A DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-xps/" name="MSG A XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-emf/" name="MSG A EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-tiff/" name="MSG A TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-epub/" name="MSG A EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/msg-to-docm/" name="MSG A DOCM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}