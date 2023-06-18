---
title: Export XPS to POTM via C# API
description: .NET API to Convert XPS to POTM without using Microsoft Word
url_ignore: /net/conversion/xps-to-potm/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: POTM
otherformats: PPS SWF POWERPOINT POT PPSX XAML ODP POTX OTP PPSM PPT PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS to POTM via .NET" h2=".NET API to Export XPS to POTM on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a powerful package of File Format Automation APIs that makes it easy to Render XPS to POTM in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the XPS file format into PPTX. This API provides a wide range of features that allow you to manipulate PDF documents, such as creating, editing, converting, and merging PDF files. 

The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to POTM. This API provides a comprehensive set of features for creating, editing, and converting presentations. It also allows you to add text, shapes, images, and other objects to your presentations. Additionally, it supports a wide range of presentation formats, including POTM, PPTX, PPT, PPSX, PPS, and more. 

By using Aspose.Total for .NET, you can easily Render XPS to POTM in two simple steps. The PDF Processing API, Aspose.PDF for .NET, is used to transform the XPS file format into PPTX. Then, the Presentation Processing API, Aspose.Slides for .NET, is used to convert the PPTX to POTM. This package of File Format Automation APIs makes it easy to manipulate and convert a wide range of file formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert XPS to POTM" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XPS to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to POTM format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Potm` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load XPS file with an instance of Document class
Document document = new Document("input.xps");
// save XPS as a PPTX 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 
// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Potm
presentation.Save("output.potm", SaveFormat.Potm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from XPS File via .NET" %}}
While converting XPS to POTM, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a XPS file’s XMP metadata. To get a XPS file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input XPS file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
{{% blocks/products/pf/feature-page-code %}}
```cs// open XPS document
Document doc = new Document("input.xps");
// get XPS XMP properties
Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Read Only POTM File via .NET" %}}
 By using [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, you can further enhance the features of your conversion application. One of the feature can be to create your output file read only to increase security. The API allows you to set your POTM file to Read-Only, which means users (after they open the presentation) see the Read-Only recommendation.
{{% blocks/products/pf/feature-page-code %}}
```cs// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// make POTM read only
presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Potm
presentation.Save("output.potm", SaveFormat.Potm);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}