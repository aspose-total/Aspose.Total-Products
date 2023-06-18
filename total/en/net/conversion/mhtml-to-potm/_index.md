---
title: Export MHTML to POTM via C# API
description: .NET API to Convert MHTML to POTM without using Microsoft Word
url_ignore: /net/conversion/mhtml-to-potm/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: POTM
otherformats: SWF PPT ODP OTP PPS PPSX POT PPTM XAML POTX POWERPOINT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render MHTML to POTM via .NET" h2=".NET API to Export MHTML to POTM on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.Total for .NET is a powerful package of File Format Automation APIs that enables you to easily render MHTML to POTM in two simple steps. The first step involves using the PDF Processing API, Aspose.PDF for .NET, to transform the MHTML file format into PPTX. This API provides a wide range of features that allow you to manipulate PDF documents in various ways, such as creating, editing, converting, and merging PDFs. 

The second step involves using the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to POTM. This API provides a comprehensive set of features that enable you to create, edit, and convert presentations in various formats, such as PPT, PPTX, POT, POTX, PPS, PPSX, and PPTM. It also allows you to manipulate slides, shapes, text, and images in presentations. 

By using Aspose.Total for .NET, you can quickly and easily render MHTML to POTM in two simple steps. The PDF Processing API, Aspose.PDF for .NET, is used to transform the MHTML file format into PPTX, and the Presentation Processing API, Aspose.Slides for .NET, is used to convert the PPTX to POTM. Both APIs provide a wide range of features that enable you to manipulate documents and presentations in various ways.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert MHTML to POTM" %}}
1. Open MHTML file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert MHTML to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to POTM format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Potm` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load MHTML file with an instance of Document class
Document document = new Document("input.mhtml");
// save MHTML as a PPTX 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 
// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Potm
presentation.Save("output.potm", SaveFormat.Potm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from MHTML File via .NET" %}}
While converting MHTML to POTM, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a MHTML file’s XMP metadata. To get a MHTML file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input MHTML file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
{{% blocks/products/pf/feature-page-code %}}
```cs// open MHTML document
Document doc = new Document("input.mhtml");
// get MHTML XMP properties
Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Read Only POTM File via .NET" %}}
 By using [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, you can further enhance the features of your conversion application. One of the feature can be to create your output file read only to increase security. The API allows you to set your POTM file to Read-Only, which means users (after they open the presentation) see the Read-Only recommendation.
{{% blocks/products/pf/feature-page-code %}}
```cs// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// make POTM read only
presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Potm
presentation.Save("output.potm", SaveFormat.Potm);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}