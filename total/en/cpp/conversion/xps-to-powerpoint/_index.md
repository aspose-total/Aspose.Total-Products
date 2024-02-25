---
title: C++ API to Convert XPS to POWERPOINT  
description: Convert XPS to POWERPOINT via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/xps-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: POWERPOINT
otherformats: SWF XAML PPTM PPSM PPT PPSX POTM OTP POT ODP POTX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS to POWERPOINT within C++ Applications" h2="Convert XPS to POWERPOINT within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert XPS to PowerPoint?</h2>

XPS (XML Paper Specification) is a document format developed by Microsoft which is used to store documents in a fixed layout. It is similar to PDF but has some advantages over it. XPS documents are more secure and can be easily edited. However, XPS documents are not compatible with PowerPoint, which is a popular presentation software. Therefore, it is necessary to convert XPS documents to PowerPoint in order to use them in presentations.

<h2>How Aspose.Total Helps for XPS to PowerPoint Conversion?</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that enables developers to easily integrate XPS to PowerPoint conversion feature inside their C++ applications. It includes two APIs, Aspose.PDF for C++ and Aspose.Slides for C++, which can be used to export XPS to PPTX and convert PPTX to PowerPoint respectively. Aspose.PDF for C++ allows developers to export XPS documents to PPTX format, while Aspose.Slides for C++ enables them to convert PPTX documents to PowerPoint. Both APIs are available as part of the Aspose.Total for C++ package. With the help of these APIs, developers can easily integrate XPS to PowerPoint conversion feature inside their C++ applications in just two simple steps.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export XPS to POWERPOINT" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert XPS to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to PPT format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Ppt` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load XPS file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xps");
// save XPS as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of XPS Document via C++" %}}
In the process of rendering XPS to POWERPOINT, you can open a password protected XPS and also change its password. In order to change the password of a XPS file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing XPS Document
auto doc = MakeObject<Document>(L"input.xps", L"owner");
// change password of XPS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in POWERPOINT File via C++" %}}
After converting XPS to POWERPOINT, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a POWERPOINT file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a POWERPOINT file
auto pres = System::MakeObject<Presentation>("output.powerpoint");
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
pres->Save(u"updated.powerpoint", SaveFormat::Ppt);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}