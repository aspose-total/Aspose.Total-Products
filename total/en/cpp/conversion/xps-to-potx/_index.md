---
title: C++ API to Convert XPS to POTX  
description: Convert XPS to POTX via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/xps-to-potx/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: POTX
otherformats: PPTM ODP PPS SWF POTM OTP POT POWERPOINT PPSX PPSM PPT XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS to POTX within C++ Applications" h2="Convert XPS to POTX within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

Are you a C++ developer looking to add a feature to integrate XPS to POTX conversion inside your C++ applications? XPS is a fixed-layout document format developed by Microsoft and is used to store documents in an XML-based format. POTX is a PowerPoint Open XML template file format used to store PowerPoint presentations. Converting XPS to POTX can help you create presentations with a consistent look and feel.

<h2>How Aspose.Total Helps for XPS to POTX Conversion</h2>

You can easily export XPS to PPTX by using Aspose.PDF for C++. It is a powerful PDF processing API that enables you to create, read, edit, and convert PDF documents. It also allows you to export XPS to PPTX format. Secondly, by using Aspose.Slides for C++, you can convert PPTX to POTX. It is a powerful presentation processing API that enables you to create, read, edit, and convert presentations. Both APIs come under Aspose.Total for C++ package. Aspose.Total for C++ is a suite of APIs that provides a comprehensive set of features for working with PDF, Word, Excel, PowerPoint, and other file formats. It allows you to create, read, edit, and convert documents and presentations in various formats. With Aspose.Total for C++, you can easily export XPS to POTX in two simple steps.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export XPS to POTX" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert XPS to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to POTX format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Potx` as SaveFormat
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
// save the presentation as Potx format
prs->Save(u"output.potx", Aspose::Slides::Export::SaveFormat::Potx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of XPS Document via C++" %}}
In the process of rendering XPS to POTX, you can open a password protected XPS and also change its password. In order to change the password of a XPS file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
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

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in POTX File via C++" %}}
After converting XPS to POTX, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a POTX file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a POTX file
auto pres = System::MakeObject<Presentation>("output.potx");
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
pres->Save(u"updated.potx", SaveFormat::Potx);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}