---
title: 将 PPT 转换为 DOTM 的 C++ API
description: 在 C++ 应用程序中将 PPT 导出为 DOTM
url: /zh/cpp/conversion/ppt-to-dotm/
family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: DOTM
otherformats: DOC WORD DOT RTF TEXT WORDML DOTX OTT FLATOPC ODT DOCX DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="将 PPT 渲染为 DOTM 的 C++ API" h2="在 C++ 应用程序中将 PPT 导出为 DOTM，无需任何 Microsoft PowerPoint 或 Word 依赖项" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) 是完整的 C++ 文件格式自动化库包。通过使用 pacakge 中可用的 API 的丰富功能，我们可以轻松地将 PowerPoint PPT 转换为 Word DOTM。为了执行转换，您可以首先使用 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API 将 PPT 转换为 HTML。之后，通过使用功能丰富的文字处理 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)，您可以将 HTML 转换为 DOTM。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="将 PPT 转换为 DOTM 的 C++ API" %}}
1. 使用 [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 类参考加载 PPT 文件
2. 使用 [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 成员函数将 PPT 渲染为 HTML 并将 Html 设置为 SaveFormat
3. 使用 [Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument) 类引用加载转换后的 HTML 文件
4. 使用[Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string)成员函数将文档保存为DOTM格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://downloads.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
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
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-dotm/" name="PPT 至 DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-word/" name="PPT 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-dot/" name="PPT 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-rtf/" name="PPT 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-text/" name="PPT 至 TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-wordml/" name="PPT 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-dotx/" name="PPT 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-ott/" name="PPT 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-flatopc/" name="PPT 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-odt/" name="PPT 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-dotmx/" name="PPT 至 DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/ppt-to-dotmm/" name="PPT 至 DOTMM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}