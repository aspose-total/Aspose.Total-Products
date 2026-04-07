---
title: 在 Python 中将 PDF 转换为 EMAIL
description: 在 Python 应用程序中将 PDF 保存为 EMAIL，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: EMAIL
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 PDF 转换为 EMAIL" h2="在您的 Python 应用程序中将 PDF 转换为 EMAIL，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 PDF 到 EMAIL 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 PDF 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 EMAIL 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 PDF 转换为 EMAIL" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 PDF 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 PDF 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后PDF被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 PDF 到 EMAIL 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 PDF 保存为 EMAIL" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

使用 Python API 的 PDF 转 Email 转换使组织能够将静态 PDF 文档转换为可用于通信、归档和工作流交付的邮件就绪内容。此过程帮助团队在对可访问性、可读性和分发速度有高要求的消息环境中重复使用基于文档的信息。

通过自动化 PDF 转 Email 转换，企业可以简化通知、报告、客户外联以及基于文档的通信流水线。它通过减少手动格式化工作并使文档内容高效进入现代自动化系统，支持可扩展的工作流。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* **基于文档的通知**  
  将 PDF 内容转换为电子邮件，以快速发送报告、警报或摘要。

* **工作流通信**  
  在审批链、内部更新和服务通信中使用转换后的电子邮件内容。

* **数字内容再利用**  
  在电子邮件渠道中重复使用基于 PDF 的信息，而无需手动重新创建内容。

* **客户文档交付**  
  以更易访问的电子邮件格式发送发票、对账单和信息文档。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **自动化报告分发**  
  计划系统可以将 PDF 报告转换为电子邮件，并自动发送给相关方。

* **触发式通知流水线**  
  业务事件可以触发 PDF 转 Email 转换，实现即时的外发通信。

* **文档路由工作流**  
  转换后的电子邮件内容可以动态路由到团队、部门或客户。

* **大规模消息运营**  
  基于 Python 的自动化可以高效处理大量 PDF 文件，生成邮件就绪的输出。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}