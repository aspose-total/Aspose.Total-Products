---
title: C# API to Export XPS to MHTML
description: Convert XPS to MHTML without using Microsoft Word
url_ignore: /net/conversion/xps-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: MHTML
otherformats: ODT PS RTF DOT PCL MARKDOWN WORDML DOCM DOTX DOTM XAMLFLOW FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS to MHTML via .NET" h2=".NET API to Export XPS to MHTML on Windows, macOS, and Linux without using Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive suite of APIs that provides powerful document manipulation and conversion features for .NET applications. It includes the Aspose.PDF for .NET API, which enables developers to convert XPS file formats to DOC. This API is equipped with advanced features such as the ability to extract text from PDF documents, create and manipulate PDF documents, and convert PDF documents to other popular file formats.

The Aspose.Words for .NET API is a powerful document processing API that enables developers to render DOC files to MHTML. This API provides a wide range of features such as the ability to create, edit, and convert documents, as well as the ability to insert and extract text from documents. It also supports a variety of document formats, including DOC, DOCX, RTF, HTML, and MHTML.

Aspose.Total for .NET is a great choice for developers who need to add document manipulation and conversion features to their .NET applications. With the Aspose.PDF for .NET API, developers can easily convert XPS file formats to DOC. And with the Aspose.Words for .NET API, developers can render DOC files to MHTML. This comprehensive suite of APIs provides developers with the tools they need to create powerful document manipulation and conversion features for their .NET applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert XPS to MHTML" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XPS to Doc by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load Doc file by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class of Aspose.Words 
4. Save the document to MHTML format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Mhtml as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
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
// call save method while passing SaveFormat.Mhtml
outputDocument.Save("output.mhtml", SaveFormat.Mhtml);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrypt XPS File using Owner Password via .NET" %}}
Before converting XPS to MHTML, if you want to decrypt your document you can do it by using the API. In order to decrypt the PDF file, you first need to create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the XPS using the owner’s password. After that, you need to call [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) method of the Document object. Finally, save the updated file using Save method of the Document object. 
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

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}