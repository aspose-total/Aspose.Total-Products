---
title: API de C# para exportar correo electrónico a RTF
description: Convierta EMAIL a RTF sin usar Microsoft Word o Outlook en .NET
url_ignore: /es/net/conversion/email-to-rtf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: RTF
otherformats: PS TIFF EPUB SVG WORDML OTT PNG JPEG XPS GIF MD EMF ODT TEXT DOTX PCL FLATOPC DOTM DOCM DOCX RTF DOT DOC PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EMAIL a RTF a través de .NET" h2=".NET API para procesar EMAIL a RTF en Windows, macOS y Linux sin usar Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si es un desarrollador de .NET que busca agregar funciones de conversión de EMAIL a RTF dentro de sus aplicaciones, las API de manipulación de formato de archivo de [Aspose.Total for .NET](https://products.aspose.com/total/net/) son la solución. delantero. Al usar [Aspose.Email for .NET](https://products.aspose.com/email/net/), puede convertir el formato de archivo de EMAIL a HTML. Después de eso, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede convertir HTML a RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir correo electrónico a RTF" %}}
1. Abra el archivo EMAIL usando la clase [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convierta EMAIL a HTML utilizando el método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Guarde el documento en formato RTF usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Rtf como SaveFormat
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
Antes de convertir EMAIL a RTF, si desea asegurarse de que está convirtiendo el correo electrónico correcto, puede cargar el documento EMAIL, analizarlo y ver la propiedad deseada. Mediante el uso de la clase [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, puede obtener información sobre el remitente y los destinatarios. Por ejemplo, puede verificar el correo electrónico de un remitente específico para la conversión usando la propiedad [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de documentos RTF a través de .NET" %}}
Al guardar el documento de EMAIL a RTF, es posible que deba proteger su documento de salida. A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto puede ser útil para evitar que otras personas editen información sensible y confidencial en su documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, le permite controlar la forma en que restringe el contenido usando el [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parámetro de enumeración. Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a RTF mediante programación: casos de uso" %}}
**Conversión de Archivos de Correo a Formato de Texto Rico (RTF)**

Los archivos de correo se utilizan para almacenar contenido textual, lo que los hace ideales para crear mensajes simples y comunicaciones. Sin embargo, cuando se trata de formateado y diseño, los archivos RTF son esenciales para lograr presentaciones profesionales.

La conversión de archivos de correo a formatos RTF es necesaria para desbloquear la potencial visual de tu documento completa y capacidades de presentación. Esta conversión te permite:

**Uso Caso:**

*   **Correspondencia Profesional**: Convertir archivos de correo para crear letras, memorandos y comunicaciones formales visuales.
*   **Escribir Informes de Negocios**: Utilizar RTF para formatear informes, propuestas y presentaciones para clientes, socios o gestión.
*   **Materiales de Marketing**: Convertir archivos de correo para crear boletines de noticias, folletos y materiales de marketing atractivos.
*   **Bolsa de Trabajo**: Utilizar RTF para formatear informes, tesis y trabajos académicos con diseño y organización precisa.
*   **Documentación Técnica**: Convertir archivos de correo para crear guías de usuario, instrucciones y documentación técnica para productos o software.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}