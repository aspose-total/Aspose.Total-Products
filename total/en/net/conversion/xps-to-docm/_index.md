---
title: C# API to Export XPS to DOCM
description: Convert XPS to DOCM without using Microsoft Word
url_ignore: /net/conversion/xps-to-docm/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: DOCM
otherformats: DOT FLATOPC DOTM MHTML WORDML ODT PS MARKDOWN RTF PCL OTT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS to DOCM via .NET" h2=".NET API to Export XPS to DOCM on Windows, macOS, and Linux without using Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a comprehensive API that provides powerful document manipulation and conversion features for .NET applications. It includes a range of APIs that can be used to create, edit, convert, and render documents in various formats. 

The PDF Processing API, Aspose.PDF for .NET, is a powerful tool for converting XPS files to DOC format. It provides a wide range of features, such as the ability to extract text, images, and other content from PDF documents, as well as the ability to create, edit, and convert PDF documents. 

The Document Processing API, Aspose.Words for .NET, is a powerful tool for rendering DOC files to DOCM. It provides a wide range of features, such as the ability to create, edit, and convert documents in various formats, as well as the ability to extract text, images, and other content from documents. It also provides features for manipulating document elements, such as headers, footers, and page numbers. 

Aspose.Total for .NET is a powerful API that can be used to add document manipulation and conversion features to .NET applications. It includes a range of APIs that can be used to create, edit, convert, and render documents in various formats. The PDF Processing API, Aspose.PDF for .NET, can be used to convert XPS files to DOC format, while the Document Processing API, Aspose.Words for .NET, can be used to render DOC files to DOCM. With these powerful APIs, developers can easily add document manipulation and conversion features to their .NET applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert XPS to DOCM" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XPS to Doc by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load Doc file by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class of Aspose.Words 
4. Save the document to DOCM format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Docm as SaveFormat
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
// call save method while passing SaveFormat.Docm
outputDocument.Save("output.docm", SaveFormat.Docm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrypt XPS File using Owner Password via .NET" %}}
Before converting XPS to DOCM, if you want to decrypt your document you can do it by using the API. In order to decrypt the PDF file, you first need to create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the XPS using the owner’s password. After that, you need to call [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) method of the Document object. Finally, save the updated file using Save method of the Document object. 
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

{{% blocks/products/pf/feature-page-section  h2="Create ReadOnly DOCM- File via .NET" %}}
In order to protect your DOCM from editing and to prevent other people from editing sensitive and confidential information in your document, you can also set the protection of the document using the API. You can limit the ability to edit a document and only allow certain actions with it. This can be done using [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. It enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load Doc with an instance of Document
Document document = new Document("input.doc");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Docm
document.Save("output.docm", SaveFormat.Docm);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}