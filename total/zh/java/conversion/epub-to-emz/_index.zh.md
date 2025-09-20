---
title: 通过 Java 将 EPUB 转换为 EMZ
description: 在您的 Java 应用程序中将 EPUB 文件导出为 EMZ，而无需使用任何第三方应用程序
url_ignore: /zh/java/conversion/epub-to-emz/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: EMZ
otherformats: JPEG2000 DXF WMZ IMAGE SVGZ TGA WMF PSD  EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 EPUB 转换为 EMZ" h2="在任何 Java J2SE、J2EE、J2ME 应用程序中将 EPUB 文件导出为 EMZ，无需使用 Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
您可以通过两个简单的步骤将 epub 文件转换为 Java 中的 EMZ 图像。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 EPUB 导出为 JPEG。之后，通过使用 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) 图像处理 API，您可以将 JPEG 渲染为 EMZ。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 包。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 EPUB 导出为 EMZ" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开EPUB文件
2. 始化JpegDevice类对象，使用[Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) 方法
3. 使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载 JPEG 文件
4. 使用 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) 将文档保存为 EMZ 格式-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 在单个文件中将 EPUB 转换为 EMZ" %}}
该 API 还允许您将 EPUB 文件导出为 EMZ 到单个文件。为了转换所有页面，您可以先将 EPUB 文档渲染为一个 TIFF 文件，然后再将 TIFF 文件导出为 EMZ。您可以使用 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 类打开输入文件并创建 Resolution、TiffSettings 和 TIFF 设备对象。您可以使用 [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- 获取单个 TIFF 图像[TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) 类的 java.io.OutputStream-) 方法。最后，您可以使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载 TIFF 文件并使用 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) 方法。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 EPUB 转换为带水印的 EMZ" %}}
使用 API，您还可以在 EMZ 文档中将 EPUB 文件导出为带有水印的 EMZ。为了添加水印，您可以先将 EPUB 转换为 JPEG 并在其中添加水印。为了添加水印，使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载图像文件，创建 [Graphics](https) 的对象://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics)类并用Image对象初始化，创建一个新的[Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) 对象并将平移和变换设置为所需的角度，并使用 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# 添加水印drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 方法。在图像中添加水印后，您可以将 JPEG 保存为 EMZ 格式。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 EPUB 转换和旋转为 EMZ 文件" %}}
使用 API，您还可以根据需要旋转输出的 EMZ 图像。 Image.rotateFlip 方法可用于将图像旋转 90/180/270 度并水平或垂直翻转图像。该库提供了简单的方法来执行复杂的操作，同时封装了所有丑陋的细节。您可以指定要应用于图像的旋转和翻转类型。为了旋转和翻转图像，您可以使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载转换后的 JPEG 图像并调用 Image。 rotateFlip 方法，同时指定适当的 [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
将 **EPUB 转换为 EMZ** 对于从数字出版物生成 **压缩的 Windows 图元文件** 至关重要。EMZ 文件提供了一种可伸缩且压缩的图形格式，使其成为优化电子书中插图、图表和基于矢量的内容的理想选择。通过将 EPUB 视觉内容转换为 EMZ，出版商、设计师和企业可以确保高质量的图形，这些图形轻巧、便携，并且适用于印刷和数字工作流程。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}
- **出版图形优化** – 在保持可伸缩图像质量的同时减小文件大小。
- **跨平台电子书插图** – 为电子书阅读器提供通用支持的图形。
- **高质量印刷工作流** – 为专业印刷准备出版图形。
- **营销材料生成** – 将插图重新制作为推广资产。
- **可伸缩图像的归档** – 存储压缩的、分辨率独立的图形以供长期使用。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}
- **EPUB 到 EMZ 转换流水线** – 自动从电子书中提取可伸缩图形。
- **自动化图元文件提取** – 瞬间将嵌入的插图转换为 EMZ 格式。
- **出版工作流程压缩** – 优化大规模出版项目中的图像处理。
- **企业级图形自动化** – 在组织中标准化压缩的图元文件生成。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}