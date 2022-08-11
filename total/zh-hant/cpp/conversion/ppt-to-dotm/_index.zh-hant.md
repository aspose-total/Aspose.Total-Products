---
title: 將 PPT 轉換為 DOTM 的 C++ API
description: 在 C++ 應用程序中將 PPT 導出為 DOTM
url: /zh-hant/cpp/conversion/ppt-to-dotm/
family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOTM
otherformats: DOC WORD DOT RTF TEXT WORDML DOTX OTT FLATOPC ODT DOCX DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="將 PPT 渲染為 DOTM 的 C++ API" h2="在 C++ 應用程序中將 PPT 導出為 DOTM，無需任何 Microsoft PowerPoint 或 Word 依賴項" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 是完整的 C++ 文件格式自動化庫包。通過使用 pacakge 中可用的 API 的豐富功能，我們可以輕鬆地將 PowerPoint PPT 轉換為 Word DOTM。為了執行轉換，您可以首先使用 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API 將 PPT 轉換為 HTML。之後，通過使用功能豐富的文字處理 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)，您可以將 HTML 轉換為 DOTM。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="將 PPT 轉換為 DOTM 的 C++ API" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 類參考加載 PPT 文件
2. 使用 [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 成員函數將 PPT 渲染為 HTML 並將 Html 設置為 SaveFormat
3. 使用 [Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument) 類引用加載轉換後的 HTML 文件
4. 使用[保存](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string)成員函數將文檔保存為DOTM格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，從 [下載](https://downloads.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppt");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotmument
System::SharedPtr<Dotmument> dotm = System::MakeObject<Dotmument>(u"htmlOutput.html");
// save dotmument in DOTM format
dotm->Save(u"output.dotm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-dotm/" name="PPT 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-word/" name="PPT 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-dot/" name="PPT 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-rtf/" name="PPT 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-text/" name="PPT 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-wordml/" name="PPT 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-dotx/" name="PPT 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-ott/" name="PPT 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-flatopc/" name="PPT 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-odt/" name="PPT 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-dotmx/" name="PPT 至 DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/ppt-to-dotmm/" name="PPT 至 DOTMM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}