---
title: 在 C++ 中將 DOC 轉換為 JSON 格式
description: 在 C++ 中將 DOC 導出為 JSON，而不使用 Microsoft Excel 或 Word

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C++ 將 DOC 轉換為 JSON 格式" h2="通過 C++ 將 DOC 導出為 JSON，無需使用 Microsoft<sup>&reg;</sup> Word 或 Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
通過使用 [Aspose.Total for C++](https://products.aspose.com/total/cpp/)，您可以在 C++ 應用程序中將 DOC 轉換為 JSON 格式。首先，通過使用 [Aspose.Words for C++](https://products.aspose.com/words/cpp/)，您可以將 DOC 導出為 HTML。之後，通過使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)，您可以將 HTML 轉換為 JSON 格式。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通過 C++ 將 DOC 轉換為 JSON 格式" %}}
1. 用[Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)類參考打開DOC文件
2. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 成員函數將 DOC 轉換為 HTML
3. 使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 類參考加載 HTML 文檔
4. 使用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 成員函數將文檔保存為 JSON 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
通過 Visual Studio 的包管理器控制台安裝 ```Install-Package Aspose.Total.Cpp```。

或者，從 [下載](https://releases.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 將受保護的 DOC 轉換為 JSON 格式" %}}
使用 API，您還可以打開受密碼保護的文檔。如果您的輸入 DOC 文檔受密碼保護，則您無法在不使用密碼的情況下將其轉換為 JSON 格式。為此，請使用接受 LoadOptions 對象的特殊構造函數重載。此對象包含 Password 屬性，該屬性指定密碼字符串。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}