---
title: 在 Python 中将 WORD 转换为 EMLX
description: 在 Python 应用程序中将 WORD 保存为 EMLX，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: EMLX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 WORD 转换为 EMLX" h2="在您的 Python 应用程序中将 WORD 转换为 EMLX，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 WORD 到 EMLX 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 WORD 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 EMLX 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 WORD 转换为 EMLX" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 WORD 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 WORD 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后WORD被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 WORD 到 EMLX 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 WORD 保存为 EMLX" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

使用 Python API 将 Word 转换为 EMLX 可以将文字处理文档转换为在特定电子邮件环境中常用的 EMLX 消息文件。这支持需要在邮件中心格式中保留或重新利用文档内容以进行查看、传输或归档的场景。

在自动化系统中，此转换通过使文档成为结构化的电子邮件工件，适配消息存储、迁移或通信处理流水线，从而提升工作流的连续性。

{{% blocks/products/pf/agp/feature-section-col title="关键使用案例" %}}

* **邮件客户端兼容性**
  将文档内容转换为 EMLX 文件，以便在兼容的消息环境中使用。

* **基于文档的消息归档**
  在适合有序存储的消息格式中保留 Word 编写的内容。

* **跨格式内容复用**
  允许相同的源材料同时用于文档和面向电子邮件的目的。

* **迁移准备**
  支持从文档来源需要消息兼容文件的迁移过程。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **自动邮件文件转换**
  将 Word 文档处理为 EMLX 输出，以便存储或后续导入。

* **保留工作流支持**
  将业务文档转换为电子邮件式记录，以用于结构化归档。

* **批量内容打包**
  从标准化文档模板大规模生成消息文件。

* **系统集成流水线**
  在更广泛的内容和通信工作流中将 EMLX 输出用作中间资产。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}