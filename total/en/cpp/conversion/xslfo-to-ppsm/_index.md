---
title: C++ API to Convert XSLFO to PPSM  
description: Convert XSLFO to PPSM via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/xslfo-to-ppsm/
family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPSM
otherformats: OTP POTX XAML ODP POTM POT PPSX PPS PPT SWF POWERPOINT PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XSLFO to PPSM within C++ Applications" h2="Convert XSLFO to PPSM within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert XSLFO to PPSM?</h2>

XSLFO (XSL Formatting Objects) is a markup language for XML document formatting which is used to define the layout of a document. It is used to describe the look and feel of a document. PPSM (PowerPoint Show) is a presentation file format used by Microsoft PowerPoint. It is used to store a presentation in a single file. Converting XSLFO to PPSM is beneficial for C++ developers as it allows them to integrate XSLFO to PPSM conversion feature inside their C++ applications.

<h2>How Aspose.Total Helps for XSLFO to PPSM Conversion?</h2>

Aspose.Total for C++ is a suite of APIs that provides a wide range of features for C++ developers. It includes Aspose.PDF for C++ and Aspose.Slides for C++. Aspose.PDF for C++ is a powerful PDF processing API that enables developers to export XSLFO to PPTX. Aspose.Slides for C++ is a powerful presentation processing API that enables developers to convert PPTX to PPSM. Both APIs come under Aspose.Total for C++ package. 

Therefore, C++ developers can easily integrate XSLFO to PPSM conversion feature inside their C++ applications by using Aspose.Total for C++. It provides a simple and efficient way to export XSLFO to PPTX and then convert PPTX to PPSM. Aspose.Total for C++ is a comprehensive suite of APIs that provides a wide range of features for C++ developers. It is a great choice for C++ developers who want to add XSLFO to PPSM conversion feature inside their C++ applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export XSLFO to PPSM" %}}
1. Open XSLFO file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert XSLFO to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to PPSM format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Ppsm` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load XSLFO file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xslfo");
// save XSLFO as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppsm format
prs->Save(u"output.ppsm", Aspose::Slides::Export::SaveFormat::Ppsm);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of XSLFO Document via C++" %}}
In the process of rendering XSLFO to PPSM, you can open a password protected XSLFO and also change its password. In order to change the password of a XSLFO file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing XSLFO Document
auto doc = MakeObject<Document>(L"input.xslfo", L"owner");
// change password of XSLFO Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in PPSM File via C++" %}}
After converting XSLFO to PPSM, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a PPSM file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a PPSM file
auto pres = System::MakeObject<Presentation>("output.ppsm");
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
pres->Save(u"updated.ppsm", SaveFormat::Ppsm);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}