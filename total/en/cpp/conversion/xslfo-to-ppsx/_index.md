---
title: C++ API to Convert XSLFO to PPSX  
description: Convert XSLFO to PPSX via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/xslfo-to-ppsx/
family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPSX
otherformats: PPSM POT POTM PPTM XAML POWERPOINT POTX OTP PPS PPT ODP SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XSLFO to PPSX within C++ Applications" h2="Convert XSLFO to PPSX within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert XSLFO to PPSX</h2>

C++ developers often need to integrate XSLFO to PPSX conversion feature inside their applications. XSLFO (XSL Formatting Objects) is a markup language for XML document formatting which is most commonly used to generate PDF documents. PPSX is a Microsoft PowerPoint Open XML Slide Show file which is used to store slides created using Microsoft PowerPoint. Converting XSLFO to PPSX allows users to view the content of the XSLFO document in the form of a presentation.

<h2>How Aspose.Total Helps for XSLFO to PPSX Conversion</h2>

Aspose.Total for C++ is a comprehensive package of APIs that helps developers to create, manipulate and convert various file formats. It includes two APIs, Aspose.PDF for C++ and Aspose.Slides for C++, which can be used to convert XSLFO to PPSX. 

The first step is to export XSLFO to PPTX by using Aspose.PDF for C++. This API provides a wide range of features to create, read, edit and convert PDF documents. It also allows developers to convert PDF documents to various other file formats, including PPTX.

The second step is to convert PPTX to PPSX by using Aspose.Slides for C++. This API provides a wide range of features to create, read, edit and convert presentations. It also allows developers to convert presentations to various other file formats, including PPSX.

In conclusion, Aspose.Total for C++ is an ideal package for C++ developers who need to integrate XSLFO to PPSX conversion feature inside their applications. It provides two APIs, Aspose.PDF for C++ and Aspose.Slides for C++, which can be used to convert XSLFO to PPSX in two simple steps.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export XSLFO to PPSX" %}}
1. Open XSLFO file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert XSLFO to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to PPSX format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Ppsx` as SaveFormat
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
// save the presentation as Ppsx format
prs->Save(u"output.ppsx", Aspose::Slides::Export::SaveFormat::Ppsx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of XSLFO Document via C++" %}}
In the process of rendering XSLFO to PPSX, you can open a password protected XSLFO and also change its password. In order to change the password of a XSLFO file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
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

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in PPSX File via C++" %}}
After converting XSLFO to PPSX, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a PPSX file
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

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}