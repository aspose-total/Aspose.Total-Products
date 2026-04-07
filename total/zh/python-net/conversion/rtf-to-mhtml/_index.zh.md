---
title: 在 Python 中将 RTF 转换为 MHTML
description: RTF 到 mhtml Web 存档格式和 HtmlFixed 文件在 Python 应用程序中的转换，无需使用 Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: RTF
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 RTF 转换为 MHTML" h2="在您的 Python 应用程序中将 RTF 转换为 MHTML、HtmlFixed 和 HTML，而无需安装 Microsoft Word<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于尝试添加 RTF 到 MHTML（Web 存档格式）转换功能或 HtmlFixed 的 Python 开发人员来说，他们希望使用应用程序中的绝对定位元素将文档保存为 HTML 格式。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。它是处理不同格式的各种 API 的完整包。 

我们使用 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包中的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API 来添加 RTF 到 MHTML 的转换功能。 如果 RTF 文件很简单，那么它只有两行代码。 加载 RTF 文件并使用适当的文件路径以及作为 MHTML 或 HTML_FIXED 的 SaveFormat 枚举调用 save 方法。 但是，如果需要将文档模型恢复为接近原始模型，则需要在结果文档中保存一些额外的信息，称为往返信息。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何 在 Python 中将 RTF 转换为 MHTML" %}}
- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类加载源 RTF 文件
- 创建 [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/) 的实例。
- 将 export_roundtrip_information 设置为 True
- 将 [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) 指定为 MHTML
- 在指定输出文件路径和 SaveFormat 作为参数时调用 `save` 方法。 因此，您的 RTF 文件将在指定路径转换为 MHTML。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 RTF 到 MHTML 或 HtmlFixed 格式的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/)) 引用项目中的 API
- 或者使用以下 pip 命令 ```pip install aspose.words```。
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（请参阅 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照 [INSTALL](https://docs.aspose.com/words/python-net/installation/) 的分步说明进行操作。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 RTF 保存为 MHTML - 简单" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python 中的 RTF 到 MHTML 转换" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

RTF 到 MHTML 的转换将富文本文档转换为网络存档文件，将内容和资源合并为单个可移植的包。当需要以浏览器友好的格式保存文档信息以便共享、查看或离线访问时，这非常有价值。

在自动化系统中，RTF 到 MHTML 支持可扩展的文档发布、归档打包和内容分发工作流，其中自包含的网页可读格式提升了可访问性和一致性。

{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}

* **可移植的网页文档创建**  
  将富文本内容转换为单文件网页存档，便于共享。

* **离线内容访问**  
  帮助以一种无需实时依赖即可查看的格式保存文档信息。

* **浏览器兼容归档**  
  支持以网页友好形式长期保留文本内容。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}

* **自动化网页存档生成**  
  系统可以将 RTF 文档转换为 MHTML 文件，用于门户、记录或分发工作流。

* **内容打包流水线**  
  编程式转换实现跨系统和团队的自包含文档交付。

* **可扩展的归档渲染**  
  批处理可以从大型文档库生成可在浏览器中查看的存档。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}