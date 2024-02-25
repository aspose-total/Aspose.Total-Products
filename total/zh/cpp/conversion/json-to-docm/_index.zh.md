---
title: 通过 C++ 将 JSON 格式转换为 DOCM
description: C++ API t0 在不使用 Microsoft Word 的情况下将 JSON 解析为 DOCM

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOCM
otherformats: OTT CHM PCL DOT PS DOTX ODT FLATOPC WORDML EPUB DOC WORD RTF MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 C++ 将 JSON 格式转换为 DOCM" h2="在 C++ 应用程序中将 JSON 解析为 DOCM，无需使用 Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for C++](https://products.aspose.com/total/cpp/)，您可以通过两个简单的步骤在您的 C++ 应用程序中将 JSON 解析为 DOCM。首先，通过使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)，您可以将 JSON 导出为 PDF。之后，通过使用 [Aspose.Words for C++](https://products.aspose.com/words/cppp/)，您可以将 PDF 转换为 DOCM。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 C++ 中将 JSON 格式转换为 DOCM" %}}
1. 创建一个新的 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 对象并从文件中读取有效的 JSON 数据
2. 使用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 方法将 JSON 保存为 PDF
3. 使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 类加载 PDF 文档
4. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 方法将文档保存为 DOCM 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
通过 Visual Studio 的包管理器控制台安装 ```Install-Package Aspose.Total.Cpp```。

或者，从 [下载](https://releases.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="在 C++ 中设置布局并将 JSON 格式转换为 DOCM" %}}
在将 JSON 解析为 DOCM 时，您还可以通过使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 类加载 JSON 来设置行和列的大小。如果您需要为工作表中的所有行设置相同的行高，您可以使用 [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) 集合的方法。同样，要为工作表中的所有列设置相同的列宽，请使用 ICells 集合的 [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) 方法。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 C++ 中将 JSON 格式转换为带有水印的 DOCM" %}}
使用 API，您还可以将 JSON 解析为带有水印的 DOCM。为了给您的 DOCM 文档添加水印，您可以先将 JSON 转换为 PDF 并为其添加水印。为了添加水印，使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 类加载新创建的 PDF 文件，为文本水印设置不同的属性，
调用 SetText 方法并传递 TextWatermarkOptions 的水印文本和对象。添加水印后，您可以将文档保存到 DOCM。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}