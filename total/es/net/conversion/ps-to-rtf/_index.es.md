---
title: API de C# para exportar PS a RTF
description: Convierta PS a RTF sin usar Microsoft Word
url_ignore: /es/net/conversion/ps-to-rtf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: RTF
otherformats: DOTM ODT PCL FLATOPC OTT DOT DOTX WORDML MHTML MARKDOWN XAMLFLOW RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar PS a RTF a través de .NET" h2="API .NET para exportar PS a RTF en Windows, macOS y Linux sin usar Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para .NET](https://products.aspose.com/total/net/) es una potente API para agregar funciones de manipulación y conversión de documentos dentro de su aplicación .NET. Mediante el uso de la API avanzada de procesamiento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede convertir el formato de archivo PS a DOC. Después de eso, al utilizar la potente API de procesamiento de documentos [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede procesar DOC a RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir PS a RTF" %}}
1. Abra el archivo PS usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta PS a Doc usando el método [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el archivo Doc usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Guarde el documento en formato RTF usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Rtf como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Descifre el archivo PS usando la contraseña del propietario a través de .NET" %}}
Antes de convertir PS a RTF, si desea descifrar su documento, puede hacerlo mediante la API. Para descifrar el archivo PDF, primero debe crear un objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) y abrir el PS con la contraseña del propietario. Después de eso, debe llamar al método [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) del objeto Document. Finalmente, guarde el archivo actualizado usando el método Guardar del objeto Documento.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crear archivo RTF de solo lectura a través de .NET" %}}
Para proteger su RTF de la edición y evitar que otras personas editen información sensible y confidencial en su documento, también puede configurar la protección del documento mediante la API. Puede limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto se puede hacer usando la API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Le permite controlar la forma en que restringe el contenido mediante el parámetro de enumeración [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos PS a RTF mediante programación: casos de uso" %}}
Los archivos de formato PDF portátiles (PS) se utilizan para almacenar información de documento, lo que los hace ideales para crear documentos y presentaciones profesionales. Sin embargo, cuando se trabaja con contenido multimedia, los archivos RTF (Formato de texto rico) se convierten en esenciales para la edición de texto y formato.

La conversión de archivos PS a formatos RTF es necesaria para desbloquear las capacidades completas de la edición del texto y la formato. Esta conversión permite:

*   Edición de documentos: convertir archivos PS para editar el texto, la estructura y los formatos de manera más intuitiva.
*   Creación de PDF: usar RTF para crear documentos PDF profesionales con una representación precisa de los fuentes y la disposición.
*   Importación de texto: convertir archivos PS para importar grandes cantidades de contenido de texto en otras aplicaciones para la edición eficiente.
*   Preservación de formato: usar RTF para preservar la forma de los documentos, incluidos los fuentes, el espacio y la alineación, durante la compartición y la colaboración.
*   Mejora de compatibilidad: convertir archivos PS para mejorar su compatibilidad con diversas aplicaciones y plataformas, garantizando una intercambio documental sin problemas.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}