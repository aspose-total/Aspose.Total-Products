---
title: 使用 C++ 更新 Excel 文件 

description: 使用基于 C++ 的应用程序无需安装 Microsoft Office 即可编辑 Microsoft Excel XLSX、XLS、CSV 文档。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 C++ 更新 Excel 文档" h2="在基于 C++ 的应用程序中修改 Microsoft Excel XLSX、XLS 文件，而无需安装 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}
组织通常会通过公司软件更新存储在 excel 文件中的数据，例如学生数据、患者记录和仓库物品清单等。 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API 提供使用软件修改电子表格的功能。 程序员只需编写几行 API 代码就可以通过修改功能增强软件。 作为 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包的一部分的 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API 使这个修改过程变得容易。 下面是更新Excel文件的过程。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="使用 C++ 更新 Excel 文档" %}}

使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API，加载使用 [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) 的源文件。 使用 GetIWorksheets()->GetObjectByIndex(0) 访问 [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet)，使用 GetICells()->GetObjectByIndex 访问所需的单元格。 使用PutValue方式，修改被访问单元格中的内容。 最后调用 save() 方法来保存文档。

{{% blocks/products/pf/feature-page-code h3="C++ 代码 - 更新 Excel 文档" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="更新">}}