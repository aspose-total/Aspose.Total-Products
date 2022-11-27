---
title: 使用 Python 更新 Excel 文件 

description: 無需在 Python 應用程序中安裝 Microsoft Office 即可編輯 Microsoft Excel XLSX、XLS、CSV 文檔
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Python 更新 Excel 文檔" h2="在 Python 應用程序中修改 Microsoft Excel XLSX、XLS 文件而無需安裝 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}
組織通常會通過公司軟件更新存儲在 Excel 文件中的數據，例如學生數據、患者記錄和倉庫物品清單等。 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API 提供了通過軟件修改電子表格的功能。 程序員可以通過集成 API 並編寫幾行代碼來增強具有修改功能的軟件。 作為 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) 包的一部分的 [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API 使這個修改過程變得容易。下面是更新Excel文件的過程。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Python 更新 Excel 文檔" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API 提供了處理 Excel 電子表格加載的工作簿類。 過程很簡單。 通過提供源文件作為參數來創建 [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) 類對象。 使用 [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) 方法通過提供其索引來訪問相關的工作表。 調用[Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)方法修改被訪問單元格中的內容，最後調用save()方法保存文檔。

{{% blocks/products/pf/feature-page-code h3="Python - 更新 Excel 文檔" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="更新">}}