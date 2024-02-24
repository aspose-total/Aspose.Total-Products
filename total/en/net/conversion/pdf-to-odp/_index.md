---
title: Export PDF to ODP via C# API
description: .NET API to Convert PDF to ODP without using Microsoft Word
url_ignore: /net/conversion/pdf-to-odp/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: ODP
otherformats: PPT SWF PPS XAML POWERPOINT POTM PPTM POTX OTP PPSM PPSX POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to ODP via .NET" h2=".NET API to Export PDF to ODP on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a powerful package of File Format Automation APIs that makes it easy to Render PDF to ODP in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the PDF file format to PPTX. The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to ODP. 

The PDF Processing API, Aspose.PDF for .NET, is a comprehensive library of classes and methods that allow developers to create, read, edit, and convert PDF documents. It provides a wide range of features such as document manipulation, text extraction, document conversion, and more. With this API, developers can easily convert PDF files to other popular file formats such as PPTX, HTML, XPS, and more. 

The Presentation Processing API, Aspose.Slides for .NET, is a comprehensive library of classes and methods that allow developers to create, read, edit, and convert presentation documents. It provides a wide range of features such as document manipulation, text extraction, document conversion, and more. With this API, developers can easily convert PPTX files to other popular file formats such as ODP, HTML, XPS, and more. 

By using the powerful File Format Automation APIs of Aspose.Total for .NET, developers can easily Render PDF to ODP in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the PDF file format to PPTX. The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to ODP. This makes it easy for developers to quickly and easily convert PDF files to ODP.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PDF to ODP" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to ODP format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Odp` as SaveFormat
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
// call save method while passing SaveFormat.Odp
presentation.Save("output.odp", SaveFormat.Odp);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from PDF File via .NET" %}}
While converting PDF to ODP, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a PDF file’s XMP metadata. To get a PDF file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input PDF file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
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

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}