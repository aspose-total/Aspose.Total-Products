---
title: Export CGM to ODP via C# API
description: .NET API to Convert CGM to ODP without using Microsoft Word
url_ignore: /net/conversion/cgm-to-odp/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODP
otherformats: POT PPSX SWF POWERPOINT OTP POTM PPT PPS POTX XAML PPSM PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render CGM to ODP via .NET" h2=".NET API to Export CGM to ODP on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a powerful package of File Format Automation APIs that can be used to easily convert CGM to ODP in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the CGM file format into PPTX. The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to ODP. 

Aspose.Total for .NET is a comprehensive suite of APIs that can be used to automate a wide range of file format conversions. It includes APIs for manipulating documents, spreadsheets, presentations, images, and other file formats. The PDF Processing API, Aspose.PDF for .NET, is a powerful API that can be used to convert CGM to PPTX. It provides a wide range of features, such as the ability to convert CGM to PDF, extract text from PDF documents, and convert PDF documents to other file formats. 

The Presentation Processing API, Aspose.Slides for .NET, is an API that can be used to convert PPTX to ODP. It provides a wide range of features, such as the ability to create, edit, and convert presentations, as well as the ability to add text, images, and other elements to presentations. It also provides the ability to export presentations to other file formats, such as ODP. 

By using Aspose.Total for .NET, you can easily convert CGM to ODP in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the CGM file format into PPTX. The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to ODP. This powerful package of File Format Automation APIs makes it easy to automate the conversion of CGM to ODP.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert CGM to ODP" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert CGM to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to ODP format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Odp` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load CGM file with an instance of Document class
Document document = new Document("input.cgm");
// save CGM as a PPTX 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 
// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Odp
presentation.Save("output.odp", SaveFormat.Odp);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from CGM File via .NET" %}}
While converting CGM to ODP, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a CGM file’s XMP metadata. To get a CGM file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input CGM file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
{{% blocks/products/pf/feature-page-code %}}
```cs// open CGM document
Document doc = new Document("input.cgm");
// get CGM XMP properties
Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Read Only ODP File via .NET" %}}
 By using [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, you can further enhance the features of your conversion application. One of the feature can be to create your output file read only to increase security. The API allows you to set your ODP file to Read-Only, which means users (after they open the presentation) see the Read-Only recommendation.
{{% blocks/products/pf/feature-page-code %}}
```cs// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// make ODP read only
presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Odp
presentation.Save("output.odp", SaveFormat.Odp);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}