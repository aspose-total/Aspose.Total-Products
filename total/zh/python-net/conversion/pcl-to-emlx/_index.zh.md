---
title: 在 Python 中将 PCL 转换为 EMLX
description: 在 Python 应用程序中将 PCL 保存为 EMLX，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: PCL
outformat: EMLX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 PCL 转换为 EMLX" h2="在您的 Python 应用程序中将 PCL 转换为 EMLX，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 PCL 到 EMLX 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 PCL 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 EMLX 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 PCL 转换为 EMLX" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 PCL 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 PCL 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后PCL被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 PCL 到 EMLX 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 PCL 保存为 EMLX" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

使用 Python API 将 PCL 转换为 EMLX，使得能够将传统的 PCL 打印文件转换为在特定电子邮件存储环境中使用的 EMLX 消息文件。这帮助组织在需要结构化消息文件进行本地存储、分析或迁移的生态系统中重新利用打印机生成的内容。

自动化 PCL 到 EMLX 的转换通过消除手动重新格式化步骤并实现将打印输出直接转换为电子邮件兼容的工件，提高了效率。它支持在消息保存、可移植性或特定应用电子邮件处理重要的可扩展工作流。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* **面向邮箱的文件转换**  
  将 PCL 文档转换为 EMLX 文件，以用于基于消息的存储工作流。

* **传统文档再利用**  
  使打印机生成的文件能够重新用作结构化的电子邮件消息资产。

* **迁移准备**  
  帮助为使用 EMLX 消息存储的环境准备来源于打印的内容。

* **数字消息保存**  
  支持以符合以电子邮件为中心的系统的格式保留文档内容。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **自动化格式适配**  
  系统可以将传入的 PCL 文件转换为 EMLX 文件，作为消息准备流水线的一部分。

* **大批量文档转换**  
  批量自动化可以将大量 PCL 集合处理为结构化的电子邮件文件输出。

* **特定应用导出工作流**  
  自动化流程可以生成 EMLX 文件，以在兼容的环境中进行存储或审阅。

* **文档迁移流**  
  在现代化计划期间，PCL 数据可以通过编程方式转换为 EMLX 文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}