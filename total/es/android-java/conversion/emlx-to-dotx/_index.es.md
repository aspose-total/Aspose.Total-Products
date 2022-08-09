---
title: Renderizar EMLX a DOTX en la aplicación Andorid
description: Exporte EMLX a DOTX sin usar Microsoft Word o Outlook en sus aplicaciones Andorid
url: /es/android-java/conversion/emlx-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: DOTX
otherformats: WORDML DOCM TEXT DOCX SVG DOTM EPUB EMF DOC MD BMP PCL TIFF FLATOPC RTF OTT PNG XPS ODT JPEG GIF DOT PDF PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transforma EMLX a DOTX en Andorid Apps" h2="Diseño de aplicaciones de Andorid para exportar EMLX a DOTX usando Andorid a través de la API de Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Las aplicaciones de Andorid son fáciles de usar para los usuarios finales a diario. Día a día, el número de usuarios de teléfonos Andorid está aumentando. Usando las potentes bibliotecas de automatización de formato de archivo [Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/), puede desarrollar aplicaciones de manipulación y conversión de correo electrónico. Puede convertir EMLX a DOTX mediante la combinación de [Aspose.Emlx for Android Java](https://products.aspose.com/emlx/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Con la primera API, puede convertir el formato de archivo de EMLX a HTML y, con la segunda API, puede representar HTML como DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir EMLX a DOTX en Andorid" %}}
1. Abra el archivo EMLX usando la clase [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. Convierta CORREO ELECTRÓNICO a HTML usando [guardar](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions )) método
3. Cargue HTML usando la clase [Documento](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Guarde el documento en formato DOTX utilizando [guardar](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) método y establecer DOTX como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.Emlx para Android a través de Java](https://docs.aspose.com/emlx/androidjava/installation/) y [Aspose.Words para Andorid a través de Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOTX
document.save("output.dotx", SaveFormat.DOTX); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-wordml/" name="EMLX A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-docm/" name="EMLX A DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-text/" name="EMLX A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-docx/" name="EMLX A DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-svg/" name="EMLX A SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-dotm/" name="EMLX A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-epub/" name="EMLX A EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-emf/" name="EMLX A EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-doc/" name="EMLX A DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-md/" name="EMLX A MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-dotx/" name="EMLX A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-pcl/" name="EMLX A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-tiff/" name="EMLX A TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-flatopc/" name="EMLX A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-rtf/" name="EMLX A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-ott/" name="EMLX A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-png/" name="EMLX A PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-xps/" name="EMLX A XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-odt/" name="EMLX A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-jpeg/" name="EMLX A JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-gif/" name="EMLX A GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-dot/" name="EMLX A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-pdf/" name="EMLX A PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/emlx-to-ps/" name="EMLX A PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}