---
title: 使用 Python 将 POTM 转换为 XLSB
description: 在不使用 Microsoft Office 的情况下在 Python 应用程序中将 POTM 转换为 XLSB 

family: total
platformtag: Python
feature: conversion
informat: POTM
outformat: XLSB
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Python 将 POTM 转换为 XLSB" h2="无需安装 Microsoft PowerPoint<sup>&reg;</sup> 或 Excel，即可在 Python 应用程序中将 POTM 转换为 XLSB" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于尝试在应用程序中添加 POTM 到 XLSB 转换功能的 Python 开发人员。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式（包括 POTM 和 XLSB 文件）的各种 API 的完整包。

主要分两步。 首先使用 [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API 将 POTM 文件转换为 HTML。 之后通过使用 Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/)，将创建的 HTML 保存为所需的 Microsoft Excel 格式。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 POTM 转换为 XLSB" %}}
- **步骤1** 使用[Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)类实例打开源POTM文件 
- 通过提供文件名和所需目录路径，使用 [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) 方法将 POTM 文件保存为 HTML
-  **第2步** 使用 Workbook 类的实例加载 HTML 文件
-  在指定输出 XLSB 文件路径时调用 `save` 方法。这样你的POTM文件就在指定路径下转成XLSB了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 POTM 到 XLSB 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Slides](https://pypi.org/project/Aspose.Slides/) 和 [Aspose.Cells](https://pypi.org/project/aspose-cells-python/)）
-  或者使用以下 pip 命令```pip install aspose.slides``` 和```pip install aspose-cells-python```
-  此外，基于 Microsoft Windows 或 Linux 的操作系统（更多信息请参见 [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) 和 [Slides](https://docs.aspose.com/slides/python-net/system-requirements/)）
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 POTM 保存为 HTML - 第 1 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 HTML 保存为 XLSB - 第 2 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}