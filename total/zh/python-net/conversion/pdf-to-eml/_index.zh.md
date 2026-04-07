---
title: 在 Python 中将 PDF 转换为 EML
description: 在 Python 应用程序中将 PDF 保存为 EML，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 PDF 转换为 EML" h2="在您的 Python 应用程序中将 PDF 转换为 EML，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 PDF 到 EML 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 PDF 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 EML 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 PDF 转换为 EML" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 PDF 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 PDF 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后PDF被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 PDF 到 EML 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 PDF 保存为 EML" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

使用 Python API 将 PDF 转换为 EML 有助于将 PDF 文档转换为可存储、共享或导入兼容邮件系统的标准电子邮件消息文件。这对于以面向消息的格式保存文档内容，以用于通信、备份和互操作性具有重要价值。

自动化 PDF 到 EML 的转换通过实现文档导入邮件存档、自动化消息流和批量处理系统，提高了运营效率。它支持在需要结构化电子邮件文件输出的情况下进行可扩展的数据交换。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* **电子邮件文件生成**  
  将 PDF 文档转换为 EML 文件，以便存储、传输或后续交付。

* **归档工作流**  
  以标准的电子邮件兼容格式保存文档内容，以用于记录保存。

* **邮件系统集成**  
  准备 PDF 派生的内容，以便导入电子邮件客户端和处理系统。

* **内容再利用**  
  将 PDF 信息重新格式化为结构化的消息文件，以用于数字通信工作流。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **批量电子邮件文件创建**  
  自动化脚本可以将大量 PDF 转换为 EML 文件，以供下游使用。

* **归档摄取管道**  
  系统可以将转换后的 EML 输出路由到存储或合规仓库。

* **自动化消息准备**  
  PDF 内容可以以编程方式准备为电子邮件文件，以供后续审阅或发送。

* **文档到消息转换**  
  Python 工作流可以动态地将传入的 PDF 转换为可重复使用的 EML 资产。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}