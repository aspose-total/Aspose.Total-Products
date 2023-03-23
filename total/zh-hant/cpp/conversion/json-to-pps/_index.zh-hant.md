---
title: 通過 C++ 將 JSON 格式轉換為 PPS
description: 在不使用 Microsoft PowerPoint 的情況下，在 C++ 中將 JSON 解析為 PPS

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPS
otherformats: PPSX PPSM PPTM POWERPOINT POTM POTX PPT ODP OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C++ 將 JSON 格式轉換為 PPS" h2="無需使用 Microsoft<sup>&reg;</sup> PowerPoint 即可將 JSON 解析為 PPS 的 C++ API" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通過兩個簡單的步驟在任何 C++ 應用程序中將 JSON 轉換為 PPS。首先，通過使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)，您可以將 JSON 解析為 PPTX。之後，通過使用 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)，您可以將 PPTX 轉換為 PPS。這兩個 API 都屬於 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通過 C++ 將 JSON 格式轉換為 PPS" %}}
1. 創建一個新的 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 對象並從文件中讀取有效的 JSON 數據
2. 使用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 方法將 JSON 保存為 PPTX
3. 使用 [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 類加載 PPTX 文檔
4. 使用[Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)方法將文檔保存為PPS格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
通過 Visual Studio 的包管理器控制台安裝 ```Install-Package Aspose.Total.Cpp```。

或者，從 [下載](https://releases.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 設置佈局並將 JSON 格式轉換為 PPS" %}}
在將 JSON 解析為 PPS 時，您還可以通過使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 類加載 JSON 來設置行和列的大小。如果您需要為工作表中的所有行設置相同的行高，您可以使用 [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) 集合的方法。同樣，要為工作表中的所有列設置相同的列寬，請使用 ICells 集合的 [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) 方法。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 C++ 中將 JSON 格式轉換為帶有水印的 PPS" %}}
使用 API，您還可以將 JSON 轉換為帶水印的 PPS。為了給你的PPS文檔添加水印，你可以先將JSON解析為PPTX並添加水印。為了添加水印，使用 [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) 類加載新創建的 PPTX 文件，獲取第一張幻燈片，添加Rectangle 類型的 AutoShape，將 TextFrame 添加到 Rectangle，為文本框架創建 Paragraph 對象，為段落創建 Portion 對象，使用 set_Text() 添加水印，可以將文檔保存到 PPS。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}