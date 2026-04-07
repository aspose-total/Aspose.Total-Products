---
title: 在 Python 中将 WORDML 转换为 EMAIL
description: 在 Python 应用程序中将 WORDML 保存为 EMAIL，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: WORDML
outformat: EMAIL
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 WORDML 转换为 EMAIL" h2="在您的 Python 应用程序中将 WORDML 转换为 EMAIL，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 WORDML 到 EMAIL 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 WORDML 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 EMAIL 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 WORDML 转换为 EMAIL" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 WORDML 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 WORDML 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后WORDML被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 WORDML 到 EMAIL 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 WORDML 保存为 EMAIL" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

WordML 到电子邮件的转换将文档内容转换为可用于通信工作流、模板化消息和内容再利用的电子邮件就绪输出。当文档文本需要成为可分发的电子邮件内容而无需手动重写时，这一功能非常有价值。

借助 Python API，WordML 到电子邮件的转换可以实现自动化，提取正文文本，在相关情况下保留结构，并简化文档到消息的工作流，以用于通知、活动和运营通信。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* **内容再利用**
  将文档文本转换为可用于通信场景的电子邮件就绪内容。

* **模板生成**
  使用 WordML 文档作为一致的外发消息的源材料。

* **运营消息**
  帮助将内部或生成的文档转化为结构化的电子邮件通信。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **文档到消息管道**
  自动将 WordML 文件转换为外发系统的电子邮件内容。

* **通知工作流支持**
  实现从标准化文档源动态生成电子邮件正文。

* **大规模通信自动化**
  在定期报告、更新或基于文档的警报中扩展消息创建的规模。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}