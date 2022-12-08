---
title: 通过 Java 将 MHTML 转换为 JPEG2000
description: 在您的 Java 应用程序中将 MHTML 文件导出为 JPEG2000，而无需使用任何第三方应用程序
url_ignore: /zh/java/conversion/mhtml-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: JPEG2000
otherformats: JPEG2000 PSD EMZ SVGZ TGA WMZ DXF  IMAGE WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 MHTML 转换为 JPEG2000" h2="在任何 Java J2SE、J2EE、J2ME 应用程序中将 MHTML 文件导出为 JPEG2000，无需使用 Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
您可以通过两个简单的步骤将 mhtml 文件转换为 Java 中的 JPEG2000 图像。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 MHTML 导出为 JPEG。之后，通过使用 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) 图像处理 API，您可以将 JPEG 渲染为 JPEG2000。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 包。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 MHTML 导出为 JPEG2000" %}}
1.使用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开MHTML文件
2.初始化JpegDevice类对象，使用[Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) 方法
3. 使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载 JPEG 文件
4. 使用 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) 将文档保存为 JPEG2000 格式-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从基于 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 的项目轻松地使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 在单个文件中将 MHTML 转换为 JPEG2000" %}}
该 API 还允许您将 MHTML 文件导出为 JPEG2000 到单个文件。为了转换所有页面，您可以先将 MHTML 文档渲染为一个 TIFF 文件，然后再将 TIFF 文件导出为 JPEG2000。您可以使用 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 类打开输入文件并创建 Resolution、TiffSettings 和 TIFF 设备对象。您可以使用 [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- 获取单个 TIFF 图像[TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) 类的 java.io.OutputStream-) 方法。最后，您可以使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载 TIFF 文件并使用 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) 方法。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 MHTML 转换为带水印的 JPEG2000" %}}
使用 API，您还可以在 JPEG2000 文档中将 MHTML 文件导出为带有水印的 JPEG2000。为了添加水印，您可以先将 MHTML 转换为 JPEG 并在其中添加水印。为了添加水印，使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载图像文件，创建 [Graphics](https) 的对象://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics)类并用Image对象初始化，创建一个新的[Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) 对象并将平移和变换设置为所需的角度，并使用 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# 添加水印drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 方法。在图像中添加水印后，您可以将 JPEG 保存为 JPEG2000 格式。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 MHTML 转换和旋转为 JPEG2000 文件" %}}
使用 API，您还可以根据需要旋转输出的 JPEG2000 图像。 Image.rotateFlip 方法可用于将图像旋转 90/180/270 度并水平或垂直翻转图像。该库提供了简单的方法来执行复杂的操作，同时封装了所有丑陋的细节。您可以指定要应用于图像的旋转和翻转类型。为了旋转和翻转图像，您可以使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载转换后的 JPEG 图像并调用 Image。 rotateFlip 方法，同时指定适当的 [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType)。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-emz/" name="MHTML 到 EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-tga/" name="MHTML 到 TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-jpeg2000/" name="MHTML 到 JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-image/" name="MHTML 到 IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-psd/" name="MHTML 到 PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-wmz/" name="MHTML 到 WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-svgz/" name="MHTML 到 SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to/" name="MHTML 到" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-wmf/" name="MHTML 到 WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-dxf/" name="MHTML 到 DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-dicom/" name="MHTML 到 DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}