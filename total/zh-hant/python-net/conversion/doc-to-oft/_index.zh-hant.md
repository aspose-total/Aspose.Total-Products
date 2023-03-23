---
title: 在 Python 中將 DOC 轉換為 OFT
description: 在 Python 應用程序中將 DOC 保存為 OFT，而無需使用 Microsoft Word 或 Outlook

family: total
platformtag: Python
feature: conversion
informat: DOC
outformat: OFT
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 將 DOC 轉換為 OFT" h2="在您的 Python 應用程序中將 DOC 轉換為 OFT，而無需安裝 Microsoft Word<sup>&reg;</sup> 或 Outlook。" >}}

{{% blocks/products/pf/feature-page-summary %}}

對於 Python 開發人員，誰正在嘗試在應用程序中添加 DOC 到 OFT 轉換功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以幫助自動化轉換過程。 它是處理不同格式的各種 API 的完整包，包括電子郵件、圖像和 Microsoft Word 格式。 作為 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包的一部分的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 和 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API 使用 Python 可以輕鬆進行此轉換。 這是一個兩步過程，首先加載 DOC 文件並通過 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 將其呈現為 HTML。 其次使用 [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) 加載轉換後的 HTML 並將其保存為 OFT 格式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中將 DOC 轉換為 OFT" %}}

- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 類打開源 DOC 文件
- 在指定輸出 HTML 文件路徑和相關的 HTML 保存選項作為參數時調用 `save` 方法。 所以你的 DOC 文件在指定的路徑被轉換成 HTML
- 現在使用 MailMessage.load 加載保存的 HTML 文件
- 使用相關文件路徑調用 save 方法。所以最後DOC被轉換了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}

- 對於 DOC 到 OFT 的轉換，需要 Python 3.5 或更高版本
- 直接從 PyPI 引用項目中的 API（[Aspose.Words](https://pypi.org/project/aspose-words/) 和 [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/)）
- 或者使用以下 pip 命令 ```pip install aspose.words``` 和 ```pip install Aspose.Email-for-Python-via-NET``` 
- 此外，基於 Microsoft Windows 或 Linux 的操作系統（有關 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 和 [Email](https://docs.aspose.com/email/python-net/system-requirements/) 的更多信息）和 Linux 檢查 gcc 和 libpython 的附加要求，並按照分步說明進行操作 [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中將 DOC 保存為 OFT" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}