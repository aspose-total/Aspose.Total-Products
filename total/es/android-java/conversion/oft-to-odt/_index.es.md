---
title: Renderizar OFT a ODT en la aplicación Andorid
description: Exporte OFT a ODT sin usar Microsoft Word o Outlook en sus aplicaciones Andorid
url: /es/android-java/conversion/oft-to-odt/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: ODT
otherformats: MD PS DOC PCL WORDML XPS JPEG EPUB RTF BMP DOCM OTT GIF DOTM SVG DOTX FLATOPC DOT PNG PDF TIFF DOCX EMF TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transforma OFT a ODT en Andorid Apps" h2="Diseño de aplicaciones de Andorid para exportar OFT a ODT usando Andorid a través de la API de Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Las aplicaciones de Andorid son fáciles de usar para los usuarios finales a diario. Día a día, el número de usuarios de teléfonos Andorid está aumentando. Usando las potentes bibliotecas de automatización de formato de archivo [Aspose.Total para Android a través de Java](https://products.aspose.com/total/android-java/), puede desarrollar aplicaciones de manipulación y conversión de correo electrónico. Puede convertir OFT a ODT mediante la combinación de [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Con la primera API, puede convertir el formato de archivo de OFT a HTML y, con la segunda API, puede representar HTML como ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir OFT a ODT en Andorid" %}}
1. Abra el archivo OFT usando la clase [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Convierta CORREO ELECTRÓNICO a HTML usando [guardar](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions )) método
3. Cargue HTML usando la clase [Documento](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Guarde el documento en formato ODT utilizando [guardar](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) método y establecer ODT como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Android a través de Java directamente desde [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) y instale [Aspose.Oft para Android a través de Java](https://docs.aspose.com/oft/androidjava/installation/) y [Aspose.Words para Andorid a través de Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.ODT
document.save("output.odt", SaveFormat.ODT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-md/" name="OFT A MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-ps/" name="OFT A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-doc/" name="OFT A DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-pcl/" name="OFT A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-wordml/" name="OFT A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-xps/" name="OFT A XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-jpeg/" name="OFT A JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-epub/" name="OFT A EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-rtf/" name="OFT A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-odt/" name="OFT A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-docm/" name="OFT A DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-ott/" name="OFT A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-gif/" name="OFT A GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-dotm/" name="OFT A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-svg/" name="OFT A SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-dotx/" name="OFT A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-flatopc/" name="OFT A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-dot/" name="OFT A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-png/" name="OFT A PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-pdf/" name="OFT A PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-tiff/" name="OFT A TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-docx/" name="OFT A DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-emf/" name="OFT A EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/android-java/conversion/oft-to-text/" name="OFT A TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}