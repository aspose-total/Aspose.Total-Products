---
title: 在 Python 中将 PDF 转换为 MHTML
description: PDF 到 mhtml Web 存档格式和 HtmlFixed 文件在 Python 应用程序中的转换，无需使用 Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 PDF 转换为 MHTML" h2="在您的 Python 应用程序中将 PDF 转换为 MHTML、HtmlFixed 和 HTML，而无需安装 Microsoft Word<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于尝试添加 PDF 到 MHTML（Web 存档格式）转换功能或 HtmlFixed 的 Python 开发人员来说，他们希望使用应用程序中的绝对定位元素将文档保存为 HTML 格式。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。它是处理不同格式的各种 API 的完整包。 

我们使用 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包中的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API 来添加 PDF 到 MHTML 的转换功能。 如果 PDF 文件很简单，那么它只有两行代码。 加载 PDF 文件并使用适当的文件路径以及作为 MHTML 或 HTML_FIXED 的 SaveFormat 枚举调用 save 方法。 但是，如果需要将文档模型恢复为接近原始模型，则需要在结果文档中保存一些额外的信息，称为往返信息。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何 在 Python 中将 PDF 转换为 MHTML" %}}
- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类加载源 PDF 文件
- 创建 [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/) 的实例。
- 将 export_roundtrip_information 设置为 True
- 将 [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) 指定为 MHTML
- 在指定输出文件路径和 SaveFormat 作为参数时调用 `save` 方法。 因此，您的 PDF 文件将在指定路径转换为 MHTML。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 PDF 到 MHTML 或 HtmlFixed 格式的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/)) 引用项目中的 API
- 或者使用以下 pip 命令 ```pip install aspose.words```。
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（请参阅 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照 [INSTALL](https://docs.aspose.com/words/python-net/installation/) 的分步说明进行操作。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 PDF 保存为 MHTML - 简单" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-mhtml-simple.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python 中的 PDF 到 MHTML 转换" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "pdf-to-mhtml-conversion-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

使用 Python API 将 PDF 转换为 MHTML 有助于将文档内容转换为一种将标记和嵌入资源合并为单个文件的网络存档格式。这使得 PDF 信息更容易在兼容浏览器的环境中保存、显示或分发。

自动化通过实现从静态文档可扩展地生成可移植的 Web 就绪文件，提高了此转换的价值。它支持内容发布、归档以及与需要自包含 Web 文档输出的系统的集成。

{{% blocks/products/pf/agp/feature-section-col title="关键使用场景" %}}

* **网络存档创建**  
  将 PDF 文件转换为 MHTML，以便在基于浏览器的存储和查看中使用。

* **可移植文档发布**  
  以自包含的 Web 友好格式共享文档内容。

* **内容保存**  
  在适合 Web 工作流的存档中保留视觉和文本信息。

* **系统互操作性**  
  在文档交换必须符合浏览器兼容标准的情况下使用 MHTML 输出。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **自动化 Web 转换流水线**  
  Python 脚本可以将 PDF 转换为 MHTML 文件，用于数字出版系统。

* **归档分发工作流**  
  转换后的输出可以交付给管理网络存档内容的仓库。

* **批量文档发布**  
  大量 PDF 可以在无需人工干预的情况下转换为可移植的 Web 文件。

* **动态内容导出**  
  系统可以按需生成文档的 MHTML 版本，以便共享或审阅。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}