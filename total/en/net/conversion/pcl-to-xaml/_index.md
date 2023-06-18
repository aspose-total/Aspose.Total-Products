---
title: Export PCL to XAML via C# API
description: .NET API to Convert PCL to XAML without using Microsoft Word
url_ignore: /net/conversion/pcl-to-xaml/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: XAML
otherformats: POTM PPSX PPS POT POWERPOINT SWF PPSM PPTM PPT POTX ODP OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PCL to XAML via .NET" h2=".NET API to Export PCL to XAML on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a powerful package of File Format Automation APIs that makes it easy to Render PCL to XAML in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the PCL file format to PPTX. The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to XAML. 

The PDF Processing API, Aspose.PDF for .NET, is a comprehensive library of tools that enables developers to create, edit, and convert PDF documents. It provides a wide range of features such as creating, editing, and converting PDF documents, extracting text and images from PDFs, and adding annotations and watermarks. It also supports the conversion of PCL files to PPTX. 

The Presentation Processing API, Aspose.Slides for .NET, is a comprehensive library of tools that enables developers to create, edit, and convert presentation documents. It provides a wide range of features such as creating, editing, and converting presentation documents, extracting text and images from presentations, and adding annotations and watermarks. It also supports the conversion of PPTX to XAML. 

Using Aspose.Total for .NET, developers can easily Render PCL to XAML in two simple steps. The PDF Processing API, Aspose.PDF for .NET, is used to convert PCL files to PPTX, and the Presentation Processing API, Aspose.Slides for .NET, is used to convert PPTX to XAML. This makes it easy for developers to quickly and easily convert PCL files to XAML.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PCL to XAML" %}}
1. Open PCL file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PCL to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to XAML format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Xaml` as SaveFormat
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
// call save method while passing SaveFormat.Xaml
presentation.Save("output.xaml", SaveFormat.Xaml);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from PCL File via .NET" %}}
While converting PCL to XAML, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a PCL file’s XMP metadata. To get a PCL file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input PCL file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
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

{{% blocks/products/pf/feature-page-section  h2="Create Read Only XAML File via .NET" %}}
 By using [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, you can further enhance the features of your conversion application. One of the feature can be to create your output file read only to increase security. The API allows you to set your XAML file to Read-Only, which means users (after they open the presentation) see the Read-Only recommendation.
{{% blocks/products/pf/feature-page-code %}}
```cs// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// make XAML read only
presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Xaml
presentation.Save("output.xaml", SaveFormat.Xaml);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}