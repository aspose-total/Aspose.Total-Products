---
title: 通过 Java 将 PS 转换为 DXF
description: 在您的 Java 应用程序中将 PS 文件导出为 DXF，而无需使用任何第三方应用程序
url_ignore: /zh/java/conversion/ps-to-dxf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: DXF
otherformats: SVGZ EMZ PSD IMAGE TGA JPEG2000 WMZ  DXF WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 PS 转换为 DXF" h2="在任何 Java J2SE、J2EE、J2ME 应用程序中将 PS 文件导出为 DXF，无需使用 Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
您可以通过两个简单的步骤将 ps 文件转换为 Java 中的 DXF 图像。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 PS 导出为 JPEG。之后，通过使用 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) 图像处理 API，您可以将 JPEG 渲染为 DXF。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 包。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 PS 导出为 DXF" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开PS文件
2. 始化JpegDevice类对象，使用[Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) 方法
3. 使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载 JPEG 文件
4. 使用 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) 将文档保存为 DXF 格式-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 在单个文件中将 PS 转换为 DXF" %}}
该 API 还允许您将 PS 文件导出为 DXF 到单个文件。为了转换所有页面，您可以先将 PS 文档渲染为一个 TIFF 文件，然后再将 TIFF 文件导出为 DXF。您可以使用 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 类打开输入文件并创建 Resolution、TiffSettings 和 TIFF 设备对象。您可以使用 [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- 获取单个 TIFF 图像[TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) 类的 java.io.OutputStream-) 方法。最后，您可以使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载 TIFF 文件并使用 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) 方法。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 PS 转换为带水印的 DXF" %}}
使用 API，您还可以在 DXF 文档中将 PS 文件导出为带有水印的 DXF。为了添加水印，您可以先将 PS 转换为 JPEG 并在其中添加水印。为了添加水印，使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载图像文件，创建 [Graphics](https) 的对象://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics)类并用Image对象初始化，创建一个新的[Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) 对象并将平移和变换设置为所需的角度，并使用 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# 添加水印drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 方法。在图像中添加水印后，您可以将 JPEG 保存为 DXF 格式。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 PS 转换和旋转为 DXF 文件" %}}
使用 API，您还可以根据需要旋转输出的 DXF 图像。 Image.rotateFlip 方法可用于将图像旋转 90/180/270 度并水平或垂直翻转图像。该库提供了简单的方法来执行复杂的操作，同时封装了所有丑陋的细节。您可以指定要应用于图像的旋转和翻转类型。为了旋转和翻转图像，您可以使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载转换后的 JPEG 图像并调用 Image。 rotateFlip 方法，同时指定适当的 [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

将PS（PostScript）文件转换为DXF（Drawing Exchange Format）可将基于矢量的精确设计从PostScript文档导入到CAD（计算机辅助设计）应用程序中。这种转换非常适合需要可编辑技术图纸的工程师、建筑师和设计师。

{{% blocks/products/pf/agp/feature-section-col title="主要用途" %}}

* 将基于PS的原理图转换为CAD兼容的DXF文件。
* 将建筑平面图从PostScript布局转换为用于3D建模的文件。
* 将工程图导入AutoCAD以进行进一步的设计优化。
* 在支持DXF的平台间共享技术矢量设计。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* 在设计和工程流程中批量进行PS到DXF的转换。
* 与CAD工作流自动化集成，实现快速项目迭代。
* 自动将PS生成的图表转换为施工文档。
* 为协作设计团队提供基于云的DXF生成。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}