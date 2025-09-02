---
title: Exportar EML a MD a través de Java
description: API de Java para convertir EML a MD sin usar Microsoft Word o Outlook
url_ignore: /es/java/conversion/eml-to-md/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: MD
otherformats: MD ODT EMF JPEG PS XPS EPUB WORDML PCL FLATOPC OTT TEXT DOTM RTF DOCX GIF DOTX DOT DOCM PNG SVG PDF DOC TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API de Java para renderizar EML a MD" h2="Exporte CORREO ELECTRÓNICO a MD mediante el uso de la API de Java en las instalaciones sin utilizar dependencias de terceros" >}}
{{% blocks/products/pf/feature-page-summary %}}
La conversión de correo electrónico es una característica poderosa que los desarrolladores de Java pueden integrar en cualquier aplicación Java J2SE, J2EE, J2ME a través de [Aspose.Total para Java](https://products.aspose.com/total/java/). Mediante el uso de dos API dentro del paquete, puede convertir correo electrónico EML a MD sin dependencias de terceros. En primer lugar, puede utilizar la API de manipulación de correo electrónico [Aspose.Email for Java](https://products.aspose.com/email/java/) para convertir el formato de archivo de correo electrónico a HTML. En segundo lugar, puede convertir HTML a MD mediante la API de procesamiento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo convertir correo electrónico a MD" %}}
1. Abra el archivo EML usando la clase [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Convierta CORREO ELECTRÓNICO a HTML usando [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)) método
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Guarde el documento en formato MD utilizando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) método y establecer MD como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Debe usar Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/)

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-summary %}}
**Markdown (MD)** es un formato de texto ligero. Convertir **EML a MD** permite utilizar correos electrónicos en blogs, sitios web y sistemas de documentación.

## ✅ Casos de uso clave
- Publicar contenido de correo electrónico directamente en generadores de sitios estáticos (Hugo, Jekyll).
- Transformar correos de soporte en artículos de base de conocimientos.
- Migrar correspondencia a documentos colaborativos.

## ⚙️ Escenarios de automatización
- Exportar automáticamente correos de servicio al cliente a MD para documentos.
- Tuberías de gestión de contenido que reutilizan el contenido del correo electrónico.
- Convertir boletines en Markdown para blogs.
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}