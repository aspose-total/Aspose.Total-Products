---
title: 在 Python 中创建 TSV
description: 在不使用 Microsoft Office 的情况下使用 Python 应用程序生成 TSV 文件。 

family: total
platformtag: Python
feature: create
informat: TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 创建 TSV" h2="通过您的 Python 应用程序生成 TSV，无需安装 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于开发人员，谁正在尝试通过 Python 应用程序创建 TSV 文件？ [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API 可以帮助自动化创建过程。 它是处理不同格式的各种 API 的完整包，包括 Microsoft Office 文件和图像。 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) 包中的 [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API 使这个生成过程变得简单。 下面是创建过程。 此外，开发人员可以轻松地增强应用程序来修改 TSV 文件。 使用 Python 更新 TSV 文件的过程是相同的，只是它在创建工作簿对象时需要现有文件作为参数。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中创建 TSV 文件" %}}

- 创建以 文件FormatType 作为参数的新 [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) 类对象
- 使用 [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) 方法获取所需 [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet) 的访问权限
- 使用 [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) 方法在访问的单元格中插入数据
- 通过传递带有路径的文件作为参数，使用 [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String)) 将文档保存为 .tsv 文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="创作要求" %}}

- 对于 TSV 生成，直接从 PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/)) 引用项目中的 API
- 或者使用以下 pip 命令```pip install aspose.cells``` 
- 此外，从 [downloads](https://releases.aspose.com/cells/python-java) 部分下载 API 包 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中创建 TSV" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}