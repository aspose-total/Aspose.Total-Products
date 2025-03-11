---
title: API de C# para exportar correo electrónico a JPEG
description: Convierta EMAIL a JPEG sin usar Microsoft Word o Outlook en .NET
url_ignore: /es/net/conversion/email-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: JPEG
otherformats: PNG DOC DOT EMF FLATOPC ODT MD TIFF XPS DOCM EPUB TEXT WORDML JPEG DOTM OTT PDF SVG DOCX GIF RTF PCL PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EMAIL a JPEG a través de .NET" h2=".NET API para procesar EMAIL a JPEG en Windows, macOS y Linux sin usar Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si es un desarrollador de .NET que busca agregar funciones de conversión de EMAIL a JPEG dentro de sus aplicaciones, las API de manipulación de formato de archivo de [Aspose.Total for .NET](https://products.aspose.com/total/net/) son la solución. delantero. Al usar [Aspose.Email for .NET](https://products.aspose.com/email/net/), puede convertir el formato de archivo de EMAIL a HTML. Después de eso, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede convertir HTML a JPEG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir correo electrónico a JPEG" %}}
1. Abra el archivo EMAIL usando la clase [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convierta EMAIL a HTML utilizando el método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Guarde el documento en formato JPEG usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Jpeg como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo de correo electrónico a través de .NET" %}}
Antes de convertir EMAIL a JPEG, si desea asegurarse de que está convirtiendo el correo electrónico correcto, puede cargar el documento EMAIL, analizarlo y ver la propiedad deseada. Mediante el uso de la clase [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, puede obtener información sobre el remitente y los destinatarios. Por ejemplo, puede verificar el correo electrónico de un remitente específico para la conversión usando la propiedad [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de documentos JPEG a través de .NET" %}}
Al guardar el documento de EMAIL a JPEG, es posible que deba proteger su documento de salida. A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto puede ser útil para evitar que otras personas editen información sensible y confidencial en su documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, le permite controlar la forma en que restringe el contenido usando el [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parámetro de enumeración. Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a JPEG mediante programación: casos de uso" %}}
Convierte archivos de correo electrónico a imágenesJPEG es una necesidad para desbloquear el potencial visual.

Los archivos de correo electrónico, que contienen datos de comunicación críticos, se pueden convertir eficientemente en imágenes JPEG, lo que los hace ideales para representaciones visuales estáticas y compartir. Sin embargo, cuando trabajamos con contenido dinámico, las plataformas de redes sociales como Instagram se convierten en fundamentales para el cuentabrazos visual y la participación.

La conversión de archivos de correo electrónico a formatos JPEG es necesaria para desbloquear completamente el potencial visual de tu contenido y capacidades compartibles. Esta conversión permite:

**Casos de uso:**

*   **Compartir en redes sociales**: Convertir archivos de correo electrónico para crear imágenesJPEG que pueden compartirse a través de diversas plataformas de redes sociales, lo que permite un alcance más amplio.
*   **Visualización de productos en comercio electrónico**: Utilizar imágenesJPEG para mostrar detalles de los productos, especificaciones y características, mejorando las experiencias de compra en línea.
*   **Promoción de eventos y publicidad**: Convertir archivos de correo electrónico en imágenesJPEG para promocionar eventos, productos o servicios, capturando la atención y generando interés.
*   **Visualización de datos e infografías**: Utilizar imágenesJPEG para visualizar datos, estadísticas y información, creando contenido informativo y atractivo para diversos públicos.
*   **Campañas de marketing digitales**: Convertir archivos de correo electrónico en imágenesJPEG para crear visuales impactantes para campañas de marketing, publicidad y materiales promocionales.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}