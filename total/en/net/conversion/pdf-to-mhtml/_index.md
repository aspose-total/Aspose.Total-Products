---
title: C# API to Export PDF to MHTML
description: Convert PDF to MHTML without using Microsoft Word
url_ignore: /net/conversion/pdf-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: MHTML
otherformats: DOTM XAMLFLOW WORDML DOT PCL FLATOPC RTF DOTX ODT OTT DOCM MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to MHTML via .NET" h2=".NET API to Export PDF to MHTML on Windows, macOS, and Linux without using Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of APIs that provides powerful document manipulation and conversion features for .NET applications. It includes the Aspose.PDF for .NET API, which enables developers to convert PDF files to DOC format. This is followed by the Aspose.Words for .NET API, which allows developers to render DOC files to MHTML. 

The Aspose.PDF for .NET API provides a wide range of features for manipulating PDF documents, such as the ability to create, edit, and convert PDF files. It also supports the extraction of text, images, and other content from PDF documents. Additionally, it can be used to add annotations, watermarks, and digital signatures to PDF documents. 

The Aspose.Words for .NET API provides a comprehensive set of features for creating, editing, and converting DOC files. It supports a wide range of document formats, including DOC, DOCX, RTF, HTML, and MHTML. It also provides features for manipulating document elements, such as text, images, tables, and hyperlinks. Additionally, it can be used to add headers and footers, page numbers, and bookmarks to documents. 

Aspose.Total for .NET is a powerful API that enables developers to quickly and easily add document manipulation and conversion features to their .NET applications. It provides a comprehensive set of features for manipulating PDF and DOC files, including the ability to convert PDF to DOC and render DOC to MHTML.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert PDF to MHTML" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to Doc by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load Doc file by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class of Aspose.Words 
4. Save the document to MHTML format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Mhtml as SaveFormat
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
// call save method while passing SaveFormat.Mhtml
outputDocument.Save("output.mhtml", SaveFormat.Mhtml);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrypt PDF File using Owner Password via .NET" %}}
Before converting PDF to MHTML, if you want to decrypt your document you can do it by using the API. In order to decrypt the PDF file, you first need to create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the PDF using the owner’s password. After that, you need to call [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) method of the Document object. Finally, save the updated file using Save method of the Document object. 
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

{{% blocks/products/pf/feature-page-section  h2="Create ReadOnly MHTML- File via .NET" %}}
In order to protect your MHTML from editing and to prevent other people from editing sensitive and confidential information in your document, you can also set the protection of the document using the API. You can limit the ability to edit a document and only allow certain actions with it. This can be done using [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. It enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load Doc with an instance of Document
Document document = new Document("input.doc");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Mhtml
document.Save("output.mhtml", SaveFormat.Mhtml);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}