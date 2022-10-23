---
title: 通过 Python 转换 Microsoft Excel 电子表格和 Visio 格式 
url: /zh/python-java/conversion/
description: 转换 Excel 文件 XLS XLSX XLSM XLSB XLTX XLTM CSV 等以及 Visio 格式 VSDX VSX VTX VDX VSSX VSTX VSDM VSSM VSTM 等只需几行 Python 代码。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python API 进行 Microsoft Excel 和 Visio 文件转换" h2="使用 Aspose.Total for Python 通过 Java 转换 Microsoft<sup>&reg;</sup> Excel 和 Visio 文档。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) 是一个完整的 API 包，可加快从头开始开发图表、文件和报告自动化解决方案或增强现有应用程序以将 Visio 图表转换为 PDF、HTML 和图像以及将 Excel 报告呈现为各种格式，包括 Web、图像和固定布局格式。 API不依赖于任何软件，是一整套文档管理和操作解决方案。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="转换 Microsoft Excel 电子表格" %}}

Total API 还支持将 Microsoft Excel 文件转换为 PDF、图像、CSV、JSON 等格式。 过程很简单。 通过 [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) 类加载文件并使用相关文件路径调用 save 方法。 Save 是具有三个选项的重载方法。仅提供文件作为参数或提供 [saveFormat](https://reference.aspose.com/cells/python-java/asposecells.api/SaveFormat) 或 [saveOptions](https://reference.aspose.com/cells/python-java/asposecells.api/SaveOptions) 作为第二个参数。 根据目标格式，可以使用少数保存选项类，例如 [DifSaveOptions](https://reference.aspose.com/cells/python-java/asposecells.api/DifSaveOptions)、[DocxSaveOptions](https://reference.aspose.com/cells/python-java/asposecells.api/DocxSaveOptions)、[HtmlSaveOptions](https://reference.aspose.com/cells/python-java/asposecells.api/HtmlSaveOptions)、[ImageSaveOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageSaveOptions)、[JsonSaveOptions](https://reference.aspose.com/cells/python-java/asposecells.api/JsonSaveOptions)、[MarkdownSaveOptions](https://reference.aspose.com/cells/python-java/asposecells.api/MarkdownSaveOptions)、[OdsSaveOptions](https://reference.aspose.com/cells/python-java/asposecells.api/OdsSaveOptions) 和更多相关类。

{{% blocks/products/pf/feature-page-code h3="Python - 微软 Excel 转换" %}}

{{< gist "aspose-com-gists" "6db1506a363937442c2d15705118f261" "convert-excel-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="将 Microsoft Visio 文件保存为各种格式" %}}
Total Python API 支持 Visio 格式的相互转换以及转换为图像、SVG、HTML 和 PDF 格式。 对于 Visio 格式的转换，只需两行代码。 首先通过 [Diagram](https://reference.aspose.com/diagram/python-java/asposediagram.api/Diagram) 类加载 VSDX、VSX、VTX、VDX 或任何源 visio 格式，然后调用带有文件路径和相关 [SaveFileFormat](https://reference.aspose.com/diagram/python-java/asposediagram.api/SaveFileFormat) 枚举类型的保存方法。  

{{% blocks/products/pf/feature-page-code h3="Python - Visio 格式转换" %}}

{{< gist "aspose-com-gists" "b70e96cfdacd18332dfe0d2ed137ee53" "convert-visio-files-to-images-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}