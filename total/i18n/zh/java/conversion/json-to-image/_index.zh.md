---
title: 通过 Java 将 JSON 格式转换为 IMAGE
description: 在不使用 Microsoft PowerPoint 的情况下，在 Java 中将 JSON 解析为 IMAGE
url: /zh/java/conversion/json-to-image/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: JPEG2000
otherformats: DICOM EMZ TGA IMAGE SVGZ JPEG2000 WMF WMZ PSD DXF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 JSON 格式转换为 IMAGE" h2="用于在任何 Java J2SE、J2EE、J2ME 应用程序中将 JSON 格式解析为 IMAGE 的 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以在任何 Java 应用程序中通过两个简单的步骤将 JSON 格式转换为 IMAGE。首先，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 JSON 解析为 JPEG。之后，通过使用 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/)，您可以将 JPEG 转换为 IMAGE。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 JSON 格式转换为 IMAGE" %}}
1.新建[Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)对象并打开JSON文件
2. 使用 [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) 将 JSON 保存为 JPEG ） 方法
3. 使用 [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载 JPEG 文档
4. 使用 [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) 将文档保存为 IMAGE 格式-） 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。。

或者，您可以从 [下载](https://downloads.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 设置布局并将 JSON 格式转换为 IMAGE" %}}
此外，该 API 允许您使用指定的布局选项将 JSON 解析为 IMAGE。为了指定布局选项，您可以使用 [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 类。它允许您将数组作为表格处理、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 JSON 格式转换为带水印的 IMAGE" %}}
使用 API，您还可以在 IMAGE 文档中将 JSON 转换为带有水印的 IMAGE。为了添加水印，您可以先将 JSON 转换为 JPEG 并在其中添加水印。为了添加水印，使用 [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载图像文件，创建 [Graphics](https) 的对象://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics)类并用Image对象初始化，创建一个新的[Matrix](https://apireference.aspose.com/imaging/java/ com.aspose.imaging/Matrix) 对象并将平移和变换设置为所需的角度，并使用 [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics# 添加水印drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 方法。在图像中添加水印后，您可以将 JPEG 保存为 IMAGE 格式。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-jpeg2000/" name="JSON 到 JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-emz/" name="JSON 到 EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-psd/" name="JSON 到 PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-wmf/" name="JSON 到 WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-wmz/" name="JSON 到 WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-dxf/" name="JSON 到 DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-image/" name="JSON 到 IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-svgz/" name="JSON 到 SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-dicom/" name="JSON 到 DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-tga/" name="JSON 到 TGA" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}