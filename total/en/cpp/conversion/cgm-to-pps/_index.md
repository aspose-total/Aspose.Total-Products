---
title: C++ API to Convert CGM to PPS  
description: Convert CGM to PPS via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/cgm-to-pps/
family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: PPS
otherformats: PPSM PPTM ODP POWERPOINT SWF POT OTP XAML POTM PPSX POTX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render CGM to PPS within C++ Applications" h2="Convert CGM to PPS within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert CGM to PPS?</h2>

CGM (Computer Graphics Metafile) is a vector graphics format used for storing and exchanging graphics data. It is widely used in engineering and technical applications. On the other hand, PPS (PowerPoint Show) is a presentation format used by Microsoft PowerPoint. It is used to store slides in a single file. Therefore, if you want to use the CGM data in a PowerPoint presentation, you need to convert it to PPS format.

<h2>How Aspose.Total Helps for CGM to PPS Conversion?</h2>

If you are a C++ developer looking to integrate CGM to PPS conversion feature inside your C++ applications, you can do it in two simple steps. You can export CGM to PPTX by using [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Secondly, by using [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), you can convert PPTX to PPS. Both APIs come under [Aspose.Total for C++](https://products.aspose.com/total/cpp/) package.

Aspose.PDF for C++ is a powerful PDF manipulation API that enables you to create, read, edit, and convert PDF documents. It supports a wide range of features, including the ability to export CGM to PPTX. Aspose.Slides for C++ is a powerful presentation API that enables you to create, read, edit, and convert presentations. It supports a wide range of features, including the ability to convert PPTX to PPS.

Aspose.Total for C++ is a suite of APIs that includes Aspose.PDF for C++ and Aspose.Slides for C++. It enables you to create, read, edit, and convert documents and presentations. It also includes a wide range of features, including the ability to export CGM to PPTX and convert PPTX to PPS. With Aspose.Total for C++, you can easily integrate CGM to PPS conversion feature inside your C++ applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export CGM to PPS" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert CGM to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to PPS format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Pps` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load CGM file with an instance of Document class
auto doc = MakeObject<Document>(u"template.cgm");
// save CGM as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pps format
prs->Save(u"output.pps", Aspose::Slides::Export::SaveFormat::Pps);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of CGM Document via C++" %}}
In the process of rendering CGM to PPS, you can open a password protected CGM and also change its password. In order to change the password of a CGM file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing CGM Document
auto doc = MakeObject<Document>(L"input.cgm", L"owner");
// change password of CGM Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in PPS File via C++" %}}
After converting CGM to PPS, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a PPS file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a PPS file
auto pres = System::MakeObject<Presentation>("output.pps");
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
pres->Save(u"updated.pps", SaveFormat::Pps);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}