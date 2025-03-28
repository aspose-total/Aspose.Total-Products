---
title: API de C# para exportar correo electrónico a PCL
description: Convierta EMLX a PCL sin usar Microsoft Word o Outlook en .NET
url_ignore: /es/net/conversion/emlx-to-pcl/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PCL
otherformats: PS EPUB PNG TEXT JPEG TIFF GIF MD FLATOPC EMF XPS ODT DOTM DOCX PCL SVG DOCM OTT WORDML DOT RTF DOTX PDF DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EMLX a PCL a través de .NET" h2=".NET API para procesar EMLX a PCL en Windows, macOS y Linux sin usar Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si es un desarrollador de .NET que busca agregar funciones de conversión de EMLX a PCL dentro de sus aplicaciones, las API de manipulación de formato de archivo de [Aspose.Total for .NET](https://products.aspose.com/total/net/) son la solución. delantero. Al usar [Aspose.Email for .NET](https://products.aspose.com/email/net/), puede convertir el formato de archivo de EMLX a HTML. Después de eso, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede convertir HTML a PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir correo electrónico a PCL" %}}
1. Abra el archivo EMLX usando la clase [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convierta EMLX a HTML utilizando el método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Guarde el documento en formato PCL usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Pcl como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.pcl", SaveFormat.Pcl); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo de correo electrónico a través de .NET" %}}Aspose.Email for .NET
Antes de convertir EMLX a PCL, si desea asegurarse de que está convirtiendo el correo electrónico correcto, puede cargar el documento EMLX, analizarlo y ver la propiedad deseada. Mediante el uso de la clase [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, puede obtener información sobre el remitente y los destinatarios. Por ejemplo, puede verificar el correo electrónico de un remitente específico para la conversión usando la propiedad [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de documentos PCL a través de .NET" %}}
Al guardar el documento de EMLX a PCL, es posible que deba proteger su documento de salida. A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto puede ser útil para evitar que otras personas editen información sensible y confidencial en su documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, le permite controlar la forma en que restringe el contenido usando el [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parámetro de enumeración. Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMLX a PCL mediante programación: casos de uso" %}}
Los archivos de lenguaje de marcado de correo electrónico (EMLX) se utilizan para almacenar información de correos electrónicos basada en texto, lo que los hace ideales para crear correos electrónicos simples con formato básico. Sin embargo, cuando se trabaja con requisitos de visualización y análisis de datos más complejos, los archivos PC/LaTeX (Lista separada por comas impresa LaTeX) son esenciales para el control preciso de tipografía y diseño.

La conversión de archivos EMLX a formatos PC/LaTeX es necesaria para desbloquear la potencialidad visual y profesional de tu documento. Esta conversión te permite:

**Uso Caso:**

*   **Escribir Tecnico**: Convertir archivos EMLX para crear documentos técnicos, manuales de usuario e instrucciones con control de tipografía y diseño preciso.
*   **Publicación Académica**: Utilizar PC/LaTeX para formatar papeles académicos, tesis y tesis de doctorado para su publicación en revistas y conferencias prestigiosas.
*   **Presentaciones Técnicas**: Convertir archivos EMLX para crear presentaciones visuales atractivas, slideshows y conferencias con control de tipografía y diseño preciso.
*   **Prototipos de Diseño**: Utilizar PC/LaTeX para crear prototipos interactivos de diseño, mockups y pruebas de concepto con control de tipografía y diseño preciso.
*   **Comunicaciones Formales**: Convertir archivos EMLX para crear documentos formales, como certificados, cartas de recomendación y informes oficiales.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}