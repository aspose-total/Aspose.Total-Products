---
title: 通过 Java 将 JSON 格式转换为 PPSX
description: 在不使用 Microsoft PowerPoint 的情况下，在 Java 中将 JSON 解析为 PPSX
url_ignore: /zh/java/conversion/json-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSX
otherformats: PPT POTM PPTM PPS PPSX POT POWERPOINT OTP POTX PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 JSON 格式转换为 PPSX" h2="无需使用 Microsoft<sup>&reg;</sup> PowerPoint 即可将 JSON 格式解析为 PPSX 的 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以在任何 Java 应用程序中通过两个简单的步骤将 JSON 格式转换为 PPSX。首先，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 JSON 解析为 PPTX。之后，通过使用 [Aspose.Slides for Java](https://products.aspose.com/slides/java/)，您可以将 PPTX 转换为 PPSX。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 JSON 格式转换为 PPSX" %}}
1. 建[Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)对象并打开JSON文件
2. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) 将 JSON 保存为 PPTX ) 方法
3. 用[Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)类加载PPTX文档
4. 使用[save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)方法将文档保存为PPSX格式
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 设置布局并将 JSON 格式转换为 PPSX" %}}
此外，该 API 允许您使用指定的布局选项将 JSON 解析为 PPSX。为了指定布局选项，您可以使用 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 类。它允许您将数组作为表格处理、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 JSON 格式转换为带水印的 PPSX" %}}
使用 API，您还可以将 JSON 转换为带水印的 PPSX。为了给你的PPSX文档添加水印，你可以先将JSON解析为PPTX并添加水印。为了添加水印，使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 类加载新创建的 PPTX 文件，遍历所有幻灯片，添加文本使用 addTextFrame，设置所有相关选项，如颜色、填充类型等，并可以将文档保存到 PPSX。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
将 **JSON 转换为 PPSX** 对于从结构化数据生成 **现代 PowerPoint 幻灯片文件** 至关重要。PPSX 文件提供全屏、即时播放的幻灯片，与当代 PowerPoint 版本兼容，使组织能够自动化演示文稿的创建，保持品牌一致性，并高效地传递数据驱动内容。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

- **商务会议** – 为高管和团队演示制作标准化、专业的幻灯片。
- **教育讲座** – 直接从结构化数据集生成讲座幻灯片和课程资料。
- **产品演示** – 为展示产品和服务构建动态、即时呈现的幻灯片。
- **营销活动** – 自动创建品牌幻灯片演示，用于促销活动。
- **研究数据展示** – 将结构化研究数据转化为视觉吸引力的幻灯片。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

- **JSON 到 PPSX 流水线** – 简化结构化数据转换为现代幻灯片文件的流程。
- **自动化幻灯片创建** – 减少手动幻灯片设计和格式化工作。
- **企业级报告幻灯片** – 在各部门生成标准化的演示文稿。
- **基于 JSON 的品牌幻灯片** – 在自动化幻灯片中嵌入数据并保持企业品牌。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}