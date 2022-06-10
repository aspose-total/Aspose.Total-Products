---
title: API de C# para exportar SVG a DOTX
description: Convierta SVG a DOTX sin usar Microsoft Word
url_ignore: /es/net/conversion/svg-to-dotx/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: DOTX
otherformats: DOTM PS FLATOPC WORDML DOT MARKDOWN PCL XAMLFLOW MHTML ODT DOTX RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar SVG a DOTX a través de .NET" h2="API .NET para exportar SVG a DOTX en Windows, macOS y Linux sin usar Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para .NET](https://products.aspose.com/total/net/) es una potente API para agregar funciones de manipulación y conversión de documentos dentro de su aplicación .NET. Mediante el uso de la API avanzada de procesamiento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede convertir el formato de archivo SVG a DOC. Después de eso, al utilizar la potente API de procesamiento de documentos [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede procesar DOC a DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir SVG a DOTX" %}}
1. Abra el archivo SVG usando la clase [Documento](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta SVG a Doc usando el método [Guardar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el archivo Doc usando la clase [Document](https://reference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Guarde el documento en formato DOTX usando el método [Guardar](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Dotx como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.svg");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dotx", SaveFormat.Dotx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Descifre el archivo SVG usando la contraseña del propietario a través de .NET" %}}
Antes de convertir SVG a DOTX, si desea descifrar su documento, puede hacerlo mediante la API. Para descifrar el archivo PDF, primero debe crear un objeto [Documento](https://reference.aspose.com/pdf/net/aspose.pdf/document) y abrir el SVG con la contraseña del propietario. Después de eso, debe llamar al método [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) del objeto Document. Finalmente, guarde el archivo actualizado usando el método Guardar del objeto Documento.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.svg", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crear archivo DOTX de solo lectura a través de .NET" %}}
Para proteger su DOTX de la edición y evitar que otras personas editen información sensible y confidencial en su documento, también puede configurar la protección del documento mediante la API. Puede limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto se puede hacer usando la API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Le permite controlar la forma en que restringe el contenido mediante el parámetro de enumeración [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-ott/" name="SVG Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-mhtml/" name="SVG Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-wordml/" name="SVG Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-dot/" name="SVG Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-odt/" name="SVG Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-rtf/" name="SVG Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-ps/" name="SVG Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-flatopc/" name="SVG Para FLAParaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-pcl/" name="SVG Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-markdown/" name="SVG Para MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-xamlflow/" name="SVG Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/svg-to-dotx/" name="SVG Para DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}