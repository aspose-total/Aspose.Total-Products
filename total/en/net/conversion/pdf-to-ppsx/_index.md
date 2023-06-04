---
title: Export PDF to PPSX via C# API
description: .NET API to Convert PDF to PPSX without using Microsoft Word
url_ignore: /net/conversion/pdf-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: PPSX
otherformats: ODP PPT POWERPOINT POT OTP POTX SWF PPTM PPS PPSM POTM XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to PPSX via .NET" h2=".NET API to Export PDF to PPSX on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a powerful package of File Format Automation APIs that makes it easy to render PDF to PPSX in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the PDF file format to PPTX. The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to PPSX. 

The PDF Processing API, Aspose.PDF for .NET, is a comprehensive library that enables developers to create, read, edit, and convert PDF documents in .NET applications. It provides a wide range of features, such as creating PDF documents from scratch, converting PDF documents to other formats, extracting text and images from PDF documents, and more. 

The Presentation Processing API, Aspose.Slides for .NET, is a comprehensive library that enables developers to create, read, edit, and convert presentation documents in .NET applications. It provides a wide range of features, such as creating presentations from scratch, converting presentations to other formats, extracting text and images from presentations, and more. 

Using Aspose.Total for .NET, developers can easily render PDF to PPSX in two simple steps. The PDF Processing API, Aspose.PDF for .NET, is used to transform the PDF file format to PPTX, and the Presentation Processing API, Aspose.Slides for .NET, is used to convert the PPTX to PPSX. This makes it easy for developers to quickly and easily convert PDF documents to PPSX.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PDF to PPSX" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to PPSX format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Ppsx` as SaveFormat
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
// call save method while passing SaveFormat.Ppsx
presentation.Save("output.ppsx", SaveFormat.Ppsx);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from PDF File via .NET" %}}
While converting PDF to PPSX, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a PDF file’s XMP metadata. To get a PDF file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input PDF file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
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
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}