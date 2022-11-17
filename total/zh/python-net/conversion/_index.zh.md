---
title: 通过 Python 进行文档转换 

description: 只需几行 Python 代码即可将 Microsoft Word 格式 DOC、DOCX 转换为 PDF、图像等以及演示幻灯片、电子邮件消息和 3D 图像。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python API 进行文档转换" h2="使用 Aspose.Words for Python 通过 .NET 转换 Microsoft<sup>&reg;</sup> Office Word、PDF、图像和各种其他格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Python API](https://products.aspose.com/total/python-net/) 加快了从头开始开发文档自动化解决方案或增强现有应用程序以创建、编辑或转换文档、演示文稿、电子邮件和 3D 文件的速度。 Python API 不仅可以处理 Microsoft Office Word 和演示文稿幻灯片，还可以处理 PDF、HTML、图像和电子邮件文件等等。 API不依赖于任何软件，是一整套文档管理和操作解决方案。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="将 Microsoft Word 转换为 PDF" %}}
Total Python API 支持多种格式的转换，例如 Microsoft Word 到 PDF、图像、Markdown 和 HTML。 API 使将 Word 文档转换为 PDF 的过程变得简单，其输出质量与 DOC、DOCX 文件一样接近文档。 过程是将 DOC 或 DOCX 文件加载到 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 对象中，然后调用 [save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) 方法，带有目标 PDF 格式及其目录路径。 就是这么简单。如果需要指定 PDF 标准，如 PDF 1.7 或 1.5，API 提供 [PdfComplaence](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfcompliance/) 枚举，用于设置[PdfSaveOptions()](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfsaveoptions/)。 

{{% blocks/products/pf/feature-page-code h3="Python - Word 到 PDF 的转换" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word 到图像的转换" %}}
文字到图片的转换是 Python API 的另一个功能。 除了转换之外，还可以轻松设置亮度、对比度、水平和垂直分辨率等各种保存选项。过程是，通过 Document 对象加载文档，然后调用具有指定路径的所需图像文件扩展名的保存方法。 为了指定各种保存选项，API 提供了 [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/)、[FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/fixedpagesaveoptions/) 或 [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/saveoptions/) 类可以从所需的场景开始使用。 下面的代码示例演示了通过应用一些附加设置来创建第一个文档页面的预览。

{{% blocks/products/pf/feature-page-code h3="Python - 文字到图像的转换" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="将 Microsoft PowerPoint 转换为 Word" %}}
Python API 支持将 Microsoft PowerPoint PPT / PPTX 转换为 Word DOC / DOCX 文件。 两个 API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) 和 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 用于执行此转换。 使用 [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) 加载 PPT / PPTX 文件。 获取 Words Document 类对象。遍历每张幻灯片，生成并插入幻灯片图像，然后通过遍历幻灯片形状来插入幻灯片文本。

{{% blocks/products/pf/feature-page-code h3="Python - PowerPoint 幻灯片到 Word 转换" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}


{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-word ppsx-to-doc pptx-to-docx ppt-to-docm pot-to-dotx potx-to-dotm potm-to-rtf pptm-to-word pps-to-docx odp-to-doc word-to-powerpoint doc-to-odp dot-to-pps docx-to-ppsm docm-to-pptm dotx-to-potm dotm-to-potx rtf-to-pot wordml-to-pptx odt-to-ppsx ott-to-pps txt-to-powerpoint md-to-ppsm" >}}