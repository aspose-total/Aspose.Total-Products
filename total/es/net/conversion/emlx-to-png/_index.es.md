---
title: API de C# para exportar correo electrónico a PNG
description: Convierta EMLX a PNG sin usar Microsoft Word o Outlook en .NET
url_ignore: /es/net/conversion/emlx-to-png/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PNG
otherformats: PNG JPEG DOCX FLATOPC TEXT OTT XPS WORDML ODT DOTX EPUB DOC PS TIFF RTF GIF MD DOCM SVG EMF DOTM DOT PDF PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EMLX a PNG a través de .NET" h2=".NET API para procesar EMLX a PNG en Windows, macOS y Linux sin usar Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Si es un desarrollador de .NET que busca agregar funciones de conversión de EMLX a PNG dentro de sus aplicaciones, las API de manipulación de formato de archivo de [Aspose.Total for .NET](https://products.aspose.com/total/net/) son la solución. delantero. Al usar [Aspose.Email for .NET](https://products.aspose.com/email/net/), puede convertir el formato de archivo de EMLX a HTML. Después de eso, al usar [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede convertir HTML a PNG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir correo electrónico a PNG" %}}
1. Abra el archivo EMLX usando la clase [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Convierta EMLX a HTML utilizando el método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Guarde el documento en formato PNG usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Png como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo de correo electrónico a través de .NET" %}}Aspose.Email for .NET
Antes de convertir EMLX a PNG, si desea asegurarse de que está convirtiendo el correo electrónico correcto, puede cargar el documento EMLX, analizarlo y ver la propiedad deseada. Mediante el uso de la clase [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, puede obtener información sobre el remitente y los destinatarios. Por ejemplo, puede verificar el correo electrónico de un remitente específico para la conversión usando la propiedad [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir la edición de documentos PNG a través de .NET" %}}
Al guardar el documento de EMLX a PNG, es posible que deba proteger su documento de salida. A veces, es posible que deba limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto puede ser útil para evitar que otras personas editen información sensible y confidencial en su documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, le permite controlar la forma en que restringe el contenido usando el [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parámetro de enumeración. Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMLX a PNG mediante programación: casos de uso" %}}
Los archivos de metafile aumentado (EMF) se utilizan para almacenar información gráfica de piso, lo que los hace ideales para crear imágenes estáticas e ilustraciones.

Sin embargo, al trabajar con datos dinámicos, otros formatos de archivo son esenciales para la edición y manipulación de imágenes.

La conversión de archivos EMF a formatos PNG es necesaria para desbloquear la potencial completa de tus capacidades de edición e impresión de imágenes. Esta conversión te permite:

**Uso Caso:**

*   **Edición e Impresión de Imágenes**: Convertir archivos EMF para editar y manipular imágenes, agregar texto, formas y efectos.
*   Diseño e Desarrollo de Iconos: Utilizar PNG para crear iconos escalables, logos y gráficos para diferentes aplicaciones.
*   Creación de Gráficas e Ilustraciones Intrincadas: Convertir archivos EMF para crear ilustraciones, gráficos y animaciones complejas que se pueden utilizar en publicaciones.
*   Optimización Web y Móvil: Utilizar PNG para optimizar imágenes para dispositivos web y móviles, asegurando velocidades de carga rápidas y visualizaciones de alta calidad.
*   Visualización de Datos e Informes Interactivos: Convertir archivos EMF para crear visualizaciones interactivas e informes, utilizando PNG para mostrar vislumbres de datos impulsados.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}