---
title: C++ API to Convert TEX to PPSX  
description: Convert TEX to PPSX via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/tex-to-ppsx/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: PPSX
otherformats: PPTM SWF PPSM POT POWERPOINT ODP XAML OTP PPS PPT POTM POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render TEX to PPSX within C++ Applications" h2="Convert TEX to PPSX within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

If you are a C++ developer, you may need to integrate the feature of TEX to PPSX conversion inside your C++ applications. TEX is a plain text file format for representing a document and PPSX is a Microsoft PowerPoint Open XML Presentation format. Converting TEX to PPSX can help you to create presentations from the documents.

<h2>How Aspose.Total helps for tex to ppsx conversion</h2>

Aspose.Total for C++ is a comprehensive package of APIs that can help you to export TEX to PPTX and then convert PPTX to PPSX. It includes [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) and [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/). Aspose.PDF for C++ can help you to export TEX to PPTX and Aspose.Slides for C++ can help you to convert PPTX to PPSX.

The process of TEX to PPSX conversion is quite simple. First, you need to export TEX to PPTX by using Aspose.PDF for C++. Secondly, you can convert PPTX to PPSX by using Aspose.Slides for C++. Both APIs come under Aspose.Total for C++ package.

Aspose.Total for C++ is a powerful package of APIs that can help you to export TEX to PPTX and then convert PPTX to PPSX. It includes Aspose.PDF for C++ and Aspose.Slides for C++. Aspose.PDF for C++ can help you to export TEX to PPTX and Aspose.Slides for C++ can help you to convert PPTX to PPSX. The process of TEX to PPSX conversion is quite simple and can be done in two simple steps. Aspose.Total for C++ is a comprehensive package of APIs that can help you to integrate the feature of TEX to PPSX conversion inside your C++ applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export TEX to PPSX" %}}
1. Open TEX file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert TEX to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to PPSX format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Ppsx` as SaveFormat
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
// save the presentation as Ppsx format
prs->Save(u"output.ppsx", Aspose::Slides::Export::SaveFormat::Ppsx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of TEX Document via C++" %}}
In the process of rendering TEX to PPSX, you can open a password protected TEX and also change its password. In order to change the password of a TEX file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
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

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in PPSX File via C++" %}}
After converting TEX to PPSX, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a PPSX file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a PPSX file
auto pres = System::MakeObject<Presentation>("output.ppsx");
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
pres->Save(u"updated.ppsx", SaveFormat::Ppsx);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}