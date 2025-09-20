---
title: 通过 Java 将 JSON 格式转换为 EMZ
description: 在不使用 Microsoft PowerPoint 的情况下，在 Java 中将 JSON 解析为 EMZ
url_ignore: /zh/java/conversion/json-to-emz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: EMZ
otherformats: EMZ SVGZ DXF JPEG2000 PSD WMF WMZ TGA DICOM IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 JSON 格式转换为 EMZ" h2="用于在任何 Java J2SE、J2EE、J2ME 应用程序中将 JSON 格式解析为 EMZ 的 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以在任何 Java 应用程序中通过两个简单的步骤将 JSON 格式转换为 EMZ。首先，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 JSON 解析为 JPEG。之后，通过使用 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/)，您可以将 JPEG 转换为 EMZ。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 JSON 格式转换为 EMZ" %}}
1. 建[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)对象并打开JSON文件
2. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) 将 JSON 保存为 JPEG ) 方法
3. 使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载 JPEG 文档
4. 使用 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) 将文档保存为 EMZ 格式-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 设置布局并将 JSON 格式转换为 EMZ" %}}
此外，该 API 允许您使用指定的布局选项将 JSON 解析为 EMZ。为了指定布局选项，您可以使用 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 类。它允许您将数组作为表格处理、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 JSON 格式转换为带水印的 EMZ" %}}
使用 API，您还可以在 EMZ 文档中将 JSON 转换为带有水印的 EMZ。为了添加水印，您可以先将 JSON 转换为 JPEG 并在其中添加水印。为了添加水印，使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载图像文件，创建 [Graphics](https) 的对象://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics)类并用Image对象初始化，创建一个新的[Matrix](https://reference.aspose.com/imaging/java/ com.aspose.imaging/Matrix) 对象并将平移和变换设置为所需的角度，并使用 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# 添加水印drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 方法。在图像中添加水印后，您可以将 JPEG 保存为 EMZ 格式。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
将 **JSON 转换为 EMZ（压缩增强型图元文件）** 对于从结构化数据集创建 **压缩矢量图形** 至关重要。EMZ 文件以较小的文件大小存储高质量视觉内容，使其非常适合可伸缩、便携和跨平台使用。将 JSON 转换为 EMZ 可以实现将结构化数据高效渲染为专业图形、图表和示意图，同时优化存储和性能。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

- **可伸缩图表** – 从 JSON 生成数据驱动的图表用于演示和报告。
- **业务图表** – 构建组织结构图、流程图和流程可视化。
- **基于 JSON 的示意图** – 将结构化数据集转换为技术矢量插图。
- **轻量级矢量存储** – 压缩大型矢量文件以便更轻松地分发和存储。
- **跨平台图形集成** – 确保在企业应用程序和平台之间的兼容性。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

- **JSON 到 EMZ 管道** – 自动化将结构化数据转换为压缩矢量图形。
- **自动化图表压缩** – 使用预压缩的矢量输出简化工作流程。
- **基于 JSON 的报告可视化** – 直接从数据集创建轻量级、可伸缩的可视化内容。
- **企业级图形标准化** – 确保组织工作流程中一致的、压缩的矢量格式。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}