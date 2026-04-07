---
title: 在 Python 中将 WORDML 转换为 MSG
description: 在 Python 应用程序中将 WORDML 保存为 MSG，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: WORDML
outformat: MSG
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 WORDML 转换为 MSG" h2="在您的 Python 应用程序中将 WORDML 转换为 MSG，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 WORDML 到 MSG 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 WORDML 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 MSG 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 WORDML 转换为 MSG" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 WORDML 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 WORDML 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后WORDML被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 WORDML 到 MSG 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 WORDML 保存为 MSG" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

WordML 到 MSG 的转换可将文档内容生成电子邮件消息文件，用于桌面邮件工作流、归档流程和通信打包。当需要将结构化文档信息保留为单独的消息记录时，这非常有用。

Python API 通过将文档文本映射到消息组件并自动生成适用于电子邮件环境的输出，支持 WordML 到 MSG 的转换。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* **消息文件创建**
  将 WordML 内容转换为 MSG 文件，以便对单个电子邮件记录进行处理。

* **桌面邮件兼容性**
  支持在面向桌面的环境中依赖消息文件交换的工作流。

* **通信归档**
  将基于文档的内容保存为离散的电子邮件式工件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **批量 MSG 生成**
  自动从多个 WordML 文档创建消息文件。

* **归档准备**
  将结构化文档转换为 MSG 记录，以用于存储和检索工作流。

* **运营内容打包**
  支持将文档衍生的通信以编程方式交付到消息系统。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}