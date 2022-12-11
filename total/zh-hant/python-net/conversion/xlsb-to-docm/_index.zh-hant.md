---
title: 使用 Python 將 XLSB 轉換為 DOCM
description: 在不使用 Microsoft Office 的情況下在 Python 應用程序中將 XLSB 轉換為 DOCM 

family: total
platformtag: Python
feature: conversion
informat: XLSB
outformat: DOCM
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Python 將 XLSB 轉換為 DOCM" h2="無需安裝 Microsoft Excel<sup>&reg;</sup> 或 Word，即可在 Python 應用程序中將 XLSB 轉換為 DOCM" >}}

{{% blocks/products/pf/feature-page-summary %}}

對於嘗試在應用程序中添加 XLSB 到 DOCM 轉換功能的 Python 開發人員。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以幫助自動化轉換過程。 它是處理不同格式（包括 XLSB 和 DOCM 文件）的各種 API 的完整包。

主要分兩步。 首先使用 [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API 將 XLSB 文件轉換為 HTML。 之後，通過使用 Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)，將創建的 HTML 保存為所需的 Microsoft Word 格式。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中將 XLSB 轉換為 DOCM" %}}
- **步驟1** 使用 Workbook 類打開源 XLSB 文件
- 通過提供文件名和所需目錄路徑，使用 save(file, SaveFormat.HTML) 方法將 XLSB 文件保存為 HTML
-  **第2步** 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 類的實例加載 HTML 文件
-  在指定輸出 DOCM 文件路徑時調用 `save` 方法。 這樣你的XLSB文件就在指定路徑下轉成DOCM了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}

- 對於 XLSB 到 DOCM 的轉換，需要 Python 3.5 或更高版本
- 直接從 PyPI 引用項目中的 API（[Aspose.Cells](https://pypi.org/project/aspose-cells-python/) 和 [Aspose.Words](https://pypi.org/project/aspose-words/)）
-  或者使用以下 pip 命令```pip install aspose-cells-python``` 和```pip install aspose.words```
-  此外，基於 Microsoft Windows 或 Linux 的操作系統（請參閱有關 [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) 和 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 的更多信息）和 Linux 檢查 gcc 和 libpython 的附加要求並遵循 [分步說明](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中將 XLSB 保存為 HTML - 第 1 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中將 HTML 保存為 DOCM - 第 2 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}