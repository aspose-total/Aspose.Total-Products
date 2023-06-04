---
title: C# API to Export XPS to MARKDOWN
description: Convert XPS to MARKDOWN without using Microsoft Word
url_ignore: /net/conversion/xps-to-markdown/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: MARKDOWN
otherformats: XAMLFLOW MHTML DOCM DOTM DOTX PS FLATOPC RTF DOT OTT WORDML ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS to MARKDOWN via .NET" h2=".NET API to Export XPS to MARKDOWN on Windows, macOS, and Linux without using Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive API that provides powerful document manipulation and conversion features for .NET applications. It includes the Aspose.PDF for .NET API, which enables developers to convert XPS file formats to DOC. This is followed by the Aspose.Words for .NET API, which allows developers to render DOC to MARKDOWN. 

The Aspose.PDF for .NET API provides a wide range of features for manipulating PDF documents, such as creating, editing, converting, and merging PDFs. It also supports the conversion of XPS files to DOC, allowing developers to easily convert XPS documents to the DOC format. The API also supports the conversion of PDF documents to other popular file formats, such as HTML, XPS, and image formats.

The Aspose.Words for .NET API provides a comprehensive set of features for manipulating DOC documents. It supports the rendering of DOC documents to MARKDOWN, allowing developers to easily convert DOC documents to the MARKDOWN format. The API also supports the conversion of DOC documents to other popular file formats, such as HTML, PDF, and image formats.

Overall, Aspose.Total for .NET is a powerful API that provides a comprehensive set of features for manipulating and converting documents. It includes the Aspose.PDF for .NET API, which enables developers to convert XPS file formats to DOC, and the Aspose.Words for .NET API, which allows developers to render DOC to MARKDOWN. With these APIs, developers can easily manipulate and convert documents to the desired format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert XPS to MARKDOWN" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XPS to Doc by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load Doc file by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class of Aspose.Words 
4. Save the document to MARKDOWN format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Markdown as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.Save("DocOutput.doc", SaveFormat.Doc); 
// load Doc with an instance of Document
var outputDocument = new Aspose.Words.Document("DocOutput.doc");
// call save method while passing SaveFormat.Markdown
outputDocument.Save("output.markdown", SaveFormat.Markdown);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrypt XPS File using Owner Password via .NET" %}}
Before converting XPS to MARKDOWN, if you want to decrypt your document you can do it by using the API. In order to decrypt the PDF file, you first need to create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the XPS using the owner’s password. After that, you need to call [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) method of the Document object. Finally, save the updated file using Save method of the Document object. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open document
Document document = new Document("Decrypt.xps", "password");
// decrypt XPS
document.Decrypt();
// save the decrypted document as doc 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create ReadOnly MARKDOWN- File via .NET" %}}
In order to protect your MARKDOWN from editing and to prevent other people from editing sensitive and confidential information in your document, you can also set the protection of the document using the API. You can limit the ability to edit a document and only allow certain actions with it. This can be done using [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. It enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load Doc with an instance of Document
Document document = new Document("input.doc");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Markdown
document.Save("output.markdown", SaveFormat.Markdown);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}