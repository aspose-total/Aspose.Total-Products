---
title: Export PCL to PPS via C# API
description: .NET API to Convert PCL to PPS without using Microsoft Word
url_ignore: /net/conversion/pcl-to-pps/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: PPS
otherformats: ODP PPT PPSM POWERPOINT POTX XAML POTM PPTM POT PPSX SWF OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PCL to PPS via .NET" h2=".NET API to Export PCL to PPS on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a powerful package of File Format Automation APIs that makes it easy to Render PCL to PPS in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the PCL file format to PPTX. This API provides a wide range of features that allow you to manipulate PDF documents, such as creating, editing, converting, and merging PDFs. 

The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to PPS. This API provides a comprehensive set of features for creating, editing, and converting presentations, including the ability to add, delete, and modify slides, as well as to add text, images, and shapes. It also supports a variety of presentation formats, including PPTX, PPS, PPT, and PPTM. 

By using Aspose.Total for .NET, you can quickly and easily Render PCL to PPS in two simple steps. The PDF Processing API, Aspose.PDF for .NET, can be used to transform the PCL file format to PPTX, and the Presentation Processing API, Aspose.Slides for .NET, can be used to convert the PPTX to PPS. This package of File Format Automation APIs provides a comprehensive set of features for creating, editing, and converting documents, making it an ideal solution for automating file format conversions.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PCL to PPS" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PCL to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to PPS format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Pps` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load PCL file with an instance of Document class
Document document = new Document("input.pcl");
// save PCL as a PPTX 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 
// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Pps
presentation.Save("output.pps", SaveFormat.Pps);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from PCL File via .NET" %}}
While converting PCL to PPS, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a PCL file’s XMP metadata. To get a PCL file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input PCL file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
{{% blocks/products/pf/feature-page-code %}}
```cs// open PCL document
Document doc = new Document("input.pcl");
// get PCL XMP properties
Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Read Only PPS File via .NET" %}}
 By using [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, you can further enhance the features of your conversion application. One of the feature can be to create your output file read only to increase security. The API allows you to set your PPS file to Read-Only, which means users (after they open the presentation) see the Read-Only recommendation.
{{% blocks/products/pf/feature-page-code %}}
```cs// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// make PPS read only
presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Pps
presentation.Save("output.pps", SaveFormat.Pps);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}