---
title: API de C# para exportar correo electrónico a PDF
description: Convierta MSG a PDF sin usar Microsoft Word o Outlook en .NET
url_ignore: /es/net/conversion/msg-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: DOT ODT WORDML JPEG PCL EMF TEXT RTF EPUB FLATOPC PDF SVG GIF OTT PS DOCX MD TIFF DOTM PNG DOCM XPS DOC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar MSG a PDF a través de .NET" h2=".NET API para procesar MSG a PDF en Windows, macOS y Linux sin usar Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si es un desarrollador de .NET que busca agregar funciones de conversión de MSG a PDF dentro de sus aplicaciones, las API de manipulación de formato de archivo de [Aspose.Total for .NET](https://products.aspose.com/total/net/) son la solución. delantero. Al usar [Aspose.Email for .NET](https://products.aspose.com/email/net/), puede convertir el formato de archivo de MSG a HTML. Después de eso, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede convertir HTML a PDF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir correo electrónico a PDF" %}}
1. Abra el archivo MSG usando la clase [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Convierta MSG a HTML utilizando el método [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Guarde el documento en formato PDF usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Pdf como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-pdf.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo de correo electrónico a través de .NET" %}}
Antes de convertir MSG a PDF, si desea asegurarse de que está convirtiendo el correo electrónico correcto, puede cargar el documento MSG, analizarlo y ver la propiedad deseada. Mediante el uso de la clase [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, puede obtener información sobre el remitente y los destinatarios. Por ejemplo, puede verificar el correo electrónico de un remitente específico para la conversión usando la propiedad [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de documentos PDF a través de .NET" %}}
Al guardar el documento de MSG a PDF, es posible que deba proteger su documento de salida. A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto puede ser útil para evitar que otras personas editen información sensible y confidencial en su documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, le permite controlar la forma en que restringe el contenido usando el [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parámetro de enumeración. Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos MSG a PDF mediante programación: casos de uso" %}}
La conversión de archivos de mensaje (MSG) en formato de documento portátil (PDF) es necesaria para desbloquear las capacidades completas de compartir y análisis de documentos. Esta conversión te permite:

**Usos:**

*   **Informes de Cumplimiento**: Convertir archivos MSG a PDF para cumplimiento regulatorio, asegurando que todos los documentos requeridos se presenten con precisión y a tiempo.
*   **Preservación de Documentos Históricos**: Utilizar la conversión de formato PDF para preservar mensajes históricos y registros, haciéndolos accesibles para futuras referencias o análisis.
*   **Verificación de Elecciones**: Convertir archivos MSG a PDF para los procesos de verificación electoral, asegurando la integridad de los datos de votación y resultados.
*   **Protección de Propiedad Intelectual**: Utilizar la conversión de formato PDF para proteger información de negocio sensible convirtiéndola en un formato evidente del acoso.
*   **Gestión del Archivo de Datos**: Convertir archivos MSG a PDF para almacenar y guardar datos históricos, haciéndolos accesibles para futuras análisis o informes.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}