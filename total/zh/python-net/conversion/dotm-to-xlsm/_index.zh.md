---
title: 使用 Python 将 DOTM 转换为 XLSM
description: 在不使用 Microsoft Word 或 Excel 的 Python 应用程序中将 DOTM 转换为 XLSM 

family: total
platformtag: Python
feature: conversion
informat: DOTM
outformat: XLSM
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Python 将 DOTM 转换为 XLSM" h2="无需安装 Microsoft Word<sup>&reg;</sup> 或 Excel，即可在 Python 应用程序中将 DOTM 转换为 XLSM" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于尝试在应用程序中添加 DOTM 到 XLSM 转换功能的 Python 开发人员。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包。

主要分两步。首先使用 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API 将 DOTM 文件转换为 HTML。 之后通过使用 Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/)，将创建的 HTML 保存为所需的 Microsoft Excel 格式。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 DOTM 转换为 XLSM" %}}
- **步骤 1** 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 DOTM 文件
- 通过提供文件名和所需目录路径，使用 [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) 方法将 DOTM 文件保存为 HTML
-  **步骤 2** 使用 Workbook 类的实例加载 HTML 文件，并将文件和 LoadOptions 作为参数
-  在指定输出 XLSM 文件路径时调用 `save` 方法。 这样你的DOTM文件就在指定路径下转成XLSM了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 DOTM 到 XLSM 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Cells](https://pypi.org/project/aspose-cells-python/)）
-  或者使用以下 pip 命令```pip install aspose.words``` 和```pip install aspose-cells-python``` 
-  此外，基于 Microsoft Windows 或 Linux 的操作系统（请参阅有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求并遵循 [分步说明](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 DOTM 保存为 HTML - 第 1 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 HTML 保存为 XLSM - 第 2 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}