---
title: API de C# para exportar correo electrónico a EMF
description: Convierta MSG a EMF sin usar Microsoft Word o Outlook en .NET
url_ignore: /es/net/conversion/msg-to-emf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EMF
otherformats: DOTX JPEG PCL OTT SVG PS ODT DOCX DOT DOCM EPUB XPS WORDML PNG MD TIFF TEXT DOC RTF EMF PDF FLATOPC DOTM GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar MSG a EMF a través de .NET" h2=".NET API para procesar MSG a EMF en Windows, macOS y Linux sin usar Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si es un desarrollador de .NET que busca agregar funciones de conversión de MSG a EMF dentro de sus aplicaciones, las API de manipulación de formato de archivo de [Aspose.Total for .NET](https://products.aspose.com/total/net/) son la solución. delantero. Al usar [Aspose.Email for .NET](https://products.aspose.com/email/net/), puede convertir el formato de archivo de MSG a HTML. Después de eso, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede convertir HTML a EMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir correo electrónico a EMF" %}}
1. Abra el archivo MSG usando la clase [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Convierta MSG a HTML utilizando el método [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Guarde el documento en formato EMF usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Emf como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.emf", SaveFormat.Emf); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo de correo electrónico a través de .NET" %}}
Antes de convertir MSG a EMF, si desea asegurarse de que está convirtiendo el correo electrónico correcto, puede cargar el documento MSG, analizarlo y ver la propiedad deseada. Mediante el uso de la clase [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, puede obtener información sobre el remitente y los destinatarios. Por ejemplo, puede verificar el correo electrónico de un remitente específico para la conversión usando la propiedad [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de documentos EMF a través de .NET" %}}
Al guardar el documento de MSG a EMF, es posible que deba proteger su documento de salida. A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto puede ser útil para evitar que otras personas editen información sensible y confidencial en su documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, le permite controlar la forma en que restringe el contenido usando el [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parámetro de enumeración. Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos MSG a EMF mediante programación: casos de uso" %}}
Es necesario convertir archivos MSG a formatos de EMF para desbloquear las capacidades completas de edición de imágenes. Esta conversión te permite:

**Usos:

*   **Diseño gráfico e ilustración**: Convertir archivos MSG para crear gráficos estáticos, ilustraciones y arte.
*   **Preservación del arte digital**: Utilizar formatos de EMF para preservar el arte digital, garantizar compatibilidad con software legado y mantener la integridad de la imagen.
*   **Bóveda técnica y CAD**: Convertir archivos MSG para apoyar los dibujos técnicos, el diseño asistido por computadora (CAD) y las aplicaciones de ingeniería.
*   **Captura pantalla y rasterización**: Utilizar formatos de EMF para capturar pantallas, convertir gráficos rasterizados a formatos vectoriales y mejorar la calidad de rendición de pantalla.
*   **Digital signage e publicidad**: Convertir archivos MSG para crear señales digitales atractivas, materiales de publicidad interactivos y paneles de diapositiva.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}