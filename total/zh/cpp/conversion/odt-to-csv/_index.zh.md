---
title: 在 C++ 中将 ODT 转换为 CSV 或使用免费的在线转换器
description: 无需使用 Microsoft Word 或 Microsoft Excel 即可将 ODT 转换为 CSV 的 C++ API 或在线应用程序 或在线。在集成代码之前快速测试免费的 POT 到 CSV 在线转换器。

family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: CSV
otherformats: EXCEL FODS XLTX TSV XLAM ODS XLT XLSX SXC XLS XLSB DIF XLTM XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="将 ODT 转换为 CSV 的 C++ API 或在线应用程序" h2="通过 C++ 将 ODT 导出为 CSV，无需使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以在 C++ 应用程序中轻松包含 ODT 到 CSV 的转换功能。通过使用功能丰富、功能强大且易于使用的文档操作和转换 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)，您可以将 ODT 导出为 HTML。之后，通过使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)，您可以将 HTML 转换为 CSV。这两个 API 都属于 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="将 ODT 转换为 CSV 的 C++ API 或在线应用程序" %}}
1. 用[Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)类参考打开ODT文件
2. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string_saveformat) 成员函数将 ODT 转换为 HTML
3. 使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 类参考加载 HTML 文档
4. 使用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) 成员函数将文档保存为 CSV 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://releases.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 访问 ODT 文档属性" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) 还允许您访问 ODT 文件的文档属性，并让您在转换过程之前做出明智的决定。要访问文档属性，您可以使用 [BuiltInOdtumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_odtument_properties) 获取内置属性和 [CustomOdtumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_odtument_properties)来获取自定义属性。以下代码示例演示如何枚举文档中的所有内置和自定义属性。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-odtument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 将 CSV 文件保存到流" %}}
将 ODT 转换为 CSV 后，[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) 使您能够将文档保存为流式传输。要将文件保存到流中，请创建 MemoryStream 或 FileStream 对象，然后通过调用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 将文件保存到该流对象中对象的 [保存](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) 方法。调用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) 方法。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}