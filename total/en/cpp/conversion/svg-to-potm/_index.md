---
title: C++ API to Convert SVG to POTM  
description: Convert SVG to POTM via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/svg-to-potm/
family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: POTM
otherformats: PPS PPSM POTX SWF PPSX POWERPOINT PPT ODP PPTM XAML OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render SVG to POTM within C++ Applications" h2="Convert SVG to POTM within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert SVG to POTM?</h2>

If you are a C++ developer looking to add a feature to your applications that allows for SVG to POTM conversion, then you are in the right place. SVG (Scalable Vector Graphics) is an XML-based vector image format for two-dimensional graphics with support for interactivity and animation. POTM (PowerPoint Open XML Macro-Enabled Presentation) is a file format used by Microsoft PowerPoint to store presentations that contain macros. Converting SVG to POTM allows you to use the vector graphics in your PowerPoint presentations.

<h2>How Aspose.Total Helps for SVG to POTM Conversion?</h2>

Aspose.Total for C++ is a package that contains all the APIs from Aspose for C++. It includes Aspose.PDF for C++ and Aspose.Slides for C++, which can be used to export SVG to PPTX and convert PPTX to POTM respectively. Aspose.PDF for C++ allows you to export SVG to PPTX in two simple steps. First, you need to load the SVG file and then save it as a PPTX file. Aspose.Slides for C++ can then be used to convert the PPTX file to POTM. The API provides a wide range of features that allow you to customize the output POTM file. You can add text, images, shapes, and other elements to the presentation. You can also apply various formatting options to the elements.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export SVG to POTM" %}}
1. Open SVG file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert SVG to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to POTM format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Potm` as SaveFormat
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
// save the presentation as Potm format
prs->Save(u"output.potm", Aspose::Slides::Export::SaveFormat::Potm);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of SVG Document via C++" %}}
In the process of rendering SVG to POTM, you can open a password protected SVG and also change its password. In order to change the password of a SVG file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
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

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in POTM File via C++" %}}
After converting SVG to POTM, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a POTM file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a POTM file
auto pres = System::MakeObject<Presentation>("output.potm");
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
pres->Save(u"updated.potm", SaveFormat::Potm);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}