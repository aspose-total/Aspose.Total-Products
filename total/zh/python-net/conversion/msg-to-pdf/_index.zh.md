---
title: 在 Python 中将 MSG 转换为 PDF
description: 在 Python 应用程序中将 MSG 保存为 PDF，而无需使用 Microsoft Outlook 或 Word 

family: total
platformtag: Python
feature: conversion
informat: MSG
outformat: PDF
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 MSG 转换为 PDF" h2="在您的 Python 应用程序中将 MSG 转换为 PDF，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 MSG 到 PDF 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 可以轻松进行此转换。 这是一个两步过程，首先加载电子邮件并通过 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 加载转换后的 HTML 并将其保存为 PDF 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 MSG 转换为 PDF" %}}

- 使用 MailMessage.load 类打开源 MSG 文件
- 在指定输出 HTML 文件路径和相关的 HTML 保存选项作为参数时调用 `save` 方法。 所以你的 MSG 文件在指定的路径被转换成 HTML
- 现在使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后MSG被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 MSG 到 PDF 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 MSG 保存为 PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

MSG 转 PDF 转换将电子邮件内容转换为一种稳定、被广泛接受的文档格式，能够保留布局并支持轻松共享。它是归档、分发和审阅电子邮件衍生信息的最实用选项之一。

在自动化系统中，MSG 转 PDF 工作流实现了可靠的记录保存、可搜索的归档以及跨设备一致的文档输出。它们被广泛用于合规、报告以及可扩展的数字文档管理。

{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}

* **可靠的归档存储**  
  以固定布局的格式保存电子邮件内容，适合长期保留。

* **通用共享**  
  以在各平台广泛支持的格式分发转换后的消息。

* **正式文档**  
  将电子邮件记录纳入案件文件、报告和官方文档集。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}

* **合规归档流水线**  
  自动将 MSG 文件转换为 PDF，以用于受监管的存储工作流。

* **可搜索的文档库**  
  将 PDF 输出导入索引和检索系统，以便更轻松访问。

* **自动化记录分发**  
  从消息内容生成可共享的文档，用于报告和审阅。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}