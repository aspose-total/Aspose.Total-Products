---
title: C++ API to Convert PDF to PPSM  
description: Convert PDF to PPSM via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/pdf-to-ppsm/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: PPSM
otherformats: PPSX POWERPOINT SWF OTP ODP POT POTX POTM PPT XAML PPTM PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF to PPSM within C++ Applications" h2="Convert PDF to PPSM within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert PDF to PPSM?</h2>

PDF to PPSM conversion is a useful feature for C++ developers who are looking to integrate PDF to PPSM conversion feature inside their C++ applications. PPSM is a Microsoft PowerPoint Show file format which is used to store presentations. It is a compressed version of PPTX file format and is used to store presentations with animations, transitions, and other effects.

<h2>How Aspose.Total helps for PDF to PPSM Conversion?</h2>

Aspose.Total for C++ is a comprehensive package of APIs which helps developers to build powerful applications. It includes two APIs, Aspose.PDF for C++ and Aspose.Slides for C++, which can be used to export PDF to PPTX and convert PPTX to PPSM respectively. 

To export PDF to PPTX, developers can use Aspose.PDF for C++ API. It provides a wide range of features to manipulate PDF documents. It can be used to convert PDF to PPTX, extract text, images, and other content from PDF documents.

Once the PDF is converted to PPTX, developers can use Aspose.Slides for C++ API to convert PPTX to PPSM. It provides a wide range of features to manipulate PowerPoint presentations. It can be used to convert PPTX to PPSM, extract text, images, and other content from PowerPoint presentations.

In conclusion, Aspose.Total for C++ is a comprehensive package of APIs which helps developers to build powerful applications. It includes two APIs, Aspose.PDF for C++ and Aspose.Slides for C++, which can be used to export PDF to PPTX and convert PPTX to PPSM respectively. This makes it easy for C++ developers to integrate PDF to PPSM conversion feature inside their C++ applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export PDF to PPSM" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert PDF to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to PPSM format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Ppsm` as SaveFormat
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
// save the presentation as Ppsm format
prs->Save(u"output.ppsm", Aspose::Slides::Export::SaveFormat::Ppsm);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of PDF Document via C++" %}}
In the process of rendering PDF to PPSM, you can open a password protected PDF and also change its password. In order to change the password of a PDF file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
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

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in PPSM File via C++" %}}
After converting PDF to PPSM, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a PPSM file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a PPSM file
auto pres = System::MakeObject<Presentation>("output.ppsm");
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
pres->Save(u"updated.ppsm", SaveFormat::Ppsm);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}