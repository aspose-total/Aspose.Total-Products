---
title: C++ API to Convert SVG to ODP  
description: Convert SVG to ODP via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/svg-to-odp/
family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: ODP
otherformats: PPSM POTM PPT POWERPOINT SWF PPS POT XAML OTP PPTM POTX PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render SVG to ODP within C++ Applications" h2="Convert SVG to ODP within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

If you are a C++ developer looking to add the ability to convert SVG to ODP inside your C++ applications, you can do it in two simple steps. Aspose.PDF for C++ is a powerful API that can be used to export SVG to PPTX. Aspose.Slides for C++ is another API that can be used to convert PPTX to ODP. Both of these APIs are part of the Aspose.Total for C++ package.

Aspose.PDF for C++ is a feature-rich API that can be used to create, read, edit, and convert PDF documents. It also provides the ability to export SVG to PPTX. It supports a wide range of features such as text extraction, image extraction, page manipulation, and more. It also supports a variety of file formats such as PDF, XPS, HTML, and more.

Aspose.Slides for C++ is a powerful API that can be used to create, read, edit, and convert presentations. It also provides the ability to convert PPTX to ODP. It supports a wide range of features such as text extraction, image extraction, page manipulation, and more. It also supports a variety of file formats such as PPTX, PPT, ODP, and more.

Both of these APIs are part of the Aspose.Total for C++ package. This package provides a comprehensive set of APIs for C++ developers. It includes APIs for PDF, Slides, Words, Cells, and more. It also provides a range of features such as text extraction, image extraction, page manipulation, and more. With Aspose.Total for C++, you can easily add the ability to convert SVG to ODP inside your C++ applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export SVG to ODP" %}}
1. Open SVG file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert SVG to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to ODP format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Odp` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load SVG file with an instance of Document class
auto doc = MakeObject<Document>(u"template.svg");
// save SVG as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Odp format
prs->Save(u"output.odp", Aspose::Slides::Export::SaveFormat::Odp);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of SVG Document via C++" %}}
In the process of rendering SVG to ODP, you can open a password protected SVG and also change its password. In order to change the password of a SVG file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing SVG Document
auto doc = MakeObject<Document>(L"input.svg", L"owner");
// change password of SVG Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in ODP File via C++" %}}
After converting SVG to ODP, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a ODP file
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