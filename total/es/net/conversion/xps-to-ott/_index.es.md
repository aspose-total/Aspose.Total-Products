---
title: API de C# para exportar XPS a OTT
description: Convierta XPS a OTT sin usar Microsoft Word
url: /es/net/conversion/xps-to-ott/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: OTT
otherformats: WORDML MARKDOWN DOT RTF XAMLFLOW FLATOPC MHTML DOTX OTT PCL DOTM PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar XPS a OTT a través de .NET" h2="API .NET para exportar XPS a OTT en Windows, macOS y Linux sin usar Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total para .NET](https://products.aspose.com/total/net/) es una potente API para agregar funciones de manipulación y conversión de documentos dentro de su aplicación .NET. Mediante el uso de la API avanzada de procesamiento de PDF [Aspose.PDF para .NET](https://products.aspose.com/pdf/net/), puede convertir el formato de archivo XPS a DOC. Después de eso, al utilizar la potente API de procesamiento de documentos [Aspose.Words for .NET](https://products.aspose.com/words/net/), puede procesar DOC a OTT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C# para convertir XPS a OTT" %}}
1. Abra el archivo XPS usando la clase [Documento](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Convierta XPS a Doc usando el método [Guardar](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Cargue el archivo Doc usando la clase [Document](https://apireference.aspose.com/words/net/aspose.words/document) de Aspose.Words
4. Guarde el documento en formato OTT usando el método [Guardar](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) y configure Ott como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.xps");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.ott", SaveFormat.Ott);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Descifre el archivo XPS usando la contraseña del propietario a través de .NET" %}}
Antes de convertir XPS a OTT, si desea descifrar su documento, puede hacerlo mediante la API. Para descifrar el archivo PDF, primero debe crear un objeto [Documento](https://apireference.aspose.com/pdf/net/aspose.pdf/document) y abrir el XPS con la contraseña del propietario. Después de eso, debe llamar al método [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) del objeto Document. Finalmente, guarde el archivo actualizado usando el método Guardar del objeto Documento.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.xps", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crear archivo OTT de solo lectura a través de .NET" %}}
Para proteger su OTT de la edición y evitar que otras personas editen información sensible y confidencial en su documento, también puede configurar la protección del documento mediante la API. Puede limitar la capacidad de editar un documento y permitir solo ciertas acciones con él. Esto se puede hacer usando la API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Le permite controlar la forma en que restringe el contenido mediante el parámetro de enumeración [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Puede configurar su documento para que sea de solo lectura usando las siguientes líneas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-ott/" name="XPS Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-mhtml/" name="XPS Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-wordml/" name="XPS Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-dot/" name="XPS Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-odt/" name="XPS Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-rtf/" name="XPS Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-ps/" name="XPS Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-flatopc/" name="XPS Para FLAParaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-pcl/" name="XPS Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-markdown/" name="XPS Para MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-xamlflow/" name="XPS Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/xps-to-dotx/" name="XPS Para DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}