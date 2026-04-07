---
title: 在 Python 中将 EPUB 转换为 MBOX
description: 在 Python 应用程序中将 EPUB 保存为 MBOX，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: EPUB
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 EPUB 转换为 MBOX" h2="在您的 Python 应用程序中将 EPUB 转换为 MBOX，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 EPUB 到 MBOX 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 EPUB 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 MBOX 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 EPUB 转换为 MBOX" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 EPUB 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 EPUB 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后EPUB被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 EPUB 到 MBOX 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 EPUB 保存为 MBOX" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

在 Python 中将 EPUB 转换为 MBOX 能够将数字出版内容转换为用于存储消息集合的邮箱式归档格式。当组织需要将转换后的内容进行归档、迁移或面向通信的存储工作流时，这非常有价值。

对于自动化驱动的操作，EPUB 到 MBOX 的转换提供了一种高效的方式，将多个内容项打包成结构化的邮件归档，使 Python 应用在可扩展的文档保存和传输流程中更为高效。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* **邮箱归档创建**  
  将 EPUB 内容转换为 MBOX 格式，以便存储在邮件归档系统和仓库中。

* **批量内容打包**  
  将出版物衍生的内容分组到统一的归档结构中，以便更易管理。

* **迁移支持**  
  在将内容迁移到接受邮箱式归档数据的系统时使用 MBOX 输出。

* **保留工作流启用**  
  将转换后的出版内容保存在适合归档的消息集合中，以供审计或参考使用。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **归档生成流水线**  
  Python 应用可以在摄取工作流期间自动从 EPUB 源生成 MBOX 文件。

* **批量转换过程**  
  自动化作业可以将大量 EPUB 文档转换为具有一致格式的邮箱归档。

* **仓库同步**  
  转换可以作为文档存储与归档平台之间内容同步的一部分触发。

* **可扩展的保存任务**  
  编程处理支持大批量归档操作，无需重复的人工干预。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}