---
title: 使用 C++ 更新 Excel 文件 

description: 使用基於 C++ 的應用程序無需安裝 Microsoft Office 即可編輯 Microsoft Excel XLSX、XLS、CSV 文檔。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C++ 更新 Excel 文檔" h2="在基於 C++ 的應用程序中修改 Microsoft Excel XLSX、XLS 文件，而無需安裝 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}
組織通常會通過公司軟件更新存儲在 excel 文件中的數據，例如學生數據、患者記錄和倉庫物品清單等。 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API 提供使用軟件修改電子表格的功能。 程序員只需編寫幾行 API 代碼就可以通過修改功能增強軟件。 作為 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包的一部分的 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API 使這個修改過程變得容易。 下面是更新Excel文件的過程。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="使用 C++ 更新 Excel 文檔" %}}

使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API，加載使用 [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) 的源文件。 使用 GetIWorksheets()->GetObjectByIndex(0) 訪問 [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet)，使用 GetICells()->GetObjectByIndex 訪問所需的單元格。 使用PutValue方式，修改被訪問單元格中的內容。 最後調用 save() 方法來保存文檔。

{{% blocks/products/pf/feature-page-code h3="C++ 代碼 - 更新 Excel 文檔" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="更新">}}