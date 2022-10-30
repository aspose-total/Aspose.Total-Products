---
title: 使用 Python 創建和更新 Microsoft Excel 文件 
url: /zh-hant/python-java/create/
description: 無需安裝 Microsoft Office 即可創建 Microsoft Excel 工作表報告 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 創建 Excel 報表" h2="在 Python 應用程序中創建和更新 Microsoft Excel 電子表格 XLS、XLSX 文檔，而無需安裝 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) 是一個 Python API，用於在 Microsoft Excel 格式（包括 XLS 和 XLSX）中創建、讀取和寫入文檔。 此 API 是 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) 包的一部分。 此外，Develpors 可以輕鬆編寫代碼，用於在工作表中插入數據、圖像、圖表、數據透視表和許多其他功能。 Python API 還支持設置各種 [公式](https://docs.aspose.com/cells/python-java/supported-formula-functions/)、將文本轉換為列、智能標記和動態公式選項等功能。 以下是創建和修改電子表格的幾個示例代碼。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="如何使用 Python 創建 Excel 文件" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API 提供了處理文件創建的 Workbook 類。 過程很簡單。 創建 Workbook 類對象並通過提供其索引來訪問相關的 Worksheet。 使用 putValue 方法在訪問的單元格中添加內容，最後調用 save() 方法以特定名稱保存文檔。

{{% blocks/products/pf/feature-page-code h3="代碼 1 - 創建簡單的 Excel 文件" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="代碼 2 - 在 Microsoft Excel 文檔中插入圖像" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="如何使用 Python 更新 Microsoft Excel 文件" %}}

除了唯一的區別之外，創建和更新 Excel 文件的過程幾乎相同。 不同的是，在創建過程中會創建 Empty Workbook 對象，而在更新過程中，需要現有的 Excel 文件。 因此，將現有文件作為參數傳遞給 Workbook 類。 休息程序是一樣的

{{% blocks/products/pf/feature-page-code h3="代碼 3 - 更新 Microsoft Excel 文檔" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}