---
title: 通过 C++ 将 JSON 格式转换为 PPT
description: 在不使用 Microsoft PowerPoint 的情况下，在 C++ 中将 JSON 解析为 PPT

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPT
otherformats: OTP PPSM PPSX POTM PPTM POT ODP PPS POWERPOINT POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 C++ 将 JSON 格式转换为 PPT" h2="无需使用 Microsoft<sup>&reg;</sup> PowerPoint 即可将 JSON 解析为 PPT 的 C++ API" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通过两个简单的步骤在任何 C++ 应用程序中将 JSON 转换为 PPT。首先，通过使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)，您可以将 JSON 解析为 PPTX。之后，通过使用 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)，您可以将 PPTX 转换为 PPT。这两个 API 都属于 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 将 JSON 格式转换为 PPT" %}}
1. 创建一个新的 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 对象并从文件中读取有效的 JSON 数据
2. 使用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 方法将 JSON 保存为 PPTX
3. 使用 [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 类加载 PPTX 文档
4. 使用[Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)方法将文档保存为PPT格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
通过 Visual Studio 的包管理器控制台安装 ```Install-Package Aspose.Total.Cpp```。

或者，从 [下载](https://releases.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 设置布局并将 JSON 格式转换为 PPT" %}}
在将 JSON 解析为 PPT 时，您还可以通过使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 类加载 JSON 来设置行和列的大小。如果您需要为工作表中的所有行设置相同的行高，您可以使用 [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) 集合的方法。同样，要为工作表中的所有列设置相同的列宽，请使用 ICells 集合的 [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) 方法。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 C++ 中将 JSON 格式转换为带有水印的 PPT" %}}
使用 API，您还可以将 JSON 转换为带水印的 PPT。为了给你的PPT文档添加水印，你可以先将JSON解析为PPTX并添加水印。为了添加水印，使用 [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 类加载新创建的 PPTX 文件，获取第一张幻灯片，添加Rectangle 类型的 AutoShape，将 TextFrame 添加到 Rectangle，为文本框架创建 Paragraph 对象，为段落创建 Portion 对象，使用 set_Text() 添加水印，可以将文档保存到 PPT。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}