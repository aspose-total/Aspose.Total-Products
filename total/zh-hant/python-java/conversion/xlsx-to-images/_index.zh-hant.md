---
title: 使用 Python 將 XLSX 轉換為圖像
description: XLSX 到圖像 TIFF BMP PNG JPEG GIF EMF SVG 在 Python 應用程序中的轉換，無需使用 Microsoft Excel 
url: /zh-hant/python-java/conversion/xlsx-to-images/
family: total
platformtag: Python
feature: conversion
informat: XLSX
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Python 將 XLSX 轉換為圖像" h2="在您的 Python 應用程序中將 XLSX 轉換為 JPG、TIFF、BMP、PNG、GIF 圖像，而無需安裝 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}

對於試圖在應用程序中添加 XLSX 到 PNG、BMP、TIFF、JPEG 和 GIF 圖像轉換功能的 Python 開發人員。 有時需要在 Web 或桌面應用程序中嵌入 Excel 電子表格。 在這種情況下，將電子表格導出到圖像是一種方法。 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API 可以幫助將 Excel 文件導出為圖像以及自動化轉換過程。 它是通過其子 [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API 處理不同格式（包括 Microsoft Excel 格式）的各種 API 的完整包。 目前 Python Excel to Image Converter API 支持將 Excel 文件轉換為 EMF、WMF、JPEG、PNG、BMP、GIF、TIFF、SVG、GLTF、PICT、SVM 和 Office 兼容 EMF 或檢查支持的 [格式](https://docs.aspose.com/cells/python-java/supported-file-formats/)。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中將 XLSX 轉換為圖像" %}}

- 創建 [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) 類對像以加載 XLSX 文件
- 使用 [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) 類並指定輸出圖像相關選項
- 使用 [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int)) 方法訪問工作表進行轉換
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- 使用 [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)) 方法將工作表的所有頁面保存為圖像。 現在 XLSX 文件被轉換為指定路徑的圖像

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}

- 對於 XLSX 到圖像（JPG、PNG、GIF、BMP、TIFF）的轉換，請直接從 PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/)) 引用項目內的 API
- 或者使用下面的 pip 命令```pip install aspose.cells``` 
- 此外，從 [下載](https://downloads.aspose.com/cells/python-java) 部分下載 API 包 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="通過 Python 將 XLSX 轉換為圖像" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他轉換選項" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-net/conversion/excel-to-images/" name="EXCEL 印象" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/bmp1-to-images/" name="XLSX 印象" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/json-to-images/" name="JSON 印象" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/tsv-to-images/" name="TSV 印象" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xlsb-to-images/" name="XLSB 印象" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xlsm-to-images/" name="XLSM 印象" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xls-to-images/" name="XLS 印象" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xlsx-to-images/" name="XLSX 印象" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xltm-to-images/" name="XLTM 印象" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xlt-to-images/" name="XLT 印象" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xltx-to-images/" name="XLTX 印象" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}