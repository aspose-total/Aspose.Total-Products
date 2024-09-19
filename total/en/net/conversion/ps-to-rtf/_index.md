---
title: C# API to Export PS to RTF
description: Convert PS to RTF without using Microsoft Word
url_ignore: /net/conversion/ps-to-rtf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: RTF
otherformats: DOTM ODT PCL FLATOPC OTT DOT DOTX WORDML MHTML MARKDOWN XAMLFLOW DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PS to RTF via .NET" h2=".NET API to Export PS to RTF on Windows, macOS, and Linux without using Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive API that provides powerful document manipulation and conversion features for .NET applications. It includes the Aspose.PDF for .NET API, which enables developers to convert PostScript (PS) files to the DOC format. Once the conversion is complete, the Aspose.Words for .NET API can be used to render the DOC file to Rich Text Format (RTF). 

The Aspose.PDF for .NET API is a powerful tool for creating, editing, and manipulating PDF documents. It provides a wide range of features, such as the ability to convert PDF files to other formats, extract text from PDFs, add annotations, and more. It also supports the conversion of PS files to DOC, allowing developers to easily convert documents from one format to another. 

The Aspose.Words for .NET API is a powerful document processing API that enables developers to create, edit, and convert documents from one format to another. It supports a wide range of document formats, including DOC, RTF, HTML, and more. It also provides features such as document merging, mail merge, and document comparison. With the Aspose.Words for .NET API, developers can easily render DOC files to RTF. 

Aspose.Total for .NET is a powerful API that provides developers with the tools they need to create, edit, and convert documents. With the Aspose.PDF for .NET API, developers can easily convert PS files to DOC, and with the Aspose.Words for .NET API, they can render DOC to RTF. Aspose.Total for .NET is an invaluable tool for any .NET developer looking to add document manipulation and conversion features to their applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert PS to RTF" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PS to Doc by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load Doc file by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class of Aspose.Words 
4. Save the document to RTF format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Rtf as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrypt PS File using Owner Password via .NET" %}}
Before converting PS to RTF, if you want to decrypt your document you can do it by using the API. In order to decrypt the PDF file, you first need to create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the PS using the owner’s password. After that, you need to call [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) method of the Document object. Finally, save the updated file using Save method of the Document object. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create ReadOnly RTF- File via .NET" %}}
In order to protect your RTF from editing and to prevent other people from editing sensitive and confidential information in your document, you can also set the protection of the document using the API. You can limit the ability to edit a document and only allow certain actions with it. This can be done using [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. It enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load Doc with an instance of Document
Document document = new Document("input.doc");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Rtf
document.Save("output.rtf", SaveFormat.Rtf);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}