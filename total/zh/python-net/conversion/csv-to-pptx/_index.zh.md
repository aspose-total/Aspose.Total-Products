---
title: 使用 Python 将 CSV 转换为 PPTX
description: 在不使用 Microsoft Office 的情况下在 Python 应用程序中将 CSV 转换为 PPTX 

family: total
platformtag: Python
feature: conversion
informat: CSV
outformat: PPTX
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Python 将 CSV 转换为 PPTX" h2="无需安装 Microsoft Excel<sup>&reg;</sup> 或 PowerPoint，即可在 Python 应用程序中将 CSV 转换为 PPTX" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于尝试在应用程序中添加 CSV 到 PPTX 转换功能的 Python 开发人员, [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式（包括 CSV 和 PPTX 文件）的各种 API 的完整包.

主要分两步. 首先使用[Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API将CSV文件转换为PDF. 之后使用 PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/)，将创建的 PDF 保存为所需的 Microsoft PowerPoint 格式. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 CSV 转换为 PPTX" %}}
- **步骤1** 使用Workbook类实例打开源CSV文件 
- 通过提供文件名和所需目录路径，使用 save 方法将 CSV 文件保存为 PDF
-  **第2步** 使用 [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) 类加载 PDF 文件
-  指定输出 PPTX 文件路径时调用 [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) 方法. 这样你的CSV文件就在指定路径下转成PPTX了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 CSV 到 PPTX 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Cells](https://pypi.org/project/aspose-cells-python/) 和 [Aspose.Slides](https://pypi.org/project/Aspose.Slides/)）
-  或者使用以下 pip 命令```pip install aspose-cells-python``` 和 ```pip install aspose.slides```
-  此外，基于 Microsoft Windows 或 Linux 的操作系统（更多信息请参见 [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) 和 [Slides](https://docs.aspose.com/slides/python-net/system-requirements/)）
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 CSV 保存为 PDF - 第 1 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 PDF 保存为 PPTX - 第 2 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}