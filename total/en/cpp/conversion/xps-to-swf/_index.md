---
title: C++ API to Convert XPS to SWF  
description: Convert XPS to SWF via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/xps-to-swf/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: SWF
otherformats: OTP PPS ODP PPSX POTM POWERPOINT PPT PPTM PPSM POTX POT XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS to SWF within C++ Applications" h2="Convert XPS to SWF within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert XPS to SWF?</h2>

XPS (XML Paper Specification) is a document format developed by Microsoft. It is used to store documents in a fixed layout format. It is similar to PDF format but it is not as popular as PDF. SWF (Small Web Format) is a vector-based file format used for multimedia, vector graphics, and ActionScript. It is used to create interactive animations, games, and applications. SWF files are widely used on the web and are supported by most web browsers.

Therefore, if you are a C++ developer and want to add XPS to SWF conversion feature inside your C++ applications, you need to convert XPS to SWF.

<h2>How Aspose.Total helps for XPS to SWF Conversion?</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that enables developers to create, manipulate, convert, and render documents, images, and other file formats. It includes APIs for PDF, Slides, Words, Cells, and other file formats.

Using Aspose.Total for C++, you can easily convert XPS to SWF in two simple steps. First, you can export XPS to PPTX by using Aspose.PDF for C++. Secondly, by using Aspose.Slides for C++, you can convert PPTX to SWF. Both APIs come under Aspose.Total for C++ package.

Aspose.PDF for C++ is a powerful PDF manipulation API that enables developers to create, read, edit, and convert PDF documents. It supports a wide range of features such as document conversion, text extraction, image extraction, document signing, and more.

Aspose.Slides for C++ is a powerful presentation manipulation API that enables developers to create, read, edit, and convert presentations. It supports a wide range of features such as document conversion, text extraction, image extraction, document signing, and more.

Therefore, Aspose.Total for C++ is the perfect solution for C++ developers who want to add XPS to SWF conversion feature inside their C++ applications. It is easy to use, reliable, and cost-effective.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export XPS to SWF" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert XPS to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to SWF format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Swf` as SaveFormat
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
// save the presentation as Swf format
prs->Save(u"output.swf", Aspose::Slides::Export::SaveFormat::Swf);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of XPS Document via C++" %}}
In the process of rendering XPS to SWF, you can open a password protected XPS and also change its password. In order to change the password of a XPS file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
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

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in SWF File via C++" %}}
After converting XPS to SWF, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a SWF file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a SWF file
auto pres = System::MakeObject<Presentation>("output.swf");
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
pres->Save(u"updated.swf", SaveFormat::Swf);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}