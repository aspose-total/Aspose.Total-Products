---
title: 通過 C++ 將 JSON 格式轉換為 FLATOPC
description: C++ API t0 在不使用 Microsoft Word 的情況下將 JSON 解析為 FLATOPC

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: FLATOPC
otherformats: ODT PCL DOT WORD PS OTT RTF EPUB DOC MOBI CHM DOTX WORDML DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C++ 將 JSON 格式轉換為 FLATOPC" h2="在 C++ 應用程序中將 JSON 解析為 FLATOPC，無需使用 Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
通過使用 [Aspose.Total for C++](https://products.aspose.com/total/cpp/)，您可以通過兩個簡單的步驟在您的 C++ 應用程序中將 JSON 解析為 FLATOPC。首先，通過使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)，您可以將 JSON 導出為 PDF。之後，通過使用 [Aspose.Words for C++](https://products.aspose.com/words/cppp/)，您可以將 PDF 轉換為 FLATOPC。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 C++ 中將 JSON 格式轉換為 FLATOPC" %}}
1. 創建一個新的 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 對象並從文件中讀取有效的 JSON 數據
2. 使用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 方法將 JSON 保存為 PDF
3. 使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 類加載 PDF 文檔
4. 使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 方法將文檔保存為 FLATOPC 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
通過 Visual Studio 的包管理器控制台安裝 ```Install-Package Aspose.Total.Cpp```。

或者，從 [下載](https://downloads.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="在 C++ 中設置佈局並將 JSON 格式轉換為 FLATOPC" %}}
在將 JSON 解析為 FLATOPC 時，您還可以通過使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 類加載 JSON 來設置行和列的大小。如果您需要為工作表中的所有行設置相同的行高，您可以使用 [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) 集合的方法。同樣，要為工作表中的所有列設置相同的列寬，請使用 ICells 集合的 [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) 方法。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 C++ 中將 JSON 格式轉換為帶有水印的 FLATOPC" %}}
使用 API，您還可以將 JSON 解析為帶有水印的 FLATOPC。為了給您的 FLATOPC 文檔添加水印，您可以先將 JSON 轉換為 PDF 並為其添加水印。為了添加水印，使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 類加載新創建的 PDF 文件，為文本水印設置不同的屬性，
調用 SetText 方法並傳遞 TextWatermarkOptions 的水印文本和對象。添加水印後，您可以將文檔保存到 FLATOPC。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-odt/" name="JSON 至 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-pcl/" name="JSON 至 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-dot/" name="JSON 至 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-word/" name="JSON 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-ps/" name="JSON 至 PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-ott/" name="JSON 至 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-rtf/" name="JSON 至 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-epub/" name="JSON 至 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-doc/" name="JSON 至 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-mobi/" name="JSON 至 MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-flatopc/" name="JSON 至 FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-dotx/" name="JSON 至 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-wordml/" name="JSON 至 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/json-to-docm/" name="JSON 至 DOCM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}