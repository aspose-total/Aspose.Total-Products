---
title: C++ API to Convert MHTML to OTP  
description: Convert MHTML to OTP via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/mhtml-to-otp/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: OTP
otherformats: PPSM PPSX POT POTM PPS POTX SWF POWERPOINT XAML ODP PPT PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render MHTML to OTP within C++ Applications" h2="Convert MHTML to OTP within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert MHTML to OTP?</h2>

MHTML (MIME HTML) is a web page archive format used to save web pages for offline viewing. It is a combination of HTML code and resources such as images, audio, and video. On the other hand, OTP (OpenDocument Presentation Template) is an open standard for electronic documents. It is used to create presentations and is supported by many applications. Therefore, it is necessary to convert MHTML to OTP in order to make the web page content available in a format that can be used by multiple applications.

<h2>How Aspose.Total Helps for MHTML to OTP Conversion?</h2>

Aspose.Total for C++ is a comprehensive package of APIs that enables developers to create, manipulate, and convert documents in various formats. It includes Aspose.PDF for C++ and Aspose.Slides for C++, which can be used to convert MHTML to OTP. To do this, firstly, you can export MHTML to PPTX by using Aspose.PDF for C++. Secondly, by using Aspose.Slides for C++, you can convert PPTX to OTP. Both APIs come under Aspose.Total for C++ package. Therefore, developers can easily integrate MHTML to OTP conversion feature inside their C++ applications by using Aspose.Total for C++.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export MHTML to OTP" %}}
1. Open MHTML file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert MHTML to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to OTP format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Otp` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load MHTML file with an instance of Document class
auto doc = MakeObject<Document>(u"template.mhtml");
// save MHTML as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Otp format
prs->Save(u"output.otp", Aspose::Slides::Export::SaveFormat::Otp);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of MHTML Document via C++" %}}
In the process of rendering MHTML to OTP, you can open a password protected MHTML and also change its password. In order to change the password of a MHTML file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing MHTML Document
auto doc = MakeObject<Document>(L"input.mhtml", L"owner");
// change password of MHTML Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in OTP File via C++" %}}
After converting MHTML to OTP, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a OTP file
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