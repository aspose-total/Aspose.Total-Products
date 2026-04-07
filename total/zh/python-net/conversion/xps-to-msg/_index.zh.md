---
title: 在 Python 中将 XPS 转换为 MSG
description: 在 Python 应用程序中将 XPS 保存为 MSG，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: MSG
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 XPS 转换为 MSG" h2="在您的 Python 应用程序中将 XPS 转换为 MSG，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 XPS 到 MSG 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 XPS 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 MSG 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 XPS 转换为 MSG" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 XPS 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 XPS 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后XPS被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 XPS 到 MSG 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 XPS 保存为 MSG" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

使用 Python API 的 XPS 转 MSG 转换，使得能够将固定布局文档转换为常用于桌面消息环境的单个电子邮件消息文件。当需要将文档内容保留为独立的消息记录以供审阅、共享或结构化通信工作流时，这非常有益。

自动化通过减少手动消息创建、实现可重复的文档到消息的转换，并支持与归档、审批和企业通信系统的集成，显著提升价值。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* **独立消息文件创建**  
  将 XPS 文档转换为 MSG 文件，以实现有序的电子邮件式存储和交换。

* **文档到通信的转换**  
  帮助将固定布局文档内容重新用于业务工作流中的消息记录。

* **可审阅的消息输出**  
  支持需要将转换后的内容以单独消息形式打开、检查或批准的工作流。

* **企业记录管理**  
  实现以消息文件格式对文档衍生的通信进行结构化保存。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **程序化消息生成**  
  系统可以在 XPS 文档完成后自动创建 MSG 文件。

* **审批工作流路由**  
  转换后的消息可以输入到自动化审查或签署流程中。

* **批量转换操作**  
  大型 XPS 集合可以在一致且可扩展的流水线中转换为 MSG 输出。

* **归档与检索自动化**  
  从文档生成的消息文件可以自动索引并存储，以便后续访问。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}