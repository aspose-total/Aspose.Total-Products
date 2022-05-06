---
title: Export XML to PPSX via C# API
description: .NET API to Convert XML to PPSX without using Microsoft Word
url_ignore: /net/conversion/xml-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: PPSX
otherformats: ODP POWERPOINT POTX OTP XAML PPS POTM SWF PPTM POT PPT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XML to PPSX via .NET" h2=".NET API to Export XML to PPSX on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Using a package of powerful File Format Automation APIs [Aspose.Total for .NET](https://products.aspose.com/total/net/) you can easily Render XML to PPSX in two simple steps. By using PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), you can transform XML file format to PPTX. After that, by using Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), you can convert PPTX to PPSX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert XML to PPSX" %}}
1. Open XML file using [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XML to PPTX by using [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to PPSX format using [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Ppsx` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load XML file with an instance of Document class
Document document = new Document("input.xml");
// save XML as a PPTX 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 
// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Ppsx
presentation.Save("output.ppsx", SaveFormat.Ppsx);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from XML File via .NET" %}}
While converting XML to PPSX, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a XML file’s XMP metadata. To get a XML file’s metadata, you can create a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) object and open the input XML file. After that, you can get the file’s metadata using the [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
{{% blocks/products/pf/feature-page-code %}}
```cs// open XML document
Document doc = new Document("input.xml");
// get XML XMP properties
Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Read Only PPSX File via .NET" %}}
 By using [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, you can further enhance the features of your conversion application. One of the feature can be to create your output file read only to increase security. The API allows you to set your PPSX file to Read-Only, which means users (after they open the presentation) see the Read-Only recommendation.
{{% blocks/products/pf/feature-page-code %}}
```cs// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// make PPSX read only
presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Ppsx
presentation.Save("output.ppsx", SaveFormat.Ppsx);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}