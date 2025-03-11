---
title: API de C# para exportar PS a ODT
description: Convierta PS a ODT sin usar Microsoft Word
url_ignore: /es/net/conversion/ps-to-odt/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: ODT
otherformats: RTF WORDML DOTM ODT OTT DOTX XAMLFLOW FLATOPC DOT MHTML PCL MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar PS a ODT a través de .NET" h2="API .NET para exportar PS a ODT en Windows, macOS y Linux sin usar Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para .NET](https://products.aspose.com/total/net/) es una potente API para agregar funciones de manipulación y conversión de documentos dentro de su aplicación .NET. Mediante el uso de la API avanzada de procesamiento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede convertir el formato de archivo PS a DOC. Después de eso, al utilizar la potente API de procesamiento de documentos [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede procesar DOC a ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir PS a ODT" %}}
1. Abra el archivo PS usando la clase [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta PS a Doc usando el método [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el archivo Doc usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Guarde el documento en formato ODT usando el método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Odt como SaveFormat
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
Antes de convertir PS a ODT, si desea descifrar su documento, puede hacerlo mediante la API. Para descifrar el archivo PDF, primero debe crear un objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) y abrir el PS con la contraseña del propietario. Después de eso, debe llamar al método [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) del objeto Document. Finalmente, guarde el archivo actualizado usando el método Guardar del objeto Documento.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crear archivo ODT de solo lectura a través de .NET" %}}
Para proteger su ODT de la edición y evitar que otras personas editen información sensible y confidencial en su documento, también puede configurar la protección del documento mediante la API. Puede limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto se puede hacer usando la API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Le permite controlar la forma en que restringe el contenido mediante el parámetro de enumeración [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos PS a ODT mediante programación: casos de uso" %}}
 archivos de formato de documento portátil (PS) se utilizan para almacenar documentos, lo que los hace ideales para crear documentos estáticos y publicaciones. Sin embargo, cuando se trabaja con datos dinámicos, las hojas de cálculo como el texto abierto de documentación (ODT) se convierten en esenciales para la edición y colaboración de documentos.

La conversión de archivos PS a formatos ODT es necesaria para desbloquear las capacidades completas de tu capacidad de edición y colaboración de documentos. Esta conversión te permite:

**Uso Caso:**

*   **Investigación académica**: Convierte archivos PS para editar artículos académicos, tesis y disertaciones, colabora con colegas e intercambia hallazgos de investigación.
*   **Escritura técnica**: Usa ODT para crear y editar documentos técnicos, como manuales de usuario, guías y instrucciones, para aplicaciones de software, dispositivos hardware y procesos de ingeniería.
*   **Presentaciones empresariales**: Convierte archivos PS para crear presentaciones atractivas, informes y propuestas utilizando el texto abierto, perfectas para comunicaciones corporativas, reuniones de negocios e eventos industriales.
*   **Publicación y medios**: Usa ODT para editar artículos, historias y contenido para publicaciones, sitios web y plataformas de medios en línea.
*   **Proyectos personales**: Convierte archivos PS para crear documentos personalizados, como currículums, certificados y cartas, utilizando el texto abierto, adaptados a las necesidades individuales.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}