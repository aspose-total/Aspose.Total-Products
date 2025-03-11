---
title: API de C# para exportar CGM a MHTML
description: Convierta CGM a MHTML sin usar Microsoft Word
url_ignore: /es/net/conversion/cgm-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MHTML
otherformats: WORDML MHTML DOTX MARKDOWN DOT FLATOPC XAMLFLOW RTF PCL ODT PS DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar CGM a MHTML a través de .NET" h2="API .NET para exportar CGM a MHTML en Windows, macOS y Linux sin usar Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para .NET](https://products.aspose.com/total/net/) es una potente API para agregar funciones de manipulación y conversión de documentos dentro de su aplicación .NET. Mediante el uso de la API avanzada de procesamiento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede convertir el formato de archivo CGM a DOC. Después de eso, al utilizar la potente API de procesamiento de documentos [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede procesar DOC a MHTML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir CGM a MHTML" %}}
1. Abra el archivo CGM usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta CGM a Doc usando el método [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el archivo Doc usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Guarde el documento en formato MHTML usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Mhtml como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-mhtml.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Descifre el archivo CGM usando la contraseña del propietario a través de .NET" %}}
Antes de convertir CGM a MHTML, si desea descifrar su documento, puede hacerlo mediante la API. Para descifrar el archivo PDF, primero debe crear un objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) y abrir el CGM con la contraseña del propietario. Después de eso, debe llamar al método [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) del objeto Document. Finalmente, guarde el archivo actualizado usando el método Guardar del objeto Documento.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crear archivo MHTML de solo lectura a través de .NET" %}}
Para proteger su MHTML de la edición y evitar que otras personas editen información sensible y confidencial en su documento, también puede configurar la protección del documento mediante la API. Puede limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto se puede hacer usando la API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Le permite controlar la forma en que restringe el contenido mediante el parámetro de enumeración [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.mhtml", SaveFormat.Mhtml);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a MHTML mediante programación: casos de uso" %}}
Conviertiendo Archivos de Metafile Gráfico (CGM) a MHTML: Desbloqueando Contenido Interactivo

Los archivos de Metafile Gráfico (CGM) se utilizan ampliamente para almacenar información de gráficos vectoriales, lo que los hace ideales para crear ilustraciones estáticas y gráficos. Sin embargo, cuando se trabaja con contenido dinámico, las plataformas basadas en HTML se vuelven esenciales para experiencias interactivas. Conviertiendo archivos de CGM a formato MHTML, se desbloquea la potencialidad completa de tu contenido interactivo, permitiéndote:

Casos de Uso:

*   **Presentaciones Interactivas**: Convertir archivos de CGM para crear presentaciones interactivas que capturan la atención y el interés del público.
*   **Ilustraciones en Web**: Utilizar MHTML para insertar gráficos vectoriales en páginas web, mejorando la experiencia del usuario y la apariencia visual.
*   **Integración de Contenido Dinámico**: Convertir archivos de CGM para integrar contenido dinámico en aplicaciones basadas en HTML, como plataformas de aprendizaje en línea o sitios de redes sociales.
*   **Conversión de Archivos PDF a HTML**: Utilizar MHTML para convertir archivos PDF que contienen gráficos vectoriales en documentos HTML interactivos, ideales para publicación y compartición en línea.
*   **Mejora de la Accesibilidad**: Convertir archivos de CGM para mejorar la accesibilidad convirtiéndolos en formatos de HTML que respaldan lectores de pantallas y otras tecnologías asistentes.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}