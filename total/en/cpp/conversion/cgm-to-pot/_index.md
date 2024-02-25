---
title: C++ API to Convert CGM to POT  
description: Convert CGM to POT via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/cgm-to-pot/
family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: POT
otherformats: SWF POWERPOINT POTM PPSM OTP XAML PPTM PPSX PPS POTX ODP PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render CGM to POT within C++ Applications" h2="Convert CGM to POT within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

CGM (Computer Graphics Metafile) is a vector graphics format used for storing and exchanging graphics data. It is widely used in the engineering and technical drawing fields. POT (PowerPoint Template) is a file format used by Microsoft PowerPoint for storing slide templates. It is used to create a consistent design for presentations. Therefore, it is important to convert CGM to POT for creating a consistent design for presentations.

<h2>How Aspose.Total helps for cgm to pot conversion</h2>

Aspose.Total for C++ is a suite of APIs that provides developers with the ability to create, manipulate, convert, and render various file formats. It includes APIs for PDF, Slides, Words, and Cells. It also includes APIs for manipulating images, barcodes, and OCR. With Aspose.Total for C++, developers can easily convert CGM to POT in two simple steps. 

The first step is to export CGM to PPTX by using Aspose.PDF for C++. Aspose.PDF for C++ is a powerful PDF manipulation API that enables developers to create, read, and edit PDF documents. It also allows developers to convert PDF documents to other file formats, such as PPTX. 

The second step is to convert PPTX to POT by using Aspose.Slides for C++. Aspose.Slides for C++ is a powerful presentation manipulation API that enables developers to create, read, and edit presentations. It also allows developers to convert presentations to other file formats, such as POT. 

Therefore, with Aspose.Total for C++, developers can easily convert CGM to POT in two simple steps. It is a powerful suite of APIs that provides developers with the ability to create, manipulate, convert, and render various file formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export CGM to POT" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert CGM to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to POT format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Pot` as SaveFormat
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
// save the presentation as Pot format
prs->Save(u"output.pot", Aspose::Slides::Export::SaveFormat::Pot);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of CGM Document via C++" %}}
In the process of rendering CGM to POT, you can open a password protected CGM and also change its password. In order to change the password of a CGM file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
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

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in POT File via C++" %}}
After converting CGM to POT, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a POT file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a POT file
auto pres = System::MakeObject<Presentation>("output.pot");
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
pres->Save(u"updated.pot", SaveFormat::Pot);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}