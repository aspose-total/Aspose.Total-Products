---
title: C++ API to Convert TEX to ODP  
description: Convert TEX to ODP via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/tex-to-odp/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: ODP
otherformats: POTX OTP PPS POT POTM PPSM PPT PPSX XAML PPTM SWF POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render TEX to ODP within C++ Applications" h2="Convert TEX to ODP within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

If you are a C++ developer looking to add the ability to convert TEX to ODP inside your C++ applications, then you need to convert TEX to PPTX and then PPTX to ODP. This is because TEX and ODP are two different file formats and cannot be directly converted.

<h2>How Aspose.Total Helps for TEX to ODP Conversion</h2>

Aspose.Total for C++ is a suite of APIs that can help you to easily and quickly convert TEX to ODP. It includes two APIs, Aspose.PDF for C++ and Aspose.Slides for C++. Aspose.PDF for C++ can be used to export TEX to PPTX and Aspose.Slides for C++ can be used to convert PPTX to ODP. Both APIs are available as part of the Aspose.Total for C++ package.

Using Aspose.Total for C++, you can easily and quickly convert TEX to ODP in two simple steps. First, you can use Aspose.PDF for C++ to export TEX to PPTX. Secondly, you can use Aspose.Slides for C++ to convert PPTX to ODP. Both APIs are available as part of the Aspose.Total for C++ package.

The Aspose.Total for C++ package is a comprehensive suite of APIs that can help you to easily and quickly convert TEX to ODP. It includes two APIs, Aspose.PDF for C++ and Aspose.Slides for C++. Aspose.PDF for C++ can be used to export TEX to PPTX and Aspose.Slides for C++ can be used to convert PPTX to ODP. The APIs are easy to use and can help you to quickly and easily convert TEX to ODP in two simple steps.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export TEX to ODP" %}}
1. Open TEX file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert TEX to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to ODP format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Odp` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load TEX file with an instance of Document class
auto doc = MakeObject<Document>(u"template.tex");
// save TEX as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Odp format
prs->Save(u"output.odp", Aspose::Slides::Export::SaveFormat::Odp);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of TEX Document via C++" %}}
In the process of rendering TEX to ODP, you can open a password protected TEX and also change its password. In order to change the password of a TEX file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing TEX Document
auto doc = MakeObject<Document>(L"input.tex", L"owner");
// change password of TEX Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in ODP File via C++" %}}
After converting TEX to ODP, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a ODP file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a ODP file
auto pres = System::MakeObject<Presentation>("output.odp");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.odp", SaveFormat::Odp);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}