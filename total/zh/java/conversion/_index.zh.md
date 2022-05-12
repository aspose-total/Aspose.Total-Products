---
title: 通过 Java 进行文件格式转换 
url: /zh/java/conversion/
description: 只需几行 Java 代码即可转换 Microsoft Office Word、Excel、PowerPoint、Outlook、PDF、HTML、3D 图像、图表、视频格式和其他不同格式。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Java 进行文件格式转换" h2="无需使用任何其他软件即可转换 Microsoft<sup>&reg;</sup> Office 文档、PDF、图像、HTML 和多个其他文件。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java Total Library](https://products.aspose.com/total/java/) 加快了从头开始开发文档操作解决方案或增强现有应用程序以轻松处理文档管理的速度。 API 不仅可以创建、编辑和转换 Microsoft Office 文档，还可以处理 PDF、HTML、图像 TIFF、JPG、PNG、BMP 和 SVG、电子邮件文件、视频格式、3D、CAD 等等。它是文档管理和操作解决方案 API 的集合，在任何 Java J2SE、J2EE、J2ME 应用程序中没有任何软件依赖性。程序员可以轻松地在任何基于 Java 的应用程序中创建、更新、呈现、打印和转换最流行的格式。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Word 到 Excel 转换" %}}
Total API 不仅支持 Microsoft Word 格式的相互转换，还支持将 Word 转换为 Excel、PDF、HTML、Images、EPUB、Markdown 和 XPS。转换过程很简单。让我们考虑 **Word 到 Excel** 转换的情况。使用 [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) 类加载 Microsoft Word 文件，并使用 [Save method](https: //apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions))。接下来使用 [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 类打开转换后的 HTML 文档，并使用 [Save](https:// /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) 方法。
 开发者还可以将【Word转PDF】（https://products.aspose.com/words/java/conversion/word-to-pdf/）。


{{% blocks/products/pf/feature-page-code h3="Java Word 到 Excel 转换" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="将 PDF 转换为图像" %}}
API支持将PDF转换为JPEG2000、EMZ、WMZ、TGA、PSD、DXF、WMF、SVGZ、APNG、DICOM、Powerpoint、Excel等格式的图像。对于 PDF 到图像的转换，让我们将 JPG 图像视为目标文件。过程是，使用 Document 类加载 PDF 文件并初始化 [JpegDevice 类](https://apireference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) 对象并通过 [Process](https) 将 PDF 渲染为 JPEG ://apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1) 方法
使用 [Image](https://apireference.aspose.com/imaging/java/aspose.imaging/image) 类加载 JPEG 文件，最后调用 Save 方法。

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="将 PowerPoint 转换为 Excel 文件" %}}

用于将 Microsoft PowerPoint 文件转换为不同的文件，包括 Excel Word、MHTML、涉及主要 Aspose.Total for Java API 的相关子 API。将 PowerPoint 文件转换为 Excel 文档的过程，使用 [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) 类加载 PowerPoint 文件并将 **PowerPoint 转换为 HTML** 通过使用 [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) 方法。接下来使用 [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载转换后的 HTML 文档，并使用 [save](https:// /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) 方法。 还列出了 **PowerPoint 到 Word** 转换的代码。

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint 到 Excel 转换" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint 到 Word 的转换" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}