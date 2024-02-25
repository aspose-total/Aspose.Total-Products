---
title: C++ API to Convert PDF to PPS  
description: Convert PDF to PPS via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/pdf-to-pps/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: PPS
otherformats: PPT SWF PPSM POT PPTM XAML OTP POTX POTM ODP POWERPOINT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to PPS within C++ Applications" h2="Convert PDF to PPS within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

Are you a C++ developer looking to add a PDF to PPS conversion feature to your C++ applications? PDF to PPS conversion is a useful tool for many C++ developers, as it allows them to easily convert PDF documents into the PPS format. This can be useful for a variety of purposes, such as creating presentations, sharing documents, or archiving documents.

<h2>How Aspose.Total Helps for PDF to PPS Conversion</h2>

Fortunately, Aspose.Total for C++ makes it easy to integrate PDF to PPS conversion into your C++ applications. Aspose.Total is a comprehensive suite of APIs that provides developers with the tools they need to create, manipulate, and convert a variety of document formats. It includes two APIs that are specifically designed for PDF to PPS conversion: Aspose.PDF for C++ and Aspose.Slides for C++.

Using Aspose.PDF for C++, you can easily export PDF documents to the PPTX format. Aspose.Slides for C++ then allows you to convert the PPTX documents to the PPS format. Both of these APIs are included in the Aspose.Total for C++ package, so you can easily access them with a single purchase.

In summary, Aspose.Total for C++ makes it easy to integrate PDF to PPS conversion into your C++ applications. With just two simple steps, you can export PDF documents to the PPTX format and then convert them to the PPS format. Aspose.Total for C++ provides you with the tools you need to make the process quick and easy.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export PDF to PPS" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert PDF to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to PPS format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Pps` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load PDF file with an instance of Document class
auto doc = MakeObject<Document>(u"template.pdf");
// save PDF as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pps format
prs->Save(u"output.pps", Aspose::Slides::Export::SaveFormat::Pps);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of PDF Document via C++" %}}
In the process of rendering PDF to PPS, you can open a password protected PDF and also change its password. In order to change the password of a PDF file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing PDF Document
auto doc = MakeObject<Document>(L"input.pdf", L"owner");
// change password of PDF Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in PPS File via C++" %}}
After converting PDF to PPS, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a PPS file
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