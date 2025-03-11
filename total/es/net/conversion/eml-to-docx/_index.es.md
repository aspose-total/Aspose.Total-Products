---
title: API de C# para exportar correo electrónico a DOCX
description: Convierta EML a DOCX sin usar Microsoft Word o Outlook en .NET
url_ignore: /es/net/conversion/eml-to-docx/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOCX
otherformats: PCL PDF TEXT RTF DOTM DOCM DOT MD DOTX TIFF DOCX FLATOPC WORDML EMF XPS PS EPUB OTT GIF ODT PNG JPEG DOC SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EML a DOCX a través de .NET" h2=".NET API para procesar EML a DOCX en Windows, macOS y Linux sin usar Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si es un desarrollador de .NET que busca agregar funciones de conversión de EML a DOCX dentro de sus aplicaciones, las API de manipulación de formato de archivo de [Aspose.Total for .NET](https://products.aspose.com/total/net/) son la solución. delantero. Al usar [Aspose.Email for .NET](https://products.aspose.com/email/net/), puede convertir el formato de archivo de EML a HTML. Después de eso, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede convertir HTML a DOCX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir correo electrónico a DOCX" %}}
1. Abra el archivo EML usando la clase [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Convierta EML a HTML utilizando el método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Guarde el documento en formato DOCX usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Docx como SaveFormat
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
Antes de convertir EML a DOCX, si desea asegurarse de que está convirtiendo el correo electrónico correcto, puede cargar el documento EML, analizarlo y ver la propiedad deseada. Mediante el uso de la clase [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, puede obtener información sobre el remitente y los destinatarios. Por ejemplo, puede verificar el correo electrónico de un remitente específico para la conversión usando la propiedad [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de documentos DOCX a través de .NET" %}}
Al guardar el documento de EML a DOCX, es posible que deba proteger su documento de salida. A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto puede ser útil para evitar que otras personas editen información sensible y confidencial en su documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, le permite controlar la forma en que restringe el contenido usando el [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parámetro de enumeración. Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a DOCX mediante programación: casos de uso" %}}
Los archivos de correo electrónico (EML) se utilizan para almacenar mensajes basados en texto, lo que los hace ideales para enviar y recibir correos electrónicos. Sin embargo, cuando trabajas con documentos que requieren formatación y presentación, Microsoft Word (.docx) se convierte en la elección preferida.

La conversión de archivos EML a formatos .docx es necesaria para desbloquear las capacidades completas de edición de documentación de tu software. Esta conversión te permite:

**Usos:**

*   **Comunicación empresarial**: Convertir archivos EML para crear documentos con una presentación profesional, como notas de reuniones, actualizaciones de proyectos y propuestas comerciales.
*   **Correspondencia personal**: Utilizar Word para formatar y editar correos electrónicos personales, cartas y mensajes, asegurando un tono limpio y legible.
*   **Minutas y actas de reuniones**: Convertir archivos EML para crear notas detalladas y organizadas de las reuniones, lo que facilita el seguimiento y las acciones posteriores.
*   **Escribir propuestas y contratos**: Utilizar Word para redactar y editar propuestas, contratos y acuerdos, asegurando claridad, concisión y profesionalismo.
*   **Escribir investigaciones y escrituras académicas**: Convertir archivos EML para crear documentos de investigación con una presentación formatada, lo que facilita la edición y la colaboración.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}