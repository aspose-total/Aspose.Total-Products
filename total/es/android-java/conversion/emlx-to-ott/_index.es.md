---
title: Renderizar EMLX a OTT en la aplicación Andorid
description: Exporte EMLX a OTT sin usar Microsoft Word o Outlook en sus aplicaciones Andorid

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: OTT
otherformats: GIF MD EPUB BMP FLATOPC DOC EMF PNG SVG TEXT DOTX DOCX TIFF ODT WORDML JPEG PCL XPS PS DOCM PDF DOT RTF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transforma EMLX a OTT en Andorid Apps" h2="Diseño de aplicaciones de Andorid para exportar EMLX a OTT usando Andorid a través de la API de Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Las aplicaciones de Andorid son fáciles de usar para los usuarios finales a diario. Día a día, el número de usuarios de teléfonos Andorid está aumentando. Usando las potentes bibliotecas de automatización de formato de archivo [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), puede desarrollar aplicaciones de manipulación y conversión de correo electrónico. Puede convertir EMLX a OTT mediante la combinación de [Aspose.Emlx for Android Java](https://products.aspose.com/emlx/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Con la primera API, puede convertir el formato de archivo de EMLX a HTML y, con la segunda API, puede representar HTML como OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir EMLX a OTT en Andorid" %}}
1. Abra el archivo EMLX usando la clase [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. Convierta CORREO ELECTRÓNICO a HTML usando [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions )) método
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Guarde el documento en formato OTT utilizando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) método y establecer OTT como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total for Android via Java directamente desde [Maven](https://releases.aspose.com/total/java/)ps://docs.aspose.com/emlx/androidjava/installation/) y [Aspose.Words para Andorid a través de Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.OTT
document.save("output.ott", SaveFormat.OTT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}