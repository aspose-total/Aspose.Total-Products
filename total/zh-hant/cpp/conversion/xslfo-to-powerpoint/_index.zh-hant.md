---
title: C++ API 將 XSLFO 轉換為 POWERPOINT
description: 通過 C++ 將 XSLFO 轉換為 POWERPOINT，無需使用 Microsoft Word 或 Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPT
otherformats: SWF POT PPT POTM PPTM PPS PPSM ODP POTX XAML PPSX OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 C++ 應用程序中將 XSLFO 渲染到 POWERPOINT" h2="在您的 C++ 應用程序中將 XSLFO 轉換為 POWERPOINT，而無需使用 Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
您是一名 C++ 開發人員，希望在您的 C++ 應用程序中添加集成 XSLFO 到 POWERPOINT 轉換功能嗎？您可以通過兩個簡單的步驟來完成。您可以使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 將 XSLFO 導出到 PPTX。其次，通過使用[Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)，您可以將PPTX轉換為POWERPOINT。這兩個 API 都屬於 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="將 XSLFO 導出為 POWERPOINT 的 C++ API" %}}
1. 用[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)類參考打開XSLFO文件
2. 使用[Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)方法函數將XSLFO轉換為PPTX
3. 用[Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)類參考加載PPTX文檔
4. 使用 [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 成員函數將文檔保存為 POWERPOINT 格式，並將 `Powerpoint` 設置為 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp```。

或者，從 [下載](https://releases.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XSLFO file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xslfo");
// save XSLFO as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 更改 XSLFO 文檔的密碼" %}}
在將 XSLFO 渲染為 POWERPOINT 的過程中，您可以打開受密碼保護的 XSLFO 並更改其密碼。要更改 XSLFO 文件的密碼，您必須知道該文檔的所有者密碼。您可以通過指定所有者密碼並使用 ChangePasswords 方法更改密碼來使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 加載受密碼保護的 PDF 文檔。
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XSLFO Document
auto doc = MakeObject<Document>(L"input.xslfo", L"owner");
// change password of XSLFO Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 在 POWERPOINT 文件中添加來自 Web 的圖像" %}}
將 XSLFO 轉換為 POWERPOINT 後，您還可以將 Web 中的圖像添加到輸出文檔中。 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) 支持對以下流行格式的圖像進行操作：JPEG、PNG、BMP、GIF 等。您可以將計算機上的一個或多個圖像添加到演示文稿的幻燈片中。此 C++ 示例代碼向您展示如何將圖像添加到 POWERPOINT 文件
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
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}