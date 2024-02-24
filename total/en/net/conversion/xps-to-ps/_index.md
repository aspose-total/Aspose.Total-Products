---
title: C# API to Export XPS to PS
description: Convert XPS to PS without using Microsoft Word
url_ignore: /net/conversion/xps-to-ps/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: PS
otherformats: FLATOPC RTF ODT PCL DOTM MHTML DOT DOTX OTT DOCM XAMLFLOW WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS to PS via .NET" h2=".NET API to Export XPS to PS on Windows, macOS, and Linux without using Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive API that provides powerful document manipulation and conversion features for .NET applications. It includes the Aspose.PDF for .NET API, which enables developers to convert XPS file formats to DOC. This is followed by the Aspose.Words for .NET API, which allows developers to render DOC to PS. 

The Aspose.PDF for .NET API provides a wide range of features for manipulating PDF documents. It enables developers to create, edit, and convert PDF documents, as well as to extract text, images, and other content from PDFs. It also provides features for creating PDF forms, adding annotations, and digitally signing documents. 

The Aspose.Words for .NET API is a powerful document processing API that enables developers to create, edit, and convert Word documents. It provides features for creating, editing, and converting documents, as well as for rendering documents to various formats, such as HTML, PDF, and PS. It also provides features for manipulating document elements, such as paragraphs, tables, and images. 

Aspose.Total for .NET is an ideal solution for developers who need to add document manipulation and conversion features to their .NET applications. It provides powerful APIs for manipulating and converting PDF and Word documents, as well as for rendering documents to various formats. With Aspose.Total for .NET, developers can easily add document manipulation and conversion features to their .NET applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert XPS to PS" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XPS to Doc by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load Doc file by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class of Aspose.Words 
4. Save the document to PS format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Ps as SaveFormat
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
// call save method while passing SaveFormat.Ps
outputDocument.Save("output.ps", SaveFormat.Ps);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrypt XPS File using Owner Password via .NET" %}}
Before converting XPS to PS, if you want to decrypt your document you can do it by using the API. In order to decrypt the PDF file, you first need to create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the XPS using the owner’s password. After that, you need to call [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) method of the Document object. Finally, save the updated file using Save method of the Document object. 
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

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}