---
title: C++ API to Convert PS to ODP  
description: Convert PS to ODP via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/ps-to-odp/
family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: ODP
otherformats: PPSM PPS POT PPT XAML POTX POWERPOINT PPTM OTP POTM PPSX SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PS to ODP within C++ Applications" h2="Convert PS to ODP within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert PS to ODP?</h2>

C++ developers often need to convert PostScript (PS) files to OpenDocument Presentation (ODP) format. This is because ODP is an open standard format that is supported by many applications, making it easier to share and collaborate on presentations.

<h2>How Aspose.Total Helps for PS to ODP Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that enables developers to easily integrate PS to ODP conversion into their C++ applications. The package includes two APIs: Aspose.PDF for C++ and Aspose.Slides for C++. 

Using Aspose.PDF for C++, developers can export PS files to PPTX format. Aspose.Slides for C++ then allows developers to convert the PPTX file to ODP format. This two-step process makes it easy to convert PS to ODP in C++ applications. 

Aspose.Total for C++ also provides a number of other features that make it easier to work with documents in C++ applications. It includes APIs for working with PDF, Word, Excel, PowerPoint, and other popular document formats. It also includes APIs for manipulating images, extracting text, and more. 

Overall, Aspose.Total for C++ is an ideal solution for C++ developers who need to integrate PS to ODP conversion into their applications. It provides a simple two-step process for converting PS to ODP, as well as a number of other features that make it easier to work with documents in C++ applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export PS to ODP" %}}
1. Open PS file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert PS to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to ODP format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Odp` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load PS file with an instance of Document class
auto doc = MakeObject<Document>(u"template.ps");
// save PS as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Odp format
prs->Save(u"output.odp", Aspose::Slides::Export::SaveFormat::Odp);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of PS Document via C++" %}}
In the process of rendering PS to ODP, you can open a password protected PS and also change its password. In order to change the password of a PS file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing PS Document
auto doc = MakeObject<Document>(L"input.ps", L"owner");
// change password of PS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in ODP File via C++" %}}
After converting PS to ODP, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a ODP file
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