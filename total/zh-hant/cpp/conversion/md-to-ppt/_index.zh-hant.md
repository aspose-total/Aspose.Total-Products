---
title: C++ API 將 MD 轉換為 PPT
description: 通過 C++ 將 MD 轉換為 PPT，無需使用 Microsoft Word 或 Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: PPT
otherformats: XAML PPSX POTM SWF ODP PPTM POWERPOINT POTX PPS OTP POT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 C++ 應用程序中將 MD 渲染到 PPT" h2="在您的 C++ 應用程序中將 MD 轉換為 PPT，而無需使用 Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
您是一名 C++ 開發人員，希望在您的 C++ 應用程序中添加集成 MD 到 PPT 轉換功能嗎？您可以通過兩個簡單的步驟來完成。您可以使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 將 MD 導出到 PPTX。其次，通過使用[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)，您可以將PPTX轉換為PPT。這兩個 API 都屬於 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="將 MD 導出為 PPT 的 C++ API" %}}
1.使用[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)類參考打開MD文件
2. 使用[Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)方法函數將MD轉換為PPTX
3.使用[Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)類參考加載PPTX文檔
4. 使用 [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 成員函數將文檔保存為 PPT 格式，並將 `Ppt` 設置為 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，從 [下載](https://downloads.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
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

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 更改 MD 文檔的密碼" %}}
在將 MD 渲染為 PPT 的過程中，您可以打開受密碼保護的 MD 並更改其密碼。要更改 MD 文件的密碼，您必須知道該文檔的所有者密碼。您可以通過指定所有者密碼並使用 ChangePasswords 方法更改密碼來使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 加載受密碼保護的 PDF 文檔。
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

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 在 PPT 文件中添加來自 Web 的圖像" %}}
將 MD 轉換為 PPT 後，您還可以將 Web 中的圖像添加到輸出文檔中。 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 支持對以下流行格式的圖像進行操作：JPEG、PNG、BMP、GIF 等。您可以將計算機上的一個或多個圖像添加到演示文稿的幻燈片中。此 C++ 示例代碼向您展示如何將圖像添加到 PPT 文件
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
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-xaml/" name="MD 至 XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-ppsx/" name="MD 至 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-potm/" name="MD 至 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-swf/" name="MD 至 SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-ppt/" name="MD 至 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-pptm/" name="MD 至 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-powerpoint/" name="MD 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-potx/" name="MD 至 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-pps/" name="MD 至 PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-otp/" name="MD 至 OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-pot/" name="MD 至 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/md-to-ppsm/" name="MD 至 PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}