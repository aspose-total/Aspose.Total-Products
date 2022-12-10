---
title: 使用 C++ 更新 XLSB 文件
description: 在不使用 Microsoft Excel 的情況下在 C++ 應用程序中修改 XLSB 文檔.
family: total
platformtag: C++
feature: update
informat: XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C++ 更新 XLSB 文件" h2="無需安裝 Microsoft Office<sup>&reg;</sup>，即可通過基於 C++ 的應用程序修改 XLSB 電子表格。" >}}

{{% blocks/products/pf/feature-page-summary %}}

對於試圖在 C++ 應用程序中更新 XLSB 文件的程序員, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API 可以幫助自動化更新過程。 它是處理多種格式（包括 Microsoft Excel 文檔）的不同 C++ 庫的完整包。 作為 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包的一部分的 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API 使這個修改過程變得容易。 更新 XLSB 文檔的過程很簡單，首先訪問工作表，然後使用 C++ 在 excel 中更新單元格值。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 C++ 中更新 XLSB 文件" %}}

- 使用 [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) 加載 XLSB 文件
- 使用 GetIWorksheets()->GetObjectByIndex(0) 訪問相關 [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet)，使用 GetICells()->GetObjectByIndex 訪問相關單元格
- 使用 PutValue 方法在訪問的單元格中插入新數據
- 通過將文件以路徑作為參數傳遞，使用 Save 方法將文件保存為 .xlsb 文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="修改要求" %}}

- XLSB修改，Windows和Linux系統遵循[系統要求](https://docs.aspose.com/cells/cpp/system-requirements/) 
- 從命令行安裝為```nuget install Aspose.Total.Cpp```
- 或者通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp```
- 或者，從 [下載](https://releases.aspose.com/cells/cpp) 獲取 ZIP 文件中的脫機 MSI 安裝程序或 DLL

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="代碼 - 在 C++ 中更新 XLSB 文件" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他修改選項" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/update/xls/" name="更新 XLS 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/update/xlsx/" name="更新 XLSX 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/update/csv/" name="更新 CSV 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/update/xlsb/" name="更新 XLSB 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/update/xlsm/" name="調整 XLSM 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/update/xlt/" name="更新 XLT 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/update/xltx/" name="更新 XLTX 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/update/xltm/" name="更新 XLTM 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/update/tsv/" name="更新 TSV 文件" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}