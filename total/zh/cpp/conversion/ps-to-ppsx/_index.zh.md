---
title: C++ API 将 PS 转换为 PPSX
description: 通过 C++ 将 PS 转换为 PPSX，无需使用 Microsoft Word 或 Adobe Acrobat Reader
url: /zh/cpp/conversion/ps-to-ppsx/
family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: PPSX
otherformats: OTP POTX PPTM POT PPSM XAML POTM PPT ODP SWF POWERPOINT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 C++ 应用程序中将 PS 渲染到 PPSX" h2="在您的 C++ 应用程序中将 PS 转换为 PPSX，而无需使用 Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
您是一名 C++ 开发人员，希望在您的 C++ 应用程序中添加集成 PS 到 PPSX 转换功能吗？您可以通过两个简单的步骤来完成。您可以使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 将 PS 导出到 PPTX。其次，通过使用[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)，您可以将PPTX转换为PPSX。这两个 API 都属于 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于将 PS 导出为 PPSX 的 C++ API" %}}
1.使用[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)类参考打开PS文件
2. 使用[Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)方法函数将PS转换为PPTX
3.使用[Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)类参考加载PPTX文档
4. 使用 [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 成员函数将文档保存为 PPSX 格式，并将 `Ppsx` 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://downloads.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PS file with an instance of Document class
auto doc = MakeObject<Document>(u"template.ps");
// save PS as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppsx format
prs->Save(u"output.ppsx", Aspose::Slides::Export::SaveFormat::Ppsx);  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 更改 PS 文档的密码" %}}
在将 PS 渲染为 PPSX 的过程中，您可以打开受密码保护的 PS 并更改其密码。要更改 PS 文件的密码，您必须知道该文档的所有者密码。您可以通过指定所有者密码并使用 ChangePasswords 方法更改密码来使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 加载受密码保护的 PDF 文档。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PS Document
auto doc = MakeObject<Document>(L"input.ps", L"owner");
// change password of PS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 在 PPSX 文件中添加来自 Web 的图像" %}}
将 PS 转换为 PPSX 后，您还可以将 Web 中的图像添加到输出文档中。 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 支持对以下流行格式的图像进行操作：JPEG、PNG、BMP、GIF 等。您可以将计算机上的一个或多个图像添加到演示文稿的幻灯片中。此 C++ 示例代码向您展示如何将图像添加到 PPSX 文件
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPSX file
auto pres = System::MakeObject<Presentation>("output.ppsx");
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
pres->Save(u"updated.ppsx", SaveFormat::Ppsx);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-otp/" name="PS 至 OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-potx/" name="PS 至 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-pptm/" name="PS 至 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-pot/" name="PS 至 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-ppsm/" name="PS 至 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-xaml/" name="PS 至 XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-potm/" name="PS 至 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-ppt/" name="PS 至 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-ppsx/" name="PS 至 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-swf/" name="PS 至 SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-powerpoint/" name="PS 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ps-to-pps/" name="PS 至 PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}