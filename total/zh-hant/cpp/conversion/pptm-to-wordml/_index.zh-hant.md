---
title: 將 PPTM 轉換為 WORDML 的 C++ API
description: 在 C++ 應用程序中將 PPTM 導出為 WORDML
url: /zh-hant/cpp/conversion/pptm-to-wordml/
family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: WORDML
otherformats: DOC DOTM DOCM DOT DOCX WORD FLATOPC TEXT ODT OTT RTF DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="將 PPTM 渲染為 WORDML 的 C++ API" h2="在 C++ 應用程序中將 PPTM 導出為 WORDML，無需任何 Microsoft PowerPoint 或 Word 依賴項" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 是完整的 C++ 文件格式自動化庫包。通過使用 pacakge 中可用的 API 的豐富功能，我們可以輕鬆地將 PowerPoint PPTM 轉換為 Word WORDML。為了執行轉換，您可以首先使用 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API 將 PPTM 轉換為 HTML。之後，通過使用功能豐富的文字處理 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)，您可以將 HTML 轉換為 WORDML。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="將 PPTM 轉換為 WORDML 的 C++ API" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 類參考加載 PPTM 文件
2. 使用 [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 成員函數將 PPTM 渲染為 HTML 並將 Html 設置為 SaveFormat
3. 使用 [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) 類引用加載轉換後的 HTML 文件
4. 使用[保存](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string)成員函數將文檔保存為WORDML格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，從 [下載](https://downloads.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Wordmlument
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"htmlOutput.html");
// save wordmlument in WORDML format
wordml->Save(u"output.wordml"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-wordml/" name="PPTM 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-dotm/" name="PPTM 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-wordmlm/" name="PPTM 至 WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-dot/" name="PPTM 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-wordmlx/" name="PPTM 至 WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-word/" name="PPTM 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-flatopc/" name="PPTM 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-text/" name="PPTM 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-odt/" name="PPTM 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-ott/" name="PPTM 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-rtf/" name="PPTM 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/pptm-to-dotx/" name="PPTM 至 DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}