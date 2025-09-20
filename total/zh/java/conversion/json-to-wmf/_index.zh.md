---
title: 通过 Java 将 JSON 格式转换为 WMF
description: 在不使用 Microsoft PowerPoint 的情况下，在 Java 中将 JSON 解析为 WMF
url_ignore: /zh/java/conversion/json-to-wmf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WMF
otherformats: TGA DICOM JPEG2000 WMZ EMZ PSD WMF DXF SVGZ IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 JSON 格式转换为 WMF" h2="用于在任何 Java J2SE、J2EE、J2ME 应用程序中将 JSON 格式解析为 WMF 的 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以在任何 Java 应用程序中通过两个简单的步骤将 JSON 格式转换为 WMF。首先，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 JSON 解析为 JPEG。之后，通过使用 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/)，您可以将 JPEG 转换为 WMF。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 JSON 格式转换为 WMF" %}}
1. 建[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)对象并打开JSON文件
2. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) 将 JSON 保存为 JPEG ) 方法
3. 使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载 JPEG 文档
4. 使用 [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase) 将文档保存为 WMF 格式-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 设置布局并将 JSON 格式转换为 WMF" %}}
此外，该 API 允许您使用指定的布局选项将 JSON 解析为 WMF。为了指定布局选项，您可以使用 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 类。它允许您将数组作为表格处理、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 JSON 格式转换为带水印的 WMF" %}}
使用 API，您还可以在 WMF 文档中将 JSON 转换为带有水印的 WMF。为了添加水印，您可以先将 JSON 转换为 JPEG 并在其中添加水印。为了添加水印，使用 [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) 类加载图像文件，创建 [Graphics](https) 的对象://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics)类并用Image对象初始化，创建一个新的[Matrix](https://reference.aspose.com/imaging/java/ com.aspose.imaging/Matrix) 对象并将平移和变换设置为所需的角度，并使用 [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics# 添加水印drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) 方法。在图像中添加水印后，您可以将 JPEG 保存为 WMF 格式。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
将 **JSON 转换为 WMF** 对于从结构化数据生成 **Windows Metafile 图形** 至关重要。WMF 文件提供与传统 Windows 应用程序和 Office 文档兼容的可伸缩矢量图形。通过将 JSON 转换为 WMF，组织可以自动化生成图表、图表和技术插图，同时确保在企业工作流程中的一致性和兼容性。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

- **传统 Windows 应用程序** – 保持与需要 WMF 图形的旧软件的兼容性。
- **可伸缩图表** – 生成可按比例缩放的基于矢量的图表，无损失地缩放。
- **Office 文档集成** – 直接将 WMF 图形嵌入到 Word、PowerPoint 和 Excel 文件中。
- **商业图表** – 从结构化数据集自动生成图表，用于企业报告。
- **技术插图** – 为手册和工程文件创建精确的、数据驱动的插图。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

- **JSON 到 WMF 管道** – 自动化将结构化数据转换为 WMF 矢量图形。
- **自动化矢量图形生成** – 减少手动图表和插图的创建。
- **基于 JSON 的图表渲染** – 直接从数据集中填充图表和可视化内容。
- **企业级插图工作流程** – 将 WMF 生成集成到企业文档流程中。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}