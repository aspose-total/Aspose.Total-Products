---
title: 使用 Python 将 XLS 转换为 ODT
description: 在不使用 Microsoft Office 的情况下在 Python 应用程序中将 XLS 转换为 ODT 

family: total
platformtag: Python
feature: conversion
informat: XLS
outformat: ODT
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Python 将 XLS 转换为 ODT" h2="无需安装 Microsoft Excel<sup>&reg;</sup> 或 Word，即可在 Python 应用程序中将 XLS 转换为 ODT" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于尝试在应用程序中添加 XLS 到 ODT 转换功能的 Python 开发人员。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式（包括 XLS 和 ODT 文件）的各种 API 的完整包。

主要分两步。 首先使用 [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API 将 XLS 文件转换为 HTML。 之后，通过使用 Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)，将创建的 HTML 保存为所需的 Microsoft Word 格式。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 XLS 转换为 ODT" %}}
- **步骤1** 使用 Workbook 类打开源 XLS 文件
- 通过提供文件名和所需目录路径，使用 save(file, SaveFormat.HTML) 方法将 XLS 文件保存为 HTML
-  **第2步** 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类的实例加载 HTML 文件
-  在指定输出 ODT 文件路径时调用 `save` 方法。 这样你的XLS文件就在指定路径下转成ODT了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 XLS 到 ODT 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Cells](https://pypi.org/project/aspose-cells-python/) 和 [Aspose.Words](https://pypi.org/project/aspose-words/)）
-  或者使用以下 pip 命令```pip install aspose-cells-python``` 和```pip install aspose.words```
-  此外，基于 Microsoft Windows 或 Linux 的操作系统（请参阅有关 [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) 和 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求并遵循 [分步说明](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 XLS 保存为 HTML - 第 1 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 HTML 保存为 ODT - 第 2 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}