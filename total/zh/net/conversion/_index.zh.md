---
title: 通过 C# 进行文件格式转换 
url: /zh/net/conversion/
description: 只需几行 C# 代码即可转换 Microsoft Word、Excel、PowerPoint、Outlook、PDF、HTML、3D 图像、图表、视频格式和许多其他流行文件。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 C# 进行文件格式转换 .NET" h2="无需使用任何其他软件即可转换 Microsoft<sup>&reg;</sup> Office 文件、PDF、图像、HTML 和其他不同格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[.NET 总库](https://products.aspose.com/total/net/) 加快从头开始开发文档管理解决方案或增强现有应用程序以轻松处理文档操作。 API 不仅可以管理 Microsoft Office 文档，还可以处理 PDF、HTML、图像 TIFF、JPG、PNG、BMP 和 SVG、电子邮件文件、视频格式、GIS 数据格式等等。它是一套完整的文档管理和操作解决方案 API，没有任何软件依赖项。程序员可以轻松地在任何基于 .NET 的应用程序中创建、更新、呈现、打印和转换最流行的格式。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="将 Word 转换为 PDF" %}}
Total API 不仅支持 Microsoft Word 格式的相互转换，还支持将 Word 转换为 PDF、HTML、图像、EPUB、Markdown 和 XPS。转换过程很简单。通过 Document 类加载 Document 并使用目标格式调用 Save 方法。就是这么简单。 **Word转PDF**代码集成前，开发者可以查看【转换结果】（https://products.aspose.com/words/net/conversion/word-to-pdf/）


{{% blocks/products/pf/feature-page-code h3="C# - Word 到 PDF 的转换" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="将 PDF 转换为图像" %}}
API 支持将 PDF 转换为图像、Powerpoint、Excel 等格式。对于 PDF 到图像的转换，让我们将 JPG 图像视为目标文件。过程是，使用 Document 类加载 PDF 文件并初始化 [JpegDevice 类](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) 对象并通过 [Process](https) 将 PDF 渲染为 JPEG ://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) 方法
使用 [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) 类加载 JPEG 文件，最后调用 Save 方法。

{{% blocks/products/pf/feature-page-code h3="C# - PDF 到图像的转换" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="将 Excel 转换为 Word 和 PowerPoint" %}}

用于将 Microsoft Excel 格式转换为包括 Word 和 PowerPoint 在内的不同文件，涉及主 Aspose.Total for .NET API 的相关子 API。 Excel文件转Word文件的过程，使用[Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)类加载EXCEL文件，先将EXCEL转为PDF，SaveFormat设置为Auto。然后使用 Document 类加载转换后的 PDF 文件并调用 Save 方法并将 Doc、Docx 设置为 SaveFormat。还列出了用于 Microsoft **Excel 到 Powerpoint** 转换的代码。

{{% blocks/products/pf/feature-page-code h3="C# - JSON 到 Excel 转换" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - Excel 到 JSON 的转换" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}