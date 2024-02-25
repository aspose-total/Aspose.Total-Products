---
title: C++ API to Convert MD to PPT  
description: Convert MD to PPT via C++ without using Microsoft Word or Adobe Acrobat Reader
url_ignore: /cpp/conversion/md-to-ppt/
family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: PPT
otherformats: XAML PPSX POTM SWF ODP PPTM POWERPOINT POTX PPS OTP POT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render MD to PPT within C++ Applications" h2="Convert MD to PPT within your C++ Applications without using Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert MD to PPT?</h2>

Markdown (MD) is a lightweight markup language used for formatting text documents. It is widely used for creating web content, such as blog posts, articles, and documentation. On the other hand, PowerPoint (PPT) is a popular presentation format used for creating slideshows. It is used for creating professional-looking presentations for business, educational, and other purposes. Therefore, it is often necessary to convert MD to PPT in order to create a professional-looking presentation.

<h2>How Aspose.Total Helps for MD to PPT Conversion?</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that enables developers to create, manipulate, and convert various file formats. It includes APIs for PDF, Slides, and other file formats. With Aspose.Total for C++, developers can easily integrate MD to PPT conversion feature inside their C++ applications.

The process of converting MD to PPT involves two steps. First, developers can export MD to PPTX by using Aspose.PDF for C++. Secondly, by using Aspose.Slides for C++, developers can convert PPTX to PPT. Both APIs come under Aspose.Total for C++ package.

Aspose.PDF for C++ is a powerful PDF manipulation API that enables developers to create, read, edit, and convert PDF documents. It supports a wide range of features, such as text extraction, document splitting, page manipulation, and more. Aspose.Slides for C++ is a powerful presentation API that enables developers to create, read, edit, and convert presentations. It supports a wide range of features, such as text formatting, slide manipulation, animation, and more.

By using Aspose.Total for C++, developers can easily integrate MD to PPT conversion feature inside their C++ applications. It is a comprehensive suite of APIs that enables developers to create, manipulate, and convert various file formats. It includes APIs for PDF, Slides, and other file formats. With Aspose.Total for C++, developers can easily export MD to PPTX and then convert PPTX to PPT.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Export MD to PPT" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert MD to PPTX by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) method function
3. Load PPTX document by using [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference 
4. Save the document to PPT format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) member function and set `Ppt` as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load MD file with an instance of Document class
auto doc = MakeObject<Document>(u"template.md");
// save MD as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of MD Document via C++" %}}
In the process of rendering MD to PPT, you can open a password protected MD and also change its password. In order to change the password of a MD file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing MD Document
auto doc = MakeObject<Document>(L"input.md", L"owner");
// change password of MD Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Add Images From Web in PPT File via C++" %}}
After converting MD to PPT, you can also add images from web to your output document. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) supports operations with images in these popular formats: JPEG, PNG, BMP, GIF, and others. You can add one or several images on your computer onto a slide in a presentation. This sample code in C++ shows you how to add an image to a PPT file
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate a Presentation object that represents a PPT file
auto pres = System::MakeObject<Presentation>("output.ppt");
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
pres->Save(u"updated.ppt", SaveFormat::Ppt);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}