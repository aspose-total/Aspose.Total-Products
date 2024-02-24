---
title: Export MD to POT via C# API
description: .NET API to Convert MD to POT without using Microsoft Word
url_ignore: /net/conversion/md-to-pot/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: POT
otherformats: POWERPOINT PPTM PPT OTP PPS POTX SWF PPSM POTM ODP XAML PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render MD to POT via .NET" h2=".NET API to Export MD to POT on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a powerful package of File Format Automation APIs that enables you to easily convert MD to POT in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the MD file format to PPTX. This API provides a wide range of features that allow you to manipulate PDF documents, such as creating, editing, converting, and merging PDFs. It also supports a variety of image formats, including JPEG, PNG, TIFF, and BMP. 

Once the MD file has been converted to PPTX, the second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to POT. This API provides a comprehensive set of features for creating, editing, and converting presentations. It supports a variety of presentation formats, including PPT, PPTX, PPS, PPSX, POT, POTX, and ODP. It also supports a variety of image formats, including JPEG, PNG, TIFF, and BMP. 

Using Aspose.Total for .NET, you can quickly and easily convert MD to POT in two simple steps. The PDF Processing API, Aspose.PDF for .NET, can be used to transform the MD file format to PPTX. Then, the Presentation Processing API, Aspose.Slides for .NET, can be used to convert the PPTX to POT. This package of File Format Automation APIs provides a comprehensive set of features for creating, editing, and converting documents and presentations.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert MD to POT" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert MD to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to POT format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Pot` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load MD file with an instance of Document class
Document document = new Document("input.md");
// save MD as a PPTX 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 
// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Pot
presentation.Save("output.pot", SaveFormat.Pot);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from MD File via .NET" %}}
While converting MD to POT, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a MD file’s XMP metadata. To get a MD file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input MD file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
{{% blocks/products/pf/feature-page-code %}}
```cs// open MD document
Document doc = new Document("input.md");
// get MD XMP properties
Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Read Only POT File via .NET" %}}
 By using [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, you can further enhance the features of your conversion application. One of the feature can be to create your output file read only to increase security. The API allows you to set your POT file to Read-Only, which means users (after they open the presentation) see the Read-Only recommendation.
{{% blocks/products/pf/feature-page-code %}}
```cs// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// make POT read only
presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Pot
presentation.Save("output.pot", SaveFormat.Pot);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}