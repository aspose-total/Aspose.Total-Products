---
title: Export XSLFO to SWF via C# API
description: .NET API to Convert XSLFO to SWF without using Microsoft Word
url_ignore: /net/conversion/xslfo-to-swf/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: SWF
otherformats: POTX PPT OTP PPSX POWERPOINT ODP POT PPS POTM PPSM XAML PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XSLFO to SWF via .NET" h2=".NET API to Export XSLFO to SWF on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a powerful package of File Format Automation APIs that can be used to easily render XSLFO to SWF in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the XSLFO file format to PPTX. This API provides a wide range of features that allow you to manipulate PDF documents in various ways, such as converting, creating, editing, and merging. 

The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to SWF. This API provides a comprehensive set of features that allow you to create, edit, and convert presentations in various formats, such as PPT, PPTX, PPS, PPSX, and ODP. It also allows you to add, remove, and modify slides, as well as insert and extract text, images, and shapes. 

By using Aspose.Total for .NET, you can easily render XSLFO to SWF in two simple steps. The PDF Processing API, Aspose.PDF for .NET, is used to transform the XSLFO file format to PPTX, and the Presentation Processing API, Aspose.Slides for .NET, is used to convert the PPTX to SWF. This package of File Format Automation APIs provides a wide range of features that allow you to manipulate documents in various ways, as well as create, edit, and convert presentations in various formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert XSLFO to SWF" %}}
1. Open XSLFO file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XSLFO to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to SWF format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Swf` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load XSLFO file with an instance of Document class
Document document = new Document("input.xslfo");
// save XSLFO as a PPTX 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 
// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Swf
presentation.Save("output.swf", SaveFormat.Swf);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from XSLFO File via .NET" %}}
While converting XSLFO to SWF, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a XSLFO file’s XMP metadata. To get a XSLFO file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input XSLFO file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
{{% blocks/products/pf/feature-page-code %}}
```cs// open XSLFO document
Document doc = new Document("input.xslfo");
// get XSLFO XMP properties
Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Read Only SWF File via .NET" %}}
 By using [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, you can further enhance the features of your conversion application. One of the feature can be to create your output file read only to increase security. The API allows you to set your SWF file to Read-Only, which means users (after they open the presentation) see the Read-Only recommendation.
{{% blocks/products/pf/feature-page-code %}}
```cs// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// make SWF read only
presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Swf
presentation.Save("output.swf", SaveFormat.Swf);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}