---
title: 在 Python 中将 RTF 转换为 EML
description: 在 Python 应用程序中将 RTF 保存为 EML，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: RTF
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 RTF 转换为 EML" h2="在您的 Python 应用程序中将 RTF 转换为 EML，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 RTF 到 EML 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 RTF 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 EML 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 RTF 转换为 EML" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 RTF 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 RTF 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后RTF被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 RTF 到 EML 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 RTF 保存为 EML" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

RTF 转换为 EML 将富文本文档转换为标准电子邮件消息文件，可在兼容的邮件系统中存储、共享、导入或归档。当文档内容需要成为具有消息结构的可移植电子邮件工件时，这非常有用。

对于自动化，RTF 转换为 EML 可实现基于文档的电子邮件生成、消息归档以及可重复的通信工作流，在这些场景中需要结构化的电子邮件文件用于交换或长期保存。

{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}

* **可移植电子邮件创建**  
  将文档内容转换为可独立共享或导入的电子邮件文件。

* **通信归档**  
  支持以公认的电子邮件格式保存基于文档的消息。

* **消息工作流标准化**  
  帮助团队从已准备好的 RTF 内容生成一致的电子邮件输出。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}

* **自动化消息文件生成**  
  系统可以将 RTF 文档转换为 EML 文件，作为通信流水线的一部分。

* **电子邮件归档准备**  
  批处理过程可以将文本内容转换为消息文件，以用于保留和合规工作流。

* **跨平台消息交换**  
  编程转换帮助将基于文档的通信迁移到电子邮件生态系统，而无需手动重新创建。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}