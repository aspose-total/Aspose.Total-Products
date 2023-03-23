---
title: 在 Python 中将 WORDML 转换为 MHTML
description: WORDML 到 mhtml Web 存档格式和 HtmlFixed 文件在 Python 应用程序中的转换，无需使用 Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: WORDML
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 WORDML 转换为 MHTML" h2="在您的 Python 应用程序中将 WORDML 转换为 MHTML、HtmlFixed 和 HTML，而无需安装 Microsoft Word<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于尝试添加 WORDML 到 MHTML（Web 存档格式）转换功能或 HtmlFixed 的 Python 开发人员来说，他们希望使用应用程序中的绝对定位元素将文档保存为 HTML 格式。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。它是处理不同格式的各种 API 的完整包。 

我们使用 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包中的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API 来添加 WORDML 到 MHTML 的转换功能。 如果 WORDML 文件很简单，那么它只有两行代码。 加载 WORDML 文件并使用适当的文件路径以及作为 MHTML 或 HTML_FIXED 的 SaveFormat 枚举调用 save 方法。 但是，如果需要将文档模型恢复为接近原始模型，则需要在结果文档中保存一些额外的信息，称为往返信息。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何 在 Python 中将 WORDML 转换为 MHTML" %}}
- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类加载源 WORDML 文件
- 创建 [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/) 的实例。
- 将 export_roundtrip_information 设置为 True
- 将 [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) 指定为 MHTML
- 在指定输出文件路径和 SaveFormat 作为参数时调用 `save` 方法。 因此，您的 WORDML 文件将在指定路径转换为 MHTML。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 WORDML 到 MHTML 或 HtmlFixed 格式的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/)) 引用项目中的 API
- 或者使用以下 pip 命令 ```pip install aspose.words```。
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（请参阅 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照 [INSTALL](https://docs.aspose.com/words/python-net/installation/) 的分步说明进行操作。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 WORDML 保存为 MHTML - 简单" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python 中的 WORDML 到 MHTML 转换" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}