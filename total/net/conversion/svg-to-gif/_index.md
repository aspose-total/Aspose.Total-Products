---
title: C# API to Export SVG to GIF
description: Convert SVG to GIF without using Microsoft Word
url: /net/conversion/svg-to-gif/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: GIF
otherformats: DOCM DOTX OTT RTF WORDML DOT MHTML FLATOPC PCL MARKDOWN XAMLFLOW DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render SVG to GIF via .NET" h2=".NET API to Export SVG to GIF on Windows, macOS, and Linux without using Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) is a powerful API to add document manipulation and conversion features inside your .NET application. By using advanced PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), you can convert SVG file format to DOC. After that, by using powerful Document Processing API [Aspose.Words for .NET](https://products.aspose.com/words/net/), you can render DOC to GIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert SVG to GIF" %}}
1. Open SVG file using [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert SVG to Doc by using [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load Doc file by using [Document](https://apireference.aspose.com/words/net/aspose.words/document) class of Aspose.Words 
4. Save the document to GIF format using [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Gif as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as a DOC 
document.Save("DocOutput.doc", SaveFormat.Doc); 
// load Doc with an instance of Document
var outputDocument = new Aspose.Words.Document("DocOutput.doc");
// call save method while passing SaveFormat.Gif
outputDocument.Save("output.gif", SaveFormat.Gif);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrypt SVG File using Owner Password via .NET" %}}
Before converting SVG to GIF, if you want to decrypt your document you can do it by using the API. In order to decrypt the PDF file, you first need to create a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) object and open the SVG using the owner’s password. After that, you need to call [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) method of the Document object. Finally, save the updated file using Save method of the Document object. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open document
Document document = new Document("Decrypt.svg", "password");
// decrypt SVG
document.Decrypt();
// save the decrypted document as doc 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create ReadOnly GIF- File via .NET" %}}
In order to protect your GIF from editing and to prevent other people from editing sensitive and confidential information in your document, you can also set the protection of the document using the API. You can limit the ability to edit a document and only allow certain actions with it. This can be done using [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. It enables you to control the way you restrict the content using the [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load Doc with an instance of Document
Document document = new Document("input.doc");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Gif
document.Save("output.gif", SaveFormat.Gif);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}