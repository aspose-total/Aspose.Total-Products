---
title: 在 Python 中將 DOTX 轉換為 POTX
description: 在 Python 應用程序中將 DOTX 轉換為 POTX，而無需使用 Microsoft Word 或 PowerPoint 
url: /zh-hant/python-net/conversion/dotx-to-potx/
family: total
platformtag: Python
feature: conversion
informat: DOTX
outformat: POTX
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 將 DOTX 轉換為 POTX" h2="無需安裝 Microsoft Word<sup>&reg;</sup> 或 PowerPoint 即可在 Python 應用程序中將 DOTX 轉換為 POTX" >}}

{{% blocks/products/pf/feature-page-summary %}}

對於 Python 開發人員，誰正在嘗試在應用程序中添加 DOTX 到 POTX 轉換功能？ [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以幫助自動化轉換過程。它是處理不同格式的各種 API 的完整包。 所以 **如何在 Python 中將 DOTX 轉換為 POTX？**

主要分兩步。 首先使用 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API 將 DOTX 文件轉換為 PDF。 之後使用 PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/)，將創建的 PDF 保存為 POTX 格式的演示文稿。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在 Python 中將 DOTX 轉換為 POTX" %}}
- **步驟1** 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 類打開源 DOTX 文件
- 通過提供文件名和所需的目錄路徑，使用 [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) 方法將 DOTX 文件保存為 PDF。
-  **第2步** 使用 [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) 類的實例加載 PDF 文件
-  在指定輸出文件路徑和 SaveFormat.POTX 作為參數時調用 `save` 方法。 因此，您的 DOTX 文件將在指定路徑轉換為 POTX。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}

- 對於 DOTX 到 POTX 的轉換，需要 Python 3.5 或更高版本
- 直接從 PyPI（[Aspose.Slides](https://pypi.org/project/Aspose.Slides/) 和 [Aspose.Words](https://pypi.org/project/aspose-words/)）引用項目中的 API 或
- 使用以下 pip 命令 ```pip install aspose.slides``` 和 ```pip install aspose.words```。而且，
- 基於 Microsoft Windows 或 Linux 的操作系統（請參閱更多有關 [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) 和 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 的信息）和 Linux 檢查 gcc 和 libpython 的其他要求，並按照 [INSTALL](https://docs.aspose.com/words/python-net/installation/) 的分步說明進行操作。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中將 DOTX 保存為 PDF - 第 1 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中將 PDF 保存為 POTX - 第 2 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}