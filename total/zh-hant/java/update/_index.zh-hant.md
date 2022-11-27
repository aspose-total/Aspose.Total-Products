---
title: 使用 Java 更新 Excel 文件 

description: 無需在基於 Java 的應用程序中安裝 Microsoft Office 即可編輯 Microsoft Excel XLSX、XLS、CSV 文檔。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Java 更新 Excel 文件" h2="在基於 Java 的應用程序中修改 Microsoft Excel XLSX、XLS 文件，而無需安裝 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}
組織通常會通過公司軟件更新存儲在 excel 文件中的數據，例如學生數據、患者記錄和倉庫物品清單等。 [Aspose.Total for Java](https://products.aspose.com/total/java/) API 提供使用他們自己的軟件修改電子表格的功能。 程序員只需編寫幾行 API 代碼就可以通過修改功能增強軟件。 作為 [Aspose.Total for Java](https://products.aspose.com/total/java/) 包的一部分的 [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API 使這個修改過程變得容易。 下面是更新Excel文件的過程。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Java 更新 Excel 文檔" %}}

[Aspose.Cells for Java](https://products.aspose.com/cells/java/) API 提供了處理 Excel 電子表格加載的 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類。 過程很簡單。 通過提供源文件作為參數來創建 Workbook 類對象。 使用 [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)) 方法訪問相關工作表和相關單元格。 使用[getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)方法修改訪問單元格中的內容，最後調用save()方法保存文檔。

{{% blocks/products/pf/feature-page-code h3="Java 代碼 - 更新 Excel 文檔" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="更新">}}