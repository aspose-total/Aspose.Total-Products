---
title: 在 Python 中将 PDF 转换为图像
description: PDF 到图像 TIFF BMP PNG JPEG GIF SVG 在 Python 应用程序中的转换，无需使用 Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: Images
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python 将 PDF 转换为图像" h2="在您的 Python 应用程序中将 PDF 转换为 JPG、TIFF、BMP、PNG 和 GIF 图像，而无需安装 Microsoft Word<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于尝试在应用程序中添加 PDF 到 PNG、BMP、TIFF、JPEG 和 GIF 图像转换功能的 Python 开发人员。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API 可以帮助导入和导出图像和 Word 文件以及自动化转换过程。 它是处理不同格式的各种 API 的完整包。 

我们使用 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) 包中的 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API 将 PDF 添加到 JPG、PNG、GIF、BMP 和 TIFF 图像转换功能。 对于只是转换，它只是两行代码。 加载 PDF 文件并使用适当的图像路径以及相关格式的 SaveFormat 调用 save 方法。 但是如果需要设置额外的信息，比如设置水平和垂直分辨率、比例、像素格式、亮度等，那么所有这些都可以使用 [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/) 类。 使用 [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/) 可以轻松地将特定的 PDF 页面渲染为具有透明或彩色背景的图像，在渲染时指定分辨率，配置压缩等等。 根据需求，可以按照自己的需求使用，这里是另一种 [Word To Image](https://products.aspose.com/words/python-net/conversion/word-to-image/) 转换的方式。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何 在 Python 中将 PDF 转换为图像" %}}
- 使用 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 类加载源 PDF 文件
- 创建 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/).[ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/)S 的实例。
- 使用 [PageSet](https://reference.aspose.com/words/python-net/aspose.words.saving/pageset/) 指定转换的页码
- 设置属性
- 在传递输出文件路径和指定选项作为参数时调用“保存”方法。 因此，您的 PDF 文件将转换为指定路径的图像。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}

- 对于 PDF 到图像（JPG、PNG、GIF、BMP、TIFF）的转换，需要 Python 3.5 或更高版本
- 直接从 PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/)) 引用项目中的 API
- 或者使用以下 pip 命令 ```pip install aspose.words```。
- 此外，基于 Microsoft Windows 或 Linux 的操作系统（请参阅 [Words](https://docs.aspose.com/words/python-net/system-requirements/) 的更多信息）和 Linux 检查 gcc 和 libpython 的附加要求，并按照 [INSTALL](https://docs.aspose.com/words/python-net/installation/) 的分步说明进行操作。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="在 Python 中将 PDF 保存到图像 - 简单转换" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-images-simple-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="具有特定选项的 PDF 到图像转换" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "pdf-to-images-conversion.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

使用 Python API 将 PDF 转换为图像，使得可以将文档页面渲染为图像文件，以便预览、共享、可视化归档以及后续基于图像的处理。当文档内容必须在图像格式更易于分发或嵌入的环境中显示时，这非常有用。

自动化通过实现快速页面渲染、批量转换以及与缩略图、预览或文档审阅系统等可视化工作流的集成，提升了此过程的效率。它支持在数字平台上可扩展地处理文档内容。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

* **页面预览生成**  
  将 PDF 页面转换为图像，以在 Web 和移动应用中提供可视化预览。

* **文档归档**  
  将文档页面存储为图像资产，以实现快速访问和可视化参考。

* **内容共享**  
  使用图像输出进行演示、沟通或嵌入式文档快照。

* **可视化处理工作流**  
  将 PDF 页面准备为图像输入，用于分析、标注或识别系统。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* **缩略图创建流水线**  
  Python 自动化可以实时从上传的 PDF 生成图像预览。

* **批量页面渲染**  
  大型 PDF 集合可通过计划工作流转换为图像集。

* **文档查看器集成**  
  系统可以为文档浏览界面按需生成图像输出。

* **动态媒体分发**  
  自动化服务能够高效地在内容平台之间分发 PDF 派生的图像。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}