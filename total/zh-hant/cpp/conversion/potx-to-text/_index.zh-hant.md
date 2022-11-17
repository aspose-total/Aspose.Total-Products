---
title: 將 POTX 轉換為 TEXT 的 C++ API
description: 在 C++ 應用程序中將 POTX 導出為 TEXT

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: TEXT
otherformats: DOCX DOTX FLATOPC WORDML ODT DOCM DOT DOC RTF WORD OTT DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="將 POTX 渲染為 TEXT 的 C++ API" h2="在 C++ 應用程序中將 POTX 導出為 TEXT，無需任何 Microsoft PowerPoint 或 Word 依賴項" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 是完整的 C++ 文件格式自動化庫包。通過使用 pacakge 中可用的 API 的豐富功能，我們可以輕鬆地將 PowerPoint POTX 轉換為 Word TEXT。為了執行轉換，您可以首先使用 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API 將 POTX 轉換為 HTML。之後，通過使用功能豐富的文字處理 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)，您可以將 HTML 轉換為 TEXT。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="將 POTX 轉換為 TEXT 的 C++ API" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 類參考加載 POTX 文件
2. 使用 [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 成員函數將 POTX 渲染為 HTML 並將 Html 設置為 SaveFormat
3. 使用 [Textument](https://reference.aspose.com/words/cpp/class/aspose.words.textument) 類引用加載轉換後的 HTML 文件
4. 使用[保存](https://reference.aspose.com/words/cpp/class/aspose.words.textument#save_string)成員函數將文檔保存為TEXT格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，從 [下載](https://downloads.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Textument
System::SharedPtr<Textument> text = System::MakeObject<Textument>(u"htmlOutput.html");
// save textument in TEXT format
text->Save(u"output.text"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-textx/" name="POTX 至 TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-dotx/" name="POTX 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-flatopc/" name="POTX 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-wordml/" name="POTX 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-odt/" name="POTX 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-textm/" name="POTX 至 TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-dot/" name="POTX 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-text/" name="POTX 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-rtf/" name="POTX 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-word/" name="POTX 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-ott/" name="POTX 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/potx-to-dotm/" name="POTX 至 DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}