---
title: C++ API to Convert CGM to POWERPOINT  
description: Convert CGM to POWERPOINT via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/cgm-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: POWERPOINT
otherformats: OTP POTX ODP POT PPT XAML SWF PPSM PPS PPSX PPTM POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render CGM to POWERPOINT within C++ Applications" h2="Convert CGM to POWERPOINT within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert CGM to PowerPoint?</h2>

CGM (Computer Graphics Metafile) is a vector graphics format used for storing and exchanging graphics data. It is widely used in the engineering and technical fields for creating technical drawings and illustrations. On the other hand, PowerPoint is a popular presentation software used for creating presentations. It is used for creating slideshows, presentations, and other visual aids. Therefore, it is important to convert CGM to PowerPoint in order to make the data more accessible and easier to share.

<h2>How Aspose.Total Helps for CGM to PowerPoint Conversion?</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that enables developers to create, manipulate, and convert various file formats. It includes APIs for PDF, Slides, and other file formats. With Aspose.Total for C++, developers can easily integrate CGM to PowerPoint conversion feature inside their C++ applications.

To export CGM to PPTX, developers can use Aspose.PDF for C++. It is a powerful PDF manipulation API that enables developers to create, read, and edit PDF documents. It also supports converting PDF documents to other file formats, including PPTX.

Once the CGM file is converted to PPTX, developers can use Aspose.Slides for C++ to convert PPTX to PowerPoint. It is a powerful presentation manipulation API that enables developers to create, read, and edit presentations. It also supports converting presentations to other file formats, including PowerPoint.

Therefore, developers can easily integrate CGM to PowerPoint conversion feature inside their C++ applications by using Aspose.Total for C++. It is a comprehensive suite of APIs that enables developers to create, manipulate, and convert various file formats. It includes APIs for PDF, Slides, and other file formats. With Aspose.Total for C++, developers can easily export CGM to PPTX and then convert PPTX to PowerPoint.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export CGM to POWERPOINT" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert CGM to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to PPT format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Ppt` as SaveFormat
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
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of CGM Document via C++" %}}
In the process of rendering CGM to POWERPOINT, you can open a password protected CGM and also change its password. In order to change the password of a CGM file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
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

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in POWERPOINT File via C++" %}}
After converting CGM to POWERPOINT, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a POWERPOINT file
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