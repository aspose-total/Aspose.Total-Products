---
title: 使用 Python 更新 CSV 文件
description: 在 Python 应用程序中修改 CSV 文档而不使用 Microsoft Excel。 

family: total
platformtag: Python
feature: update
informat: CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Python 更新 CSV 文件" h2="通过您的 Python 应用程序修改 CSV 电子表格，而无需安装 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于开发人员，谁正在尝试通过 Python 应用程序更新 CSV 文件？ [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API 可以帮助自动化更新过程。 它是处理不同格式（包括 Microsoft Excel 文件）的各种 API 的完整包。 作为 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) 包一部分的 ASPOSE.CELL API 使这个修改过程变得容易。 以下是更新 CSV 文档的过程。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中更新 CSV 文件" %}}

- 创建以源 CSV 文件为参数的新 [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) 类对象
- 使用 [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) 方法访问相关工作表
- 使用 [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) 方法在访问的单元格中插入新数据
- 通过将带有路径的文件作为参数传递，使用 save() 方法将文件保存为 .csv 文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="修改要求" %}}

- 对于 CSV 修改，直接从 PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/)) 引用项目内的 API
- 或者使用下面的 pip 命令```pip install aspose.cells``` 
- 此外，从 [下载](https://releases.aspose.com/cells/python-java) 部分下载 API 包

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="代码 - 在 Python 中更新 CSV 文件" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}