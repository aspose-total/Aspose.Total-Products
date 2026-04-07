---
title: 在 Python 中将 PDF 转换为 EMLX
description: 在 Python 应用程序中将 PDF 保存为 EMLX，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: EMLX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 PDF 转换为 EMLX" h2="在您的 Python 应用程序中将 PDF 转换为 EMLX，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 PDF 到 EMLX 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 PDF 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 EMLX 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 PDF 转换为 EMLX" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 PDF 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 PDF 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后PDF被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 PDF 到 EMLX 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 PDF 保存为 EMLX" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

使用 Python API 将 PDF 转换为 EMLX 可将 PDF 文档转换为在特定电子邮件存储生态系统中常用的消息文件。这支持需要在邮件原生文件结构中保留或交换文档内容的工作流。

此转换在处理消息导出、迁移任务和结构化通信记录的自动化环境中尤为有用。它通过实现对 PDF 内容的程序化转换为有组织的邮件兼容输出，提高了流程的一致性。

{{% blocks/products/pf/agp/feature-section-col title="关键使用场景" %}}

* **消息文件准备**  
  将 PDF 内容转换为 EMLX 文件，以用于平台特定的电子邮件存储或迁移。

* **通信记录转换**  
  在适合电子邮件导向工作流的文件格式中保留文档数据。

* **数据可移植性**  
  支持文档库与基于邮件的系统之间的转换。

* **结构化内容复用**  
  在无需手动重建内容的情况下，将 PDF 重新用于消息文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **迁移支持流水线**  
  在邮箱或内容迁移项目期间，Python 自动化可以从 PDF 生成 EMLX 文件。

* **文档归档流程**  
  系统可以将 PDF 转换为邮件兼容的记录，以实现有序的保留。

* **批量内容转换**  
  大批量文档集合可以自动处理为 EMLX 格式。

* **基于工作流的导出**  
  触发的流程可以在收到新 PDF 文档时创建 EMLX 输出。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}