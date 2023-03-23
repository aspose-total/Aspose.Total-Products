---
title: 使用 Python 将 XLTM 转换为图像
description: XLTM 到图像 TIFF BMP PNG JPEG GIF EMF SVG 在 Python 应用程序中的转换，无需使用 Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: XLTM
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Python 将 XLTM 转换为图像" h2="在您的 Python 应用程序中将 XLTM 转换为 JPG、TIFF、BMP、PNG、GIF 图像，而无需安装 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于试图在应用程序中添加 XLTM 到 PNG、BMP、TIFF、JPEG 和 GIF 图像转换功能的 Python 开发人员。 有时需要在 Web 或桌面应用程序中嵌入 Excel 电子表格。 在这种情况下，将电子表格导出到图像是一种方法。 [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API 可以帮助将 Excel 文件导出为图像以及自动化转换过程。 它是通过其子 [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API 处理不同格式（包括 Microsoft Excel 格式）的各种 API 的完整包。 目前 Python Excel to Image Converter API 支持将 Excel 文件转换为 EMF、WMF、JPEG、PNG、BMP、GIF、TIFF、SVG、GLTF、PICT、SVM 和 Office 兼容 EMF 或检查支持的 [格式](https://docs.aspose.com/cells/python-java/supported-file-formats/)。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 Python 中将 XLTM 转换为图像" %}}

- 创建 [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) 类对象以加载 XLTM 文件
- 使用 [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) 类并指定输出图像相关选项
- 使用 [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int)) 方法访问工作表进行转换
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- 使用 [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)) 方法将工作表的所有页面保存为图像。 现在 XLTM 文件被转换为指定路径的图像

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 XLTM 到图像（JPG、PNG、GIF、BMP、TIFF）的转换，请直接从 PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/)) 引用项目内的 API
- 或者使用下面的 pip 命令```pip install aspose.cells``` 
- 此外，从 [下载](https://releases.aspose.com/cells/python-java) 部分下载 API 包 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="通过 Python 将 XLTM 转换为图像" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}