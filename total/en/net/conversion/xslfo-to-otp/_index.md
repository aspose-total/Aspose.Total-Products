---
title: Export XSLFO to OTP via C# API
description: .NET API to Convert XSLFO to OTP without using Microsoft Word
url_ignore: /net/conversion/xslfo-to-otp/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: OTP
otherformats: PPT SWF POTM PPSX PPS POTX POWERPOINT POT PPTM XAML ODP PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XSLFO to OTP via .NET" h2=".NET API to Export XSLFO to OTP on Windows, macOS, and Linux without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Using a package of powerful File Format Automation APIs [Aspose.Total for .NET](https://products.aspose.com/total/net/) you can easily Render XSLFO to OTP in two simple steps. By using PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), you can transform XSLFO file format to PPTX. After that, by using Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), you can convert PPTX to OTP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API to Convert XSLFO to OTP" %}}
1. Open XSLFO file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
2. Convert XSLFO to PPTX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
3. Load PPTX file by using [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) class 
4. Save the document to OTP format using [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) method and set `Otp` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load XSLFO file with an instance of Document class
Document document = new Document("input.xslfo");
// save XSLFO as a PPTX 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 
// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Otp
presentation.Save("output.otp", SaveFormat.Otp);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Get XMP Metadata from XSLFO File via .NET" %}}
While converting XSLFO to OTP, you might need extra XMP metadata information to prioritize your batch conversion process. For example you can get and sort your conversion documents based on creation date and process the documents accordingly. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) allows you to access a XSLFO file’s XMP metadata. To get a XSLFO file’s metadata, you can create a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) object and open the input XSLFO file. After that, you can get the file’s metadata using the [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) property.
{{% blocks/products/pf/feature-page-code %}}
```cs// open XSLFO document
Document doc = new Document("input.xslfo");
// get XSLFO XMP properties
Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Create Read Only OTP File via .NET" %}}
 By using [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API, you can further enhance the features of your conversion application. One of the feature can be to create your output file read only to increase security. The API allows you to set your OTP file to Read-Only, which means users (after they open the presentation) see the Read-Only recommendation.
{{% blocks/products/pf/feature-page-code %}}
```cs// load PPTX with an instance of Presentation
Presentation presentation = new Presentation("PptxOutput.pptx");
// make OTP read only
presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Otp
presentation.Save("output.otp", SaveFormat.Otp);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}