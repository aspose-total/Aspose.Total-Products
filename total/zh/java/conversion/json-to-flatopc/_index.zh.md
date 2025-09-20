---
title: 通过 Java 将 JSON 格式转换为 FLATOPC
description: 在不使用 Microsoft Word 的情况下在 Java 中将 JSON 解析为 FLATOPC
url_ignore: /zh/java/conversion/json-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: FLATOPC
otherformats: EPUB ODT PCL WORD RTF DOC DOCM DOTX DOT MOBI PS FLATOPC WORDML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 JSON 格式转换为 FLATOPC" h2="无需使用 Microsoft<sup>&reg;</sup> Word 即可将 JSON 解析为 FLATOPC 的本地 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 Java 应用程序中的 JSON 转换为 FLATOPC。首先，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 JSON 解析为 PDF。第二步，您可以使用 Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 PDF 转换为 FLATOPC。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 JSON 格式转换为 FLATOPC" %}}
1. 创建一个新的 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 对象并从文件中读取有效的 JSON 数据
2. 使用 [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) 类和 [Save](https://reference.aspose.com/) 将 JSON 文件导入工作表单元格/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) PDF
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 PDF 文档
4. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 FLATOPC 格式)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 设置布局 & 将 JSON 格式转换为 FLATOPC" %}}
此外，API 允许您在使用 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 将 JSON 解析为 FLATOPC 时为 JSON 设置布局选项。它允许您将 Array 处理为表格、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 JSON 格式转换为带水印的 FLATOPC" %}}
使用 API，您还可以将 JSON 解析为带有水印的 FLATOPC。为了给您的 FLATOPC 文档添加水印，您可以先将 JSON 文件转换为 PDF 并为其添加水印。为了添加水印，使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载新创建的 PDF 文件，创建 TextWatermarkOptions 的实例并设置它的属性，调用 Watermark.setText 方法并传递水印文本和 TextWatermarkOptions 的对象。添加水印后，您可以将文档保存到 FLATOPC。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
将**JSON转换为FLATOPC**对于将**结构化数据转换为OpenXML Word格式**至关重要。FLATOPC提供了Word文档的标准化基于XML的表示形式，非常适合数据交换、存档和自动化工作流。通过将JSON转换为FLATOPC，组织可以将结构化数据集与WordprocessingML桥接，实现无缝互操作性、合规性和企业级文档生成。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

- **存档文档** – 将结构化数据保存在长期的基于XML的Word格式中。
- **企业工作流** – 将基于JSON的内容集成到企业文档系统中。
- **系统之间的互操作性** – 在应用程序之间交换标准化的Word内容。
- **法律框架** – 从结构化来源生成符合合规要求的Word文档。
- **基于数据的Word内容** – 直接从实时或存储的JSON数据集生成Word文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

- **JSON到FLATOPC管道** – 自动化将结构化数据集转换为OpenXML Word格式。
- **自动化文档存档** – 直接从JSON记录构建基于XML的Word存档。
- **云就绪的JSON到Word标准化** – 在云环境中实现标准化文档生成。
- **大规模文档转换** – 将大量JSON文件处理为FLATOPC，用于企业文档生态系统。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}