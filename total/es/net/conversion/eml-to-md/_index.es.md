---
title: API de C# para exportar correo electrónico a MD
description: Convierta EML a MD sin usar Microsoft Word o Outlook en .NET
url_ignore: /es/net/conversion/eml-to-md/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: MD
otherformats: MD RTF FLATOPC PS ODT DOCM DOTX EMF GIF XPS WORDML OTT DOCX TIFF PNG SVG TEXT JPEG EPUB DOC PCL DOT PDF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EML a MD a través de .NET" h2=".NET API para procesar EML a MD en Windows, macOS y Linux sin usar Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si es un desarrollador de .NET que busca agregar funciones de conversión de EML a MD dentro de sus aplicaciones, las API de manipulación de formato de archivo de [Aspose.Total for .NET](https://products.aspose.com/total/net/) son la solución. delantero. Al usar [Aspose.Email for .NET](https://products.aspose.com/email/net/), puede convertir el formato de archivo de EML a HTML. Después de eso, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede convertir HTML a MD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir correo electrónico a MD" %}}
1. Abra el archivo EML usando la clase [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Convierta EML a HTML utilizando el método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Guarde el documento en formato MD usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Md como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.md", SaveFormat.Md); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo de correo electrónico a través de .NET" %}}
Antes de convertir EML a MD, si desea asegurarse de que está convirtiendo el correo electrónico correcto, puede cargar el documento EML, analizarlo y ver la propiedad deseada. Mediante el uso de la clase [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, puede obtener información sobre el remitente y los destinatarios. Por ejemplo, puede verificar el correo electrónico de un remitente específico para la conversión usando la propiedad [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de documentos MD a través de .NET" %}}
Al guardar el documento de EML a MD, es posible que deba proteger su documento de salida. A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto puede ser útil para evitar que otras personas editen información sensible y confidencial en su documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, le permite controlar la forma en que restringe el contenido usando el [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parámetro de enumeración. Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.md", SaveFormat.Md);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a MD mediante programación: casos de uso" %}}
Archivos de correo electrónico (EML) se utilizan para almacenar información basada en texto, lo que los hace ideales para crear correos electrónicos simples y comunicaciones.

Sin embargo, cuando se trabaja con datos complejos y visualizaciones, las formataciones Markdown (MD) son esenciales para la documentación y presentación.

La conversión de archivos EML a formatos Markdown es necesaria para desbloquear las capacidades completas de tu capacidad de documentación y presentación. Esta conversión te permite:

**Uso de casos:**

*   **Documentación de correos electrónicos**: Convertir archivos EML para crear documentación lectora para correos electrónicos, incluyendo cabeceras, pies de página y contenido.
*   **Creación de publicaciones de blog**: Utilizar Markdown para escribir y formatar las publicaciones de blog, permitiendo una fácil compartición y colaboración entre los escritores.
*   **Escritura técnica**: Convertir archivos EML para crear manuales, guías e instrucciones de usuario de manera clara y concisa.
*   **Publicaciones en redes sociales**: Utilizar Markdown para formatear las publicaciones en redes sociales, incluyendo imágenes, enlaces y videos, con el fin de una mejor participación y visibilidad.
*   **Presentaciones y informes**: Convertir archivos EML para crear presentaciones interactivas y informes utilizando sintaxis de Markdown, permitiendo una fácil compartición y colaboración entre los participantes.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}