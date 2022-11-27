---
title: 使用 .NET 更新 Excel 文件 

description: 使用基於 C# .NET 的應用程序，無需安裝 Microsoft Office 即可編輯 Microsoft Excel XLSX、XLS、CSV 文檔。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 .NET 更新 Excel 文檔" h2="在基於 .NET 的應用程序中修改 Microsoft Excel XLSX、XLS 文件，而無需安裝 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}
組織通常會通過公司軟件更新存儲在 excel 文件中的數據，例如學生數據、患者記錄和倉庫物品清單等。 [Aspose.Total for .NET](https://products.aspose.com/total/net/) API 提供使用軟件修改電子表格的功能。 程序員只需編寫幾行 API 代碼就可以通過修改功能增強軟件。 作為 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 包的一部分的 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API 使這個修改過程變得容易。 下面是更新Excel文件的過程。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="使用 .NET 更新 Excel 文檔" %}}

[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API 提供了處理 Excel 電子表格加載的工作簿類。 過程很簡單。 通過提供源文件作為參數來創建 [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) 對象。 通過使用 [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/) 方法提供其索引來訪問相關工作表。 使用[PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/)方法修改訪問單元格中的內容，最後調用save()方法保存文檔。

{{% blocks/products/pf/feature-page-code h3=".NET 代碼 - 更新 Excel 文檔" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="更新">}}