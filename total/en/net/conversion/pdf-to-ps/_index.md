---
title: C# API to Export PDF to PS
description: Convert PDF to PS without using Microsoft Word
url_ignore: /net/conversion/pdf-to-ps/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: PS
otherformats: FLATOPC DOTM MARKDOWN RTF OTT WORDML PCL DOTX DOT ODT MHTML XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to PS via .NET" h2=".NET API to Export PDF to PS on Windows, macOS, and Linux without using Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of APIs that enables developers to add powerful document manipulation and conversion features to their .NET applications. It includes the Aspose.PDF for .NET API, which provides advanced PDF processing capabilities, allowing developers to convert PDF files to DOC format. Once the PDF file has been converted, the Aspose.Words for .NET API can be used to render the DOC file to PS format.

The Aspose.PDF for .NET API provides a wide range of features for manipulating PDF documents, including the ability to extract text, images, and annotations from PDFs, as well as the ability to create, edit, and convert PDFs. It also supports the conversion of PDFs to other popular file formats, such as HTML, XPS, and SVG.

The Aspose.Words for .NET API is a powerful document processing API that enables developers to create, edit, and convert documents in a variety of formats, including DOC, DOCX, RTF, and HTML. It also provides features for rendering documents to PS format, as well as for converting documents to other popular formats, such as PDF, XPS, and EPUB.

Aspose.Total for .NET is a powerful and comprehensive suite of APIs that makes it easy for developers to add powerful document manipulation and conversion features to their .NET applications. With the Aspose.PDF for .NET API, developers can easily convert PDF files to DOC format, and with the Aspose.Words for .NET API, they can render the DOC file to PS format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert PDF to PS" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to Doc by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load Doc file by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class of Aspose.Words 
4. Save the document to PS format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Ps as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.Save("DocOutput.doc", SaveFormat.Doc); 
// load Doc with an instance of Document
var outputDocument = new Aspose.Words.Document("DocOutput.doc");
// call save method while passing SaveFormat.Ps
outputDocument.Save("output.ps", SaveFormat.Ps);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrypt PDF File using Owner Password via .NET" %}}
Before converting PDF to PS, if you want to decrypt your document you can do it by using the API. In order to decrypt the PDF file, you first need to create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the PDF using the owner’s password. After that, you need to call [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) method of the Document object. Finally, save the updated file using Save method of the Document object. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open document
Document document = new Document("Decrypt.pdf", "password");
// decrypt PDF
document.Decrypt();
// save the decrypted document as doc 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create ReadOnly PS- File via .NET" %}}
In order to protect your PS from editing and to prevent other people from editing sensitive and confidential information in your document, you can also set the protection of the document using the API. You can limit the ability to edit a document and only allow certain actions with it. This can be done using [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. It enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load Doc with an instance of Document
Document document = new Document("input.doc");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Ps
document.Save("output.ps", SaveFormat.Ps);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}