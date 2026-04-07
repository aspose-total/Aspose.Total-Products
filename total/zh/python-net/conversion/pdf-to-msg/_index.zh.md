---
title: 在 Python 中将 PDF 转换为 MSG
description: 在 Python 应用程序中将 PDF 保存为 MSG，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: MSG
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 PDF 转换为 MSG" h2="在您的 Python 应用程序中将 PDF 转换为 MSG，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 PDF 到 MSG 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 PDF 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 MSG 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 PDF 转换为 MSG" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 PDF 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 PDF 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后PDF被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 PDF 到 MSG 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 PDF 保存为 MSG" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

使用 Python API 的 PDF 转 MSG 转换能够将 PDF 内容转换为桌面电子邮件环境中常用的消息文件。这对于基于文档的通信工作流、消息准备以及依赖结构化电子邮件文件格式的存储场景非常有用。

在自动化的情况下，PDF 转 MSG 转换帮助组织简化消息生成、提升一致性并减少手动格式化步骤。它非常适合用于管理通信记录、客户往来或内部通知工作流的系统。

{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}

* **电子邮件消息文件创建**  
  将 PDF 文档转换为 MSG 文件，用于通信或存储工作流。

* **文档转消息再利用**  
  在结构化电子邮件格式中重复使用 PDF 内容，无需手动重写。

* **客户端兼容的消息**  
  为使用桌面电子邮件消息文件的系统准备输出。

* **运营记录保存**  
  将文档衍生的通信以有组织的基于消息的结构存储。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}

* **批量消息生成**  
  Python 自动化可以在单个工作流中将多个 PDF 转换为 MSG 文件。

* **通知系统支持**  
  文档内容可以转换为可重复使用的消息文件，用于运营警报。

* **迁移和导出过程**  
  转换后的 MSG 输出可以支持文档系统与电子邮件系统之间的迁移。

* **工作流触发的转换**  
  新的 PDF 到达时可以自动生成相应的消息文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}