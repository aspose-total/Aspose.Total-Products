---
title: 使用 Python 将 XLSB 转换为 DOCM
description: 在不使用 Microsoft Office 的情况下在 Python 应用程序中将 XLSB 转换为 DOCM 

family: total
platformtag: Python
feature: conversion
informat: XLSB
outformat: DOCM
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Python 将 XLSB 转换为 DOCM" h2="无需安装 Microsoft Excel<sup>&reg;</sup> 或 Word，即可在 Python 应用程序中将 XLSB 转换为 DOCM" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于尝试在应用程序中添加 XLSB 到 DOCM 转换功能的 Python 开发人员。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式（包括 XLSB 和 DOCM 文件）的各种 API 的完整包。

主要分两步。 首先使用 [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API 将 XLSB 文件转换为 HTML。 之后，通过使用 Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)，将创建的 HTML 保存为所需的 Microsoft Word 格式。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 XLSB 转换为 DOCM" %}}
- **步骤1** 使用 Workbook 类打开源 XLSB 文件
- 通过提供文件名和所需目录路径，使用 save(file, SaveFormat.HTML) 方法将 XLSB 文件保存为 HTML
-  **第2步** 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类的实例加载 HTML 文件
-  在指定输出 DOCM 文件路径时调用 `save` 方法。 这样你的XLSB文件就在指定路径下转成DOCM了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 XLSB 到 DOCM 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Cells](https://pypi.org/project/aspose-cells-python/) 和 [Aspose.Words](https://pypi.org/project/aspose-words/)）
-  或者使用以下 pip 命令```pip install aspose-cells-python``` 和```pip install aspose.words```
-  此外，基于 Microsoft Windows 或 Linux 的操作系统（请参阅有关 [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) 和 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求并遵循 [分步说明](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 XLSB 保存为 HTML - 第 1 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 HTML 保存为 DOCM - 第 2 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-word/" name="XLSB 到 WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-doc/" name="XLSB 到 DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-docx/" name="XLSB 到 DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-docm/" name="XLSB 到 DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-dot/" name="XLSB 到 DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-dotm/" name="XLSB 到 DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-dotx/" name="XLSB 到 DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-mobi/" name="XLSB 到 MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-odt/" name="XLSB 到 ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-ott/" name="XLSB 到 OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-rtf/" name="XLSB 到 RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/python-net/conversion/xlsb-to-wordml/" name="XLSB 到 WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}