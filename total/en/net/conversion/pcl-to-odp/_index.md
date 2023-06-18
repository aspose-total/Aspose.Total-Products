---
title: Export PCL to ODP via C# API
description: .NET API to Convert PCL to ODP without using Microsoft Word
url_ignore: /net/conversion/pcl-to-odp/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: ODP
otherformats: PPS SWF PPSM PPTM POT PPSX POTM XAML PPT POTX POWERPOINT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PCL to ODP via .NET" h2=".NET API to Export PCL to ODP on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a powerful package of File Format Automation APIs that can be used to easily convert PCL to ODP in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the PCL file format into PPTX. The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX file to ODP.

The Aspose.Total for .NET package is a comprehensive suite of APIs that can be used to automate the conversion of a wide range of file formats. It includes the PDF Processing API, Aspose.PDF for .NET, which can be used to convert PCL to PPTX. This API is designed to be easy to use and provides a range of features that make it simple to convert PCL to PPTX. It supports a wide range of features, including the ability to convert PCL to PPTX with a single line of code.

The second step in the process is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX file to ODP. This API is designed to be easy to use and provides a range of features that make it simple to convert PPTX to ODP. It supports a wide range of features, including the ability to convert PPTX to ODP with a single line of code.

Aspose.Total for .NET is a powerful package of File Format Automation APIs that can be used to easily convert PCL to ODP in two simple steps. By using the PDF Processing API, Aspose.PDF for .NET, to transform the PCL file format into PPTX, and then using the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX file to ODP, you can quickly and easily convert PCL to ODP. This package of APIs is designed to be easy to use and provides a range of features that make it simple to convert PCL to ODP.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PCL to ODP" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PCL to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to ODP format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Odp` as SaveFormat
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
// call save method while passing SaveFormat.Odp
presentation.Save("output.odp", SaveFormat.Odp);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from PCL File via .NET" %}}
While converting PCL to ODP, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a PCL file’s XMP metadata. To get a PCL file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input PCL file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
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