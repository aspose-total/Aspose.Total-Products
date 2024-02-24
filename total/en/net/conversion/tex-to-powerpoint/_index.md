---
title: Export TEX to POWERPOINT via C# API
description: .NET API to Convert TEX to POWERPOINT without using Microsoft Word
url_ignore: /net/conversion/tex-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: POWERPOINT
otherformats: POTM PPSM PPSX XAML PPT POTX OTP PPS SWF POT ODP PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render TEX to POWERPOINT via .NET" h2=".NET API to Export TEX to POWERPOINT on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a powerful package of File Format Automation APIs that makes it easy to Render TEX to POWERPOINT in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the TEX file format to PPTX. This API provides a wide range of features that enable you to manipulate PDF documents in various ways, such as converting, creating, editing, and merging. 

Once the TEX file has been converted to PPTX, the second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to POWERPOINT. This API provides a comprehensive set of features that allow you to create, edit, and manipulate presentations in various ways, such as adding text, images, shapes, and charts. It also enables you to convert presentations to other formats, such as PDF, HTML, and SVG. 

By using Aspose.Total for .NET, you can easily Render TEX to POWERPOINT in two simple steps. The PDF Processing API, Aspose.PDF for .NET, enables you to convert TEX to PPTX, while the Presentation Processing API, Aspose.Slides for .NET, enables you to convert PPTX to POWERPOINT. This package of File Format Automation APIs provides a comprehensive set of features that make it easy to manipulate documents and presentations in various ways.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert TEX to POWERPOINT" %}}
1. Open TEX file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert TEX to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to PPT format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Ppt` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load TEX file with an instance of Document class
Document document = new Document("input.tex");
// save TEX as a PPTX 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 
// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from TEX File via .NET" %}}
While converting TEX to POWERPOINT, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a TEX file’s XMP metadata. To get a TEX file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input TEX file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
{{% blocks/products/pf/feature-page-code %}}
```cs// open TEX document
Document doc = new Document("input.tex");
// get TEX XMP properties
Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Read Only POWERPOINT File via .NET" %}}
 By using [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, you can further enhance the features of your conversion application. One of the feature can be to create your output file read only to increase security. The API allows you to set your POWERPOINT file to Read-Only, which means users (after they open the presentation) see the Read-Only recommendation.
{{% blocks/products/pf/feature-page-code %}}
```cs// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// make POWERPOINT read only
presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}