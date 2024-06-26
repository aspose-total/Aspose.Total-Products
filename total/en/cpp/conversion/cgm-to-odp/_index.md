---
title: C++ API to Convert CGM to ODP  
description: Convert CGM to ODP via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/cgm-to-odp/
family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: ODP
otherformats: PPSX POTM PPTM PPT PPSM POWERPOINT POTX OTP SWF POT XAML PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render CGM to ODP within C++ Applications" h2="Convert CGM to ODP within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert CGM to ODP?</h2>

CGM (Computer Graphics Metafile) is a vector graphics format that is used to store and exchange graphics data. It is widely used in engineering and technical applications. ODP (OpenDocument Presentation) is a file format used to store presentations. It is an open standard for electronic documents and is supported by many applications. Therefore, it is important to convert CGM to ODP for compatibility and portability.

<h2>How Aspose.Total Helps for CGM to ODP Conversion?</h2>

Aspose.Total for C++ is a suite of APIs that provides a comprehensive set of features for developing applications in C++. It includes APIs for manipulating PDF, Slides, Words, Cells, and Barcode. It also includes APIs for manipulating CGM files. With Aspose.Total for C++, you can easily convert CGM to ODP in two simple steps. 

First, you can export CGM to PPTX by using Aspose.PDF for C++. Aspose.PDF for C++ is a powerful PDF manipulation API that enables you to create, edit, and convert PDF documents. It also supports exporting CGM to PPTX. 

Secondly, you can convert PPTX to ODP by using Aspose.Slides for C++. Aspose.Slides for C++ is a powerful presentation manipulation API that enables you to create, edit, and convert presentations. It also supports converting PPTX to ODP. 

Therefore, with Aspose.Total for C++, you can easily integrate CGM to ODP conversion feature inside your C++ applications. It is a comprehensive suite of APIs that provides a comprehensive set of features for developing applications in C++.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export CGM to ODP" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert CGM to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to ODP format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Odp` as SaveFormat
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
// save the presentation as Odp format
prs->Save(u"output.odp", Aspose::Slides::Export::SaveFormat::Odp);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of CGM Document via C++" %}}
In the process of rendering CGM to ODP, you can open a password protected CGM and also change its password. In order to change the password of a CGM file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
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

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in ODP File via C++" %}}
After converting CGM to ODP, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a ODP file
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