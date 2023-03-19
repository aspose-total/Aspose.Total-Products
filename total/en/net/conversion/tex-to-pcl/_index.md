---
title: C# API to Export TEX to PCL
description: Convert TEX to PCL without using Microsoft Word
url_ignore: /net/conversion/tex-to-pcl/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: PCL
otherformats: ODT RTF DOTM MARKDOWN PS DOCM OTT WORDML DOT FLATOPC MHTML DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render TEX to PCL via .NET" h2=".NET API to Export TEX to PCL on Windows, macOS, and Linux without using Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) is a powerful API to add document manipulation and conversion features inside your .NET application. By using advanced PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), you can convert TEX file format to DOC. After that, by using powerful Document Processing API [Aspose.Words for .NET](https://products.aspose.com/words/net/), you can render DOC to PCL. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert TEX to PCL" %}}
1. Open TEX file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert TEX to Doc by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load Doc file by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class of Aspose.Words 
4. Save the document to PCL format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Pcl as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.Save("DocOutput.doc", SaveFormat.Doc); 
// load Doc with an instance of Document
var outputDocument = new Aspose.Words.Document("DocOutput.doc");
// call save method while passing SaveFormat.Pcl
outputDocument.Save("output.pcl", SaveFormat.Pcl);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Decrypt TEX File using Owner Password via .NET" %}}
Before converting TEX to PCL, if you want to decrypt your document you can do it by using the API. In order to decrypt the PDF file, you first need to create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the TEX using the owner’s password. After that, you need to call [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) method of the Document object. Finally, save the updated file using Save method of the Document object. 
{{% blocks/products/pf/feature-page-code %}}
```cs// open document
Document document = new Document("Decrypt.tex", "password");
// decrypt TEX
document.Decrypt();
// save the decrypted document as doc 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create ReadOnly PCL- File via .NET" %}}
In order to protect your PCL from editing and to prevent other people from editing sensitive and confidential information in your document, you can also set the protection of the document using the API. You can limit the ability to edit a document and only allow certain actions with it. This can be done using [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. It enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load Doc with an instance of Document
Document document = new Document("input.doc");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Pcl
document.Save("output.pcl", SaveFormat.Pcl);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}