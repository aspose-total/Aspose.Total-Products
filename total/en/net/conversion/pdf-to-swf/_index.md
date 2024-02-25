---
title: Export PDF to SWF via C# API
description: .NET API to Convert PDF to SWF without using Microsoft Word
url_ignore: /net/conversion/pdf-to-swf/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: SWF
otherformats: PPT PPS POTM OTP ODP PPTM XAML PPSM POWERPOINT PPSX POT POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to SWF via .NET" h2=".NET API to Export PDF to SWF on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a powerful package of File Format Automation APIs that makes it easy to Render PDF to SWF in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the PDF file format to PPTX. This API provides a wide range of features to manipulate PDF documents, such as creating, editing, converting, and printing. It also supports a variety of file formats, including PDF, XPS, TIFF, HTML, and more. 

The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to SWF. This API provides a comprehensive set of features to create, edit, and convert presentations. It supports a variety of file formats, including PPTX, PPT, PPSX, PPS, POTX, POT, and more. It also provides features to add, delete, and modify slides, shapes, text, and images. 

Using Aspose.Total for .NET, you can easily Render PDF to SWF in two simple steps. The PDF Processing API allows you to transform PDF file format to PPTX, and the Presentation Processing API allows you to convert PPTX to SWF. This package of File Format Automation APIs provides a comprehensive set of features to manipulate PDF and presentation documents, making it easy to convert between different file formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PDF to SWF" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to SWF format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Swf` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load PDF file with an instance of Document class
Document document = new Document("input.pdf");
// save PDF as a PPTX 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 
// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Swf
presentation.Save("output.swf", SaveFormat.Swf);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from PDF File via .NET" %}}
While converting PDF to SWF, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a PDF file’s XMP metadata. To get a PDF file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input PDF file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
{{% blocks/products/pf/feature-page-code %}}
```cs// open PDF document
Document doc = new Document("input.pdf");
// get PDF XMP properties
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
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}