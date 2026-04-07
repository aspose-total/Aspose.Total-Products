---
title: 在 Python 中将 XPS 转换为 VCF
description: 在 Python 应用程序中将 XPS 保存为 VCF，而无需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: VCF
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 XPS 转换为 VCF" h2="在您的 Python 应用程序中将 XPS 转换为 VCF，而无需安装 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于 Python 开发人员，谁正在尝试在应用程序中添加 XPS 到 VCF 转换功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助自动化转换过程。 它是处理不同格式的各种 API 的完整包，包括电子邮件、图像和 Microsoft Word 格式。 作为 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 使这种转换变得容易。 这是一个两步过程，首先加载 XPS 文件并通过 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 将其呈现为 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加载转换后的 HTML 并将其保存为 VCF 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 XPS 转换为 VCF" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类打开源 XPS 文件
- 调用 `save` 方法，同时指定输出 HTML 文件路径和相关的 HTML Save 选项作为参数。 所以你的 XPS 文件在指定的路径被转换成 HTML
- 现在使用 MailMessage.load 加载保存的 HTML 文件
- 使用相关文件路径调用 save 方法。所以最后XPS被转换了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 XPS 到 VCF 的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI 引用项目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（有关 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照分步说明进行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 XPS 保存为 VCF" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

使用 Python API 将 XPS 转换为 VCF 可以将固定布局文档中包含的联系人相关信息转换为标准化的联系人卡片文件。当表单、目录或文档生成的记录包含姓名、电话号码、地址或其他需要提取为可移植联系人格式的联系详情时，这非常有用。

在自动化环境中，此转换提升了数据复用，减少手动录入错误，并帮助将基于文档的联系人信息整合到通信、CRM 和联系人管理工作流中。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* **联系人记录提取**
  将包含联系人详细信息的 XPS 文档转换为 VCF 文件，以便轻松复用。

* **地址簿填充**
  使用转换后的输出以支持将联系人导入兼容系统。

* **表单数据再利用**
  将基于文档的客户或员工信息转换为结构化的联系人卡片。

* **可移植联系人共享**
  将提取的详细信息打包成广泛认可的格式，以便交换和存储。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **自动化联系人创建**
  从基于 XPS 的表单或目录生成 VCF 文件，无需手动重新输入。

* **CRM 数据摄取工作流**
  将转换后的联系人文件输入到自动化的客户数据管道中。

* **批量联系人处理**
  使用脚本批处理作业将多个 XPS 记录转换为 VCF 输出。

* **动态信息同步**
  使用程序化转换保持系统间的联系人数据一致。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}