---
title: Exportar MSG a WORDML a través de Java
description: API de Java para convertir MSG a WORDML sin usar Microsoft Word o Outlook
url_ignore: /es/java/conversion/msg-to-wordml/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORD_ML
otherformats: DOCX DOTM EMF PCL PS JPEG DOC EPUB OTT TIFF PDF TEXT DOT XPS DOTX GIF MD WORDML SVG FLATOPC DOCM PNG ODT RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de Java para renderizar MSG a WORDML" h2="Exporte CORREO ELECTRÓNICO a WORDML mediante el uso de la API de Java en las instalaciones sin utilizar dependencias de terceros" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversión de correo electrónico es una característica poderosa que los desarrolladores de Java pueden integrar en cualquier aplicación Java J2SE, J2EE, J2ME a través de [Aspose.Total para Java](https://products.aspose.com/total/java/). Mediante el uso de dos API dentro del paquete, puede convertir correo electrónico MSG a WORDML sin dependencias de terceros. En primer lugar, puede utilizar la API de manipulación de correo electrónico [Aspose.Email for Java](https://products.aspose.com/email/java/) para convertir el formato de archivo de correo electrónico a HTML. En segundo lugar, puede convertir HTML a WORDML mediante la API de procesamiento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir correo electrónico a WORDML" %}}
1. Abra el archivo MSG usando la clase [MailMessage](https://reference.aspose.com/msg/java/com.aspose.msg/mailmessage)
2. Convierta CORREO ELECTRÓNICO a HTML usando [guardar](https://reference.aspose.com/msg/java/com.aspose.msg/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions)) método
3. Cargue HTML usando la clase [Documento](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Guarde el documento en formato WORDML utilizando [guardar](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) método y establecer WORDML como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Debe usar Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.WORD_ML
document.save("output.word_ml", SaveFormat.WORD_ML);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-png/" name="MSG Para PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-doc/" name="MSG Para DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-ott/" name="MSG Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-odt/" name="MSG Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-wordml/" name="MSG Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-dotx/" name="MSG Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-svg/" name="MSG Para SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-docx/" name="MSG Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-epub/" name="MSG Para EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-text/" name="MSG Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-xps/" name="MSG Para XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-ps/" name="MSG Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-flatopc/" name="MSG Para FLAParaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-docm/" name="MSG Para DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-jpeg/" name="MSG Para JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-tiff/" name="MSG Para TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-dot/" name="MSG Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-emf/" name="MSG Para EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-rtf/" name="MSG Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-gif/" name="MSG Para GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-pcl/" name="MSG Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-dotm/" name="MSG Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-md/" name="MSG Para MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/msg-to-pdf/" name="MSG Para PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}