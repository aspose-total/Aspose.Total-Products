---
title: Export XPS to POT via C# API
description: .NET API to Convert XPS to POT without using Microsoft Word
url_ignore: /net/conversion/xps-to-pot/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: POT
otherformats: XAML POTM PPT OTP POWERPOINT ODP PPTM PPSM POTX SWF PPSX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS to POT via .NET" h2=".NET API to Export XPS to POT on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a powerful package of File Format Automation APIs that can be used to easily convert XPS to POT in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the XPS file format into PPTX. The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to POT. 

The Aspose.Total for .NET package provides a comprehensive set of APIs that can be used to automate the process of converting XPS to POT. The PDF Processing API, Aspose.PDF for .NET, provides a wide range of features that can be used to convert XPS to PPTX. It supports a variety of features such as the ability to convert XPS to PDF, convert XPS to HTML, and convert XPS to image formats. It also provides a range of features for manipulating PDF documents, such as the ability to split, merge, and extract pages from PDF documents. 

The Presentation Processing API, Aspose.Slides for .NET, provides a range of features that can be used to convert PPTX to POT. It supports a variety of features such as the ability to convert PPTX to PDF, convert PPTX to HTML, and convert PPTX to image formats. It also provides a range of features for manipulating presentations, such as the ability to add, delete, and rearrange slides, as well as the ability to add text, images, and shapes to slides. 

Using the Aspose.Total for .NET package, you can easily convert XPS to POT in two simple steps. The PDF Processing API, Aspose.PDF for .NET, can be used to convert XPS to PPTX, and the Presentation Processing API, Aspose.Slides for .NET, can be used to convert PPTX to POT. The package provides a comprehensive set of APIs that can be used to automate the process of converting XPS to POT, making it easy to quickly and efficiently convert XPS to POT.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert XPS to POT" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XPS to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to POT format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Pot` as SaveFormat
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
// call save method while passing SaveFormat.Pot
presentation.Save("output.pot", SaveFormat.Pot);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from XPS File via .NET" %}}
While converting XPS to POT, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a XPS file’s XMP metadata. To get a XPS file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input XPS file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
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