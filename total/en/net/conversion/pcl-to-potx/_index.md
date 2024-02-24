---
title: Export PCL to POTX via C# API
description: .NET API to Convert PCL to POTX without using Microsoft Word
url_ignore: /net/conversion/pcl-to-potx/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: POTX
otherformats: OTP PPSM PPS XAML POT SWF POTM PPSX POWERPOINT ODP PPT PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PCL to POTX via .NET" h2=".NET API to Export PCL to POTX on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a powerful package of File Format Automation APIs that can be used to easily convert PCL to POTX in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the PCL file format into PPTX. This API provides a wide range of features to manipulate PDF documents, such as creating, editing, converting, and merging PDF files. It also supports a variety of other file formats, such as HTML, XPS, and TIFF. 

The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to POTX. This API provides a comprehensive set of features to create, edit, and manipulate presentations. It supports a variety of file formats, such as PPT, PPTX, PPS, PPSX, POT, POTX, and ODP. It also supports a variety of image formats, such as JPEG, PNG, TIFF, and GIF. 

Using Aspose.Total for .NET, you can easily and quickly convert PCL to POTX in two simple steps. First, use the PDF Processing API, Aspose.PDF for .NET, to transform the PCL file format into PPTX. Then, use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to POTX. This package of File Format Automation APIs provides a comprehensive set of features to create, edit, and manipulate presentations, as well as a wide range of features to manipulate PDF documents.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PCL to POTX" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PCL to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to POTX format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Potx` as SaveFormat
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
// call save method while passing SaveFormat.Potx
presentation.Save("output.potx", SaveFormat.Potx);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from PCL File via .NET" %}}
While converting PCL to POTX, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a PCL file’s XMP metadata. To get a PCL file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input PCL file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
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

{{% blocks/products/pf/feature-page-section  h2="Create Read Only POTX File via .NET" %}}
 By using [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, you can further enhance the features of your conversion application. One of the feature can be to create your output file read only to increase security. The API allows you to set your POTX file to Read-Only, which means users (after they open the presentation) see the Read-Only recommendation.
{{% blocks/products/pf/feature-page-code %}}
```cs// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// make POTX read only
presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Potx
presentation.Save("output.potx", SaveFormat.Potx);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}