---
title: Renderizar MSG a FLATOPC en la aplicación Andorid
description: Exporte MSG a FLATOPC sin usar Microsoft Word o Outlook en sus aplicaciones Andorid

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: FLAT_OPC
otherformats: DOC DOT TIFF EPUB PS EMF WORDML JPEG DOCM PDF OTT DOCX SVG PNG TEXT RTF GIF PCL XPS ODT DOTM MD BMP DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Transforma MSG a FLATOPC en Andorid Apps" h2="Diseño de aplicaciones de Andorid para exportar MSG a FLATOPC usando Andorid a través de la API de Java" >}}

{{% blocks/products/pf/feature-page-summary %}}
Las aplicaciones de Andorid son fáciles de usar para los usuarios finales a diario. Día a día, el número de usuarios de teléfonos Andorid está aumentando. Usando las potentes bibliotecas de automatización de formato de archivo [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), puede desarrollar aplicaciones de manipulación y conversión de correo electrónico. Puede convertir MSG a FLATOPC mediante la combinación de [Aspose.Msg for Android Java](https://products.aspose.com/msg/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Con la primera API, puede convertir el formato de archivo de MSG a HTML y, con la segunda API, puede representar HTML como FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir MSG a FLATOPC en Andorid" %}}
1. Abra el archivo MSG usando la clase [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Convierta CORREO ELECTRÓNICO a HTML usando [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions )) método
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Guarde el documento en formato FLATOPC utilizando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) método y establecer FLATOPC como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total for Android via Java directamente desde [Maven](https://releases.aspose.com/total/java/)s://docs.aspose.com/msg/androidjava/installation/) y [Aspose.Words para Andorid a través de Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) en sus aplicaciones.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.FLAT_OPC
document.save("output.flat_opc", SaveFormat.FLAT_OPC); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}