---
title: 在 C++ 中將 DOTM 轉換為 XLTM
description: 無需使用 Microsoft Word 或 Microsoft Excel 即可將 DOTM 轉換為 XLTM 的 C++ API

family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: XLTM
otherformats: ODS XLS EXCEL XLAM XLSB XLT DIF SXC XLSX XLTX XLSM FODS CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="將 DOTM 轉換為 XLTM 的 C++ API" h2="通過 C++ 將 DOTM 導出為 XLTM，無需使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以在 C++ 應用程序中輕鬆包含 DOTM 到 XLTM 的轉換功能。通過使用功能豐富、功能強大且易於使用的文檔操作和轉換 API [Aspose.Words for C++](https://products.aspose.com/words/cpp/)，您可以將 DOTM 導出為 HTML。之後，通過使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)，您可以將 HTML 轉換為 XLTM。這兩個 API 都屬於 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="將 DOTM 轉換為 XLTM 的 C++ API" %}}
1.使用[Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument)類參考打開DOTM文件
2. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string_saveformat) 成員函數將 DOTM 轉換為 HTML
3. 使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 類參考加載 HTML 文檔
4. 使用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) 成員函數將文檔保存為 XLTM 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，從 [下載](https://downloads.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 訪問 DOTM 文檔屬性" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) 還允許您訪問 DOTM 文件的文檔屬性，並讓您在轉換過程之前做出明智的決定。要訪問文檔屬性，您可以使用 [BuiltInDotmumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_dotmument_properties) 來獲取內置屬性和 [CustomDotmumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_dotmument_properties)來獲取自定義屬性。以下代碼示例演示如何枚舉文檔中的所有內置和自定義屬性。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-dotmument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 將 XLTM 文件保存到流" %}}
將 DOTM 轉換為 XLTM 後，[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) 使您能夠將文檔保存為流式傳輸。要將文件保存到流中，請創建 MemoryStream 或 FileStream 對象，然後通過調用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 將文件保存到該流對像中對象的 [保存](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) 方法。調用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) 方法。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-ods/" name="DOTM 至 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-xls/" name="DOTM 至 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-excel/" name="DOTM 至 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-xlam/" name="DOTM 至 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-xlsb/" name="DOTM 至 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-xlt/" name="DOTM 至 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-dif/" name="DOTM 至 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-sxc/" name="DOTM 至 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-xlsx/" name="DOTM 至 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-xltx/" name="DOTM 至 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-xlsm/" name="DOTM 至 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-fods/" name="DOTM 至 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-xltm/" name="DOTM 至 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/dotm-to-tsv/" name="DOTM 至 TSV" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}