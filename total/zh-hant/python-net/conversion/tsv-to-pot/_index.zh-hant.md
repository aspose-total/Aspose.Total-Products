---
title: 使用 Python 將 TSV 轉換為 POT
description: 在不使用 Microsoft Office 的情況下在 Python 應用程序中將 TSV 轉換為 POT 

family: total
platformtag: Python
feature: conversion
informat: TSV
outformat: POT
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Python 將 TSV 轉換為 POT" h2="無需安裝 Microsoft Excel<sup>&reg;</sup> 或 PowerPoint，即可在 Python 應用程序中將 TSV 轉換為 POT" >}}

{{% blocks/products/pf/feature-page-summary %}}

對於嘗試在應用程序中添加 TSV 到 POT 轉換功能的 Python 開發人員, [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以幫助自動化轉換過程。 它是處理不同格式（包括 TSV 和 POT 文件）的各種 API 的完整包.

主要分兩步. 首先使用[Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API將TSV文件轉換為PDF. 之後使用 PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/)，將創建的 PDF 保存為所需的 Microsoft PowerPoint 格式. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中將 TSV 轉換為 POT" %}}
- **步驟1** 使用Workbook類實例打開源TSV文件 
- 通過提供文件名和所需目錄路徑，使用 save 方法將 TSV 文件保存為 PDF
-  **第2步** 使用 [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) 類加載 PDF 文件
-  指定輸出 POT 文件路徑時調用 [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) 方法. 這樣你的TSV文件就在指定路徑下轉成POT了

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}

- 對於 TSV 到 POT 的轉換，需要 Python 3.5 或更高版本
- 直接從 PyPI 引用項目中的 API（[Aspose.Cells](https://pypi.org/project/aspose-cells-python/) 和 [Aspose.Slides](https://pypi.org/project/Aspose.Slides/)）
-  或者使用以下 pip 命令```pip install aspose-cells-python``` 和 ```pip install aspose.slides```
-  此外，基於 Microsoft Windows 或 Linux 的操作系統（更多信息請參見 [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) 和 [Slides](https://docs.aspose.com/slides/python-net/system-requirements/)）
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中將 TSV 保存為 PDF - 第 1 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中將 PDF 保存為 POT - 第 2 步" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}