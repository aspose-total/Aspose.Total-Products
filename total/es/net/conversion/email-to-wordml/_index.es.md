---
title: API de C# para exportar correo electrónico a WORDML
description: Convierta EMAIL a WORDML sin usar Microsoft Word o Outlook en .NET
url_ignore: /es/net/conversion/email-to-wordml/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORDML
otherformats: MD TIFF OTT DOCM EMF DOTM PNG SVG DOT TEXT DOTX DOCX PDF DOC WORDML GIF FLATOPC EPUB ODT JPEG XPS RTF PS PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EMAIL a WORDML a través de .NET" h2=".NET API para procesar EMAIL a WORDML en Windows, macOS y Linux sin usar Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si es un desarrollador de .NET que busca agregar funciones de conversión de EMAIL a WORDML dentro de sus aplicaciones, las API de manipulación de formato de archivo de [Aspose.Total for .NET](https://products.aspose.com/total/net/) son la solución. delantero. Al usar [Aspose.Email for .NET](https://products.aspose.com/email/net/), puede convertir el formato de archivo de EMAIL a HTML. Después de eso, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede convertir HTML a WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir correo electrónico a WORDML" %}}
1. Abra el archivo EMAIL usando la clase [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convierta EMAIL a HTML utilizando el método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Guarde el documento en formato WORDML usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Wordml como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo de correo electrónico a través de .NET" %}}
Antes de convertir EMAIL a WORDML, si desea asegurarse de que está convirtiendo el correo electrónico correcto, puede cargar el documento EMAIL, analizarlo y ver la propiedad deseada. Mediante el uso de la clase [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, puede obtener información sobre el remitente y los destinatarios. Por ejemplo, puede verificar el correo electrónico de un remitente específico para la conversión usando la propiedad [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de documentos WORDML a través de .NET" %}}
Al guardar el documento de EMAIL a WORDML, es posible que deba proteger su documento de salida. A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto puede ser útil para evitar que otras personas editen información sensible y confidencial en su documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, le permite controlar la forma en que restringe el contenido usando el [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parámetro de enumeración. Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a WORDML mediante programación: casos de uso" %}}
Los archivos de correo electrónico se utilizan para almacenar la información de comunicación basada en texto, lo que los hace ideales para enviar mensajes a destinatarios. Sin embargo, cuando se trabaja con datos de presentaciones, los archivos WordML (Lenguaje de marcado de Word) se vuelven esenciales para crear documentos y presentaciones profesionales.

La conversión de archivos de correo electrónico en formatos WordML es necesaria para desbloquear el potencial completo de tus capacidades de creación de documentación y presentación. Esta conversión te permite:

**Casos de uso:**

*   **Correspondencia empresarial**: Convierte archivos de correo electrónico para crear informes de negocios formales, propuestas y actas de reuniones.
*   **Diseño de presentaciones**: Usa WordML para diseñar presentaciones atractivas, agregar elementos multimedia y incluir características interactivas.
*   **Plantillas de documentos**: Convierte archivos de correo electrónico para crear plantillas reutilizables de documentación frecuentemente utilizada, como contratos y políticas.
*   **Colaboración en investigación**: Usa WordML para compartir hallazgos de la investigación, colaborar con colegas y seguir el progreso.
*   **Creación de contenido publicitario**: Convierte archivos de correo electrónico para crear materiales promocionales, publicaciones en redes sociales y artículos de blog.

Al convertir tus correos electrónicos a formato WordML, puedes desbloquear nuevas posibilidades para la creación de documentación, el diseño de presentaciones y la colaboración.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}