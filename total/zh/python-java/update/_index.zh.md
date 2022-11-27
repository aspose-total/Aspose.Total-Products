---
title: 使用 Python 更新 Excel 文件 

description: 无需在 Python 应用程序中安装 Microsoft Office 即可编辑 Microsoft Excel XLSX、XLS、CSV 文档
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Python 更新 Excel 文档" h2="在 Python 应用程序中修改 Microsoft Excel XLSX、XLS 文件而无需安装 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}
组织通常会通过公司软件更新存储在 Excel 文件中的数据，例如学生数据、患者记录和仓库物品清单等。 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API 提供了通过软件修改电子表格的功能。 程序员可以通过集成 API 并编写几行代码来增强具有修改功能的软件。 作为 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) 包的一部分的 [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API 使这个修改过程变得容易。下面是更新Excel文件的过程。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Python 更新 Excel 文档" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API 提供了处理 Excel 电子表格加载的工作簿类。 过程很简单。 通过提供源文件作为参数来创建 [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) 类对象。 使用 [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) 方法通过提供其索引来访问相关的工作表。 调用[Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)方法修改被访问单元格中的内容，最后调用save()方法保存文档。

{{% blocks/products/pf/feature-page-code h3="Python - 更新 Excel 文档" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="更新">}}