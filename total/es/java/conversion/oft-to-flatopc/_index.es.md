---
title: Exportar OFT a FLATOPC a través de Java
description: API de Java para convertir OFT a FLATOPC sin usar Microsoft Word o Outlook
url_ignore: /es/java/conversion/oft-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: FLAT_OPC
otherformats: TIFF MD PS SVG FLATOPC PDF DOCX PCL DOTM DOT WORDML OTT XPS TEXT DOCM DOTX EPUB DOC RTF EMF ODT PNG JPEG GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de Java para renderizar OFT a FLATOPC" h2="Exporte CORREO ELECTRÓNICO a FLATOPC mediante el uso de la API de Java en las instalaciones sin utilizar dependencias de terceros" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversión de correo electrónico es una característica poderosa que los desarrolladores de Java pueden integrar en cualquier aplicación Java J2SE, J2EE, J2ME a través de [Aspose.Total para Java](https://products.aspose.com/total/java/). Mediante el uso de dos API dentro del paquete, puede convertir correo electrónico OFT a FLATOPC sin dependencias de terceros. En primer lugar, puede utilizar la API de manipulación de correo electrónico [Aspose.Oft for Java](https://products.aspose.com/email/java/) para convertir el formato de archivo de correo electrónico a HTML. En segundo lugar, puede convertir HTML a FLATOPC mediante la API de procesamiento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir correo electrónico a FLATOPC" %}}
1. Abra el archivo OFT usando la clase [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Convierta CORREO ELECTRÓNICO a HTML usando [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) método
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Guarde el documento en formato FLATOPC utilizando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) método y establecer FLATOPC como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Debe usar Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}