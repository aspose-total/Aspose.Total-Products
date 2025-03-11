---
title: API de C# para exportar correo electrónico a TEXT
description: Convierta EML a TEXT sin usar Microsoft Word o Outlook en .NET
url_ignore: /es/net/conversion/eml-to-text/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: TEXT
otherformats: PNG DOT DOTM JPEG ODT MD XPS PS WORDML DOCX FLATOPC EPUB SVG TIFF DOTX RTF OTT DOCM DOC PDF PCL GIF TEXT EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EML a TEXT a través de .NET" h2=".NET API para procesar EML a TEXT en Windows, macOS y Linux sin usar Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si es un desarrollador de .NET que busca agregar funciones de conversión de EML a TEXT dentro de sus aplicaciones, las API de manipulación de formato de archivo de [Aspose.Total for .NET](https://products.aspose.com/total/net/) son la solución. delantero. Al usar [Aspose.Email for .NET](https://products.aspose.com/email/net/), puede convertir el formato de archivo de EML a HTML. Después de eso, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede convertir HTML a TEXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir correo electrónico a TEXT" %}}
1. Abra el archivo EML usando la clase [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Convierta EML a HTML utilizando el método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Guarde el documento en formato TEXT usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Text como SaveFormat
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
Antes de convertir EML a TEXT, si desea asegurarse de que está convirtiendo el correo electrónico correcto, puede cargar el documento EML, analizarlo y ver la propiedad deseada. Mediante el uso de la clase [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, puede obtener información sobre el remitente y los destinatarios. Por ejemplo, puede verificar el correo electrónico de un remitente específico para la conversión usando la propiedad [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de documentos TEXT a través de .NET" %}}
Al guardar el documento de EML a TEXT, es posible que deba proteger su documento de salida. A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto puede ser útil para evitar que otras personas editen información sensible y confidencial en su documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, le permite controlar la forma en que restringe el contenido usando el [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parámetro de enumeración. Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.text", SaveFormat.Text);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a TEXT mediante programación: casos de uso" %}}
Archivos de correo electrónico (EML) se utilizan para almacenar información de comunicación basada en texto, lo que los hace ideales para crear mensajes y correos electrónicos legibles. Sin embargo, al trabajar con contenido multimedia, documentos como PDFs se convierten en esenciales para compartir y visualizar.

La conversión de archivos EML a formatos de texto es necesaria para desbloquear el potencial completo de tu contenido de mensaje y sus capacidades de análisis. Esta conversión te permite:

**Usos:**

*   **Análisis de Mensajes**: Convierte archivos EML para analizar mensajes de correo electrónico, rastrear el comportamiento del remitente y identificar patrones en la comunicación.
*   **Marketing por Email Automatizado**: Usa formatos de texto para visualizar datos de marketing de correo electrónico, automatizar campañas y medir tasas de apertura.
*   **Documentación de Soporte al Cliente**: Convierte archivos EML para crear documentación legible, preguntas frecuentes y bases del conocimiento para los clientes, lo que mejora los servicios de soporte.
*   **Registro Histórico**: Usa formatos de texto para almacenar y recuperar registros de correos electrónicos históricos, garantizando la cumplimentación con las regulaciones y requisitos de registro.
*   **Reutilización del Contenido**: Convierte archivos EML para crear contenido reutilizable, como artículos de blog, actualizaciones de redes sociales y comunicados de prensa, lo que mejora el compromiso y la alcance.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}