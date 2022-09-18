---
title: 在 Python 中将 DOT 转换为 PPTM
description: 在 Python 应用程序中将 DOT 转换为 PPTM，而无需使用 Microsoft Word 或 PowerPoint 
url: /zh/python-net/conversion/dot-to-pptm/
family: total
platformtag: Python
feature: conversion
informat: DOT
outformat: PPTM
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 DOT 转换为 PPTM" h2="无需安装 Microsoft Word<sup>&reg;</sup> 或 PowerPoint 即可在 Python 应用程序中将 DOT 转换为 PPTM" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 DOT 到 PPTM 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。它是处理不同格式的各种 API 的完整包。 所以 **如何在 Python 中将 DOT 转换为 PPTM？**

主要分两步。 首先使用 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API 将 DOT 文件转换为 PDF。 之后使用 PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/)，将创建的 PDF 保存为 PPTM 格式的 Presentation。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Python 中将 DOT 转换为 PPTM" %}}
- **步骤1** 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 DOT 文件
- 通过提供文件名和所需的目录路径，使用 [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) 方法将 DOT 文件保存为 PDF。
-  **第2步** 使用 [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) 类的实例加载 PDF 文件
-  在指定输出文件路径和 SaveFormat.PPTM 作为参数时调用 `save` 方法。 因此，您的 DOT 文件将在指定路径转换为 PPTM。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 DOT 到 PPTM 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI（[Aspose.Slides](https://pypi.org/project/Aspose.Slides/) 和 [Aspose.Words](https://pypi.org/project/aspose-words/)）引用项目中的 API 或
- 使用以下 pip 命令 ```pip install aspose.slides``` 和 ```pip install aspose.words```。而且，
- 基于 Microsoft Windows 或 Linux 的操作系统（请参阅更多有关 [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) 和 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 的信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照 [INSTALL](https://docs.aspose.com/words/python-net/installation/) 的分步说明进行操作。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 DOT 保存为 PDF - 第 1 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 PDF 保存为 PPTM - 第 2 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}