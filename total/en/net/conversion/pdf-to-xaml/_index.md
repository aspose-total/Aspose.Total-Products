---
title: Export PDF to XAML via C# API
description: .NET API to Convert PDF to XAML without using Microsoft Word
url_ignore: /net/conversion/pdf-to-xaml/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: XAML
otherformats: POWERPOINT POT ODP POTX SWF PPSM PPSX PPT POTM PPS PPTM OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to XAML via .NET" h2=".NET API to Export PDF to XAML on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a powerful package of File Format Automation APIs that makes it easy to render PDF to XAML in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the PDF file format to PPTX. The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to XAML. 

The PDF Processing API, Aspose.PDF for .NET, is a comprehensive library that enables developers to create, read, edit, and convert PDF documents. It provides a wide range of features such as text extraction, document manipulation, and image extraction. It also supports the conversion of PDF documents to other popular file formats such as HTML, XPS, and PPTX. 

The Presentation Processing API, Aspose.Slides for .NET, is a powerful library that enables developers to create, read, edit, and convert presentation documents. It provides a wide range of features such as text extraction, document manipulation, and image extraction. It also supports the conversion of presentation documents to other popular file formats such as HTML, XPS, and XAML. 

Using Aspose.Total for .NET, developers can easily render PDF to XAML in two simple steps. The first step is to use the PDF Processing API, Aspose.PDF for .NET, to transform the PDF file format to PPTX. The second step is to use the Presentation Processing API, Aspose.Slides for .NET, to convert the PPTX to XAML. This powerful package of File Format Automation APIs makes it easy to render PDF to XAML quickly and efficiently.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert PDF to XAML" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert PDF to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to XAML format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Xaml` as SaveFormat
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
// call save method while passing SaveFormat.Xaml
presentation.Save("output.xaml", SaveFormat.Xaml);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from PDF File via .NET" %}}
While converting PDF to XAML, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a PDF file’s XMP metadata. To get a PDF file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input PDF file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
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