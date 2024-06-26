---
title: 在 C++ 中将 WORD 转换为 JSON 格式
description: 在 C++ 中将 WORD 导出为 JSON，而不使用 Microsoft Excel 或 Word

family: total
platformtag: cpp
feature: conversion
informat: WORD
outformat: JSON
otherformats: SXC XLSX XLS DIF XLSB XLT XLAM TSV XLTM XLSM EXCEL XLTX FODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 C++ 将 WORD 转换为 JSON 格式" h2="通过 C++ 将 WORD 导出为 JSON，无需使用 Microsoft<sup>&reg;</sup> Word 或 Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for C++](https://products.aspose.com/total/cpp/)，您可以在 C++ 应用程序中将 WORD 转换为 JSON 格式。首先，通过使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/)，您可以将 WORD 导出为 HTML。之后，通过使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)，您可以将 HTML 转换为 JSON 格式。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 将 WORD 转换为 JSON 格式" %}}
1. 用[Wordument](https://reference.aspose.com/words/cpp/class/aspose.words.wordument)类参考打开WORD文件
2. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordument#save_string_saveformat) 成员函数将 WORD 转换为 HTML
3. 使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 类参考加载 HTML 文档
4. 使用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 成员函数将文档保存为 JSON 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
通过 Visual Studio 的包管理器控制台安装 ```Install-Package Aspose.Total.Cpp```。

或者，从 [下载](https://releases.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 将受保护的 WORD 转换为 JSON 格式" %}}
使用 API，您还可以打开受密码保护的文档。如果您的输入 WORD 文档受密码保护，则您无法在不使用密码的情况下将其转换为 JSON 格式。为此，请使用接受 LoadOptions 对象的特殊构造函数重载。此对象包含 Password 属性，该属性指定密码字符串。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}