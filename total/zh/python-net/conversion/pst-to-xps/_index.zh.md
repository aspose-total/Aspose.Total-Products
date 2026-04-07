---
title: 在 Python 中将 PST 转换为 XPS
description: 在 Python 应用程序中将 PST 保存为 XPS，而无需使用 Microsoft Outlook 或 Word 

family: total
platformtag: Python
feature: conversion
informat: PST
outformat: XPS
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 PST 转换为 XPS" h2="在您的 Python 应用程序中将 PST 转换为 XPS，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 PST 到 XPS 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 可以轻松进行此转换。 这是一个两步过程，首先加载电子邮件并通过 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 加载转换后的 HTML 并将其保存为 XPS 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 PST 转换为 XPS" %}}

- 使用 MailMessage.load 类打开源 PST 文件
- 在指定输出 HTML 文件路径和相关的 HTML 保存选项作为参数时调用 `save` 方法。 所以你的 PST 文件在指定的路径被转换成 HTML
- 现在使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后PST被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 PST 到 XPS 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 PST 保存为 XPS" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API 中的 PST 到 XPS 转换将邮箱内容转换为固定布局的文档格式，旨在实现可靠的查看和打印一致性。当需要以稳定的格式保存归档邮件以便分发、审阅或受控输出处理时，此功能非常有用。

在自动化环境中，PST 到 XPS 的转换支持标准化的文档生成和高效的固定格式交付。它帮助邮箱内容与需要可预测渲染的归档、演示和打印相关工作流集成。

{{% blocks/products/pf/agp/feature-section-col title="关键使用场景" %}}

* **固定布局文档导出**
  将 PST 内容转换为 XPS，以实现一致的视觉呈现。

* **稳定记录分发**
  帮助共享来源于邮箱的文件，在不同系统间保持布局不变。

* **打印一致的输出**
  支持需要可靠页面渲染和显示行为的工作流。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **自动化固定格式生成**
  系统可以将 PST 档案转换为 XPS，以实现可靠的下游使用。

* **受控渲染工作流**
  XPS 输出支持需要布局一致性的文档流水线。

* **可扩展的分发与归档**
  编程式转换帮助以可预测的固定布局格式交付邮箱内容。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}