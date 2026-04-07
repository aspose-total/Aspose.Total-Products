---
title: 使用 Python 将 EXCEL 转换为 POTM
description: 在不使用 Microsoft Office 的情况下在 Python 应用程序中将 EXCEL 转换为 POTM 

family: total
platformtag: Python
feature: conversion
informat: EXCEL
outformat: POTM
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Python 将 EXCEL 转换为 POTM" h2="无需安装 Microsoft Excel<sup>&reg;</sup> 或 PowerPoint，即可在 Python 应用程序中将 EXCEL 转换为 POTM" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于尝试在应用程序中添加 EXCEL 到 POTM 转换功能的 Python 开发人员, [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式（包括 EXCEL 和 POTM 文件）的各种 API 的完整包.

主要分两步. 首先使用[Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API将EXCEL文件转换为PDF. 之后使用 PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/)，将创建的 PDF 保存为所需的 Microsoft PowerPoint 格式. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 EXCEL 转换为 POTM" %}}
- **步骤1** 使用Workbook类实例打开源EXCEL文件 
- 通过提供文件名和所需目录路径，使用 save 方法将 EXCEL 文件保存为 PDF
-  **第2步** 使用 [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) 类加载 PDF 文件
-  指定输出 POTM 文件路径时调用 [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) 方法. 这样你的EXCEL文件就在指定路径下转成POTM了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 EXCEL 到 POTM 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Cells](https://pypi.org/project/aspose-cells-python/) 和 [Aspose.Slides](https://pypi.org/project/Aspose.Slides/)）
-  或者使用以下 pip 命令```pip install aspose-cells-python``` 和 ```pip install aspose.slides```
-  此外，基于 Microsoft Windows 或 Linux 的操作系统（更多信息请参见 [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) 和 [Slides](https://docs.aspose.com/slides/python-net/system-requirements/)）
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 EXCEL 保存为 PDF - 第 1 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 PDF 保存为 POTM - 第 2 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Excel 到 POTM 的 Python 转换帮助将电子表格内容转换为宏启用的演示模板，以实现高级幻灯片自动化工作流。它在可重复使用的演示结构也需要可编程操作或嵌入式自动化支持的情况下非常有用。

此转换通过将基于电子表格的模板生成与宏启用的演示功能相结合，提升了自动化的相关性。

{{% blocks/products/pf/agp/feature-section-col title="关键使用案例" %}}

* **宏启用幻灯片模板**  
  将 Excel 数据转换为 POTM 文件，以实现可重复使用且可自动化的演示文稿。

* **高级演示工作流**  
  支持可以包含逻辑驱动或辅助演示行为的模板文件。

* **结构化沟通资产**  
  从基于电子表格的源内容准备可重复使用的演示基础。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **模板自动化流水线**  
  从 Excel 输入程序化生成 POTM 文件，以实现可重复的幻灯片制作。

* **交互式演示系统**  
  启用依赖于带宏支持的可重复使用模板的工作流。

* **可扩展的演示准备**  
  使用 Python API 自动化从数据源创建宏启用的幻灯片模板。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}