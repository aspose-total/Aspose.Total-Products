---
title: 在 Python 中将 RTF 转换为 OFT
description: 在 Python 应用程序中将 RTF 保存为 OFT，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: RTF
outformat: OFT
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 RTF 转换为 OFT" h2="在您的 Python 应用程序中将 RTF 转换为 OFT，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 RTF 到 OFT 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 RTF 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 OFT 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 RTF 转换为 OFT" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 RTF 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 RTF 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后RTF被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 RTF 到 OFT 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 RTF 保存为 OFT" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

RTF 到 OFT 的转换将格式化的文本文档转换为可重复用于标准化沟通的电子邮件模板文件。当组织需要将已准备的内容转换为结构化模板，以实现一致的外联、支持或内部消息传递时，这非常有用。

在自动化工作流中，RTF 到 OFT 通过将文档编写的内容转化为可重复使用的模板，支持可重复的电子邮件生成，这些模板可以动态填充并在沟通过程中部署。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* **可重用的电子邮件模板创建**  
  将富文本内容转换为模板文件，以实现一致的消息撰写。

* **标准化内部沟通**  
  帮助团队在重复的电子邮件和通知中保持统一的措辞。

* **已准备的外联内容**  
  支持将已批准的文本资产转换为可直接使用的通信模板格式。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **基于模板的消息流水线**  
  系统可以将 RTF 文档转换为 OFT 模板，用于自动化通信工作流。

* **动态内容填充**  
  编程过程可以将可重用的模板与变量数据配对，实现可扩展的消息发送。

* **基于审批的沟通自动化**  
  标准文档文本可以转化为受控的电子邮件模板，以实现有治理的外联。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}