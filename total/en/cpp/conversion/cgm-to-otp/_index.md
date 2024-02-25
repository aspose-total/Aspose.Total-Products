---
title: C++ API to Convert CGM to OTP  
description: Convert CGM to OTP via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/cgm-to-otp/
family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: OTP
otherformats: POTM PPTM ODP PPS PPSX PPT POT PPSM XAML POWERPOINT SWF POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render CGM to OTP within C++ Applications" h2="Convert CGM to OTP within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert CGM to OTP</h2>

CGM (Computer Graphics Metafile) is a vector graphics format used for storing and exchanging graphics data. It is widely used in the engineering and technical drawing fields. OTP (Open Text Protocol) is a text-based format used for exchanging text documents. It is used for exchanging documents between different applications. Converting CGM to OTP is necessary for exchanging graphics data between different applications.

<h2>How Aspose.Total Helps for CGM to OTP Conversion</h2>

Aspose.Total for C++ is a comprehensive package of APIs for developing applications in C++. It includes APIs for manipulating PDF, Slides, Words, and other file formats. It also includes APIs for manipulating images, barcodes, and other elements. With Aspose.Total for C++, developers can easily integrate CGM to OTP conversion feature inside their C++ applications.

To export CGM to PPTX, developers can use Aspose.PDF for C++. It is a powerful PDF manipulation API that enables developers to create, edit, and convert PDF documents. It also supports exporting CGM to PPTX.

To convert PPTX to OTP, developers can use Aspose.Slides for C++. It is a powerful presentation manipulation API that enables developers to create, edit, and convert presentations. It also supports converting PPTX to OTP.

By using Aspose.Total for C++, developers can easily integrate CGM to OTP conversion feature inside their C++ applications in two simple steps. They can export CGM to PPTX by using Aspose.PDF for C++ and then convert PPTX to OTP by using Aspose.Slides for C++.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export CGM to OTP" %}}
1. Open CGM file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert CGM to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to OTP format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Otp` as SaveFormat
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
// save the presentation as Otp format
prs->Save(u"output.otp", Aspose::Slides::Export::SaveFormat::Otp);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of CGM Document via C++" %}}
In the process of rendering CGM to OTP, you can open a password protected CGM and also change its password. In order to change the password of a CGM file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
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

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in OTP File via C++" %}}
After converting CGM to OTP, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a OTP file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a OTP file
auto pres = System::MakeObject<Presentation>("output.otp");
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
pres->Save(u"updated.otp", SaveFormat::Otp);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}