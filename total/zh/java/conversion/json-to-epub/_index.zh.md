---
title: 通过 Java 将 JSON 格式转换为 EPUB
description: 在不使用 Microsoft Word 的情况下在 Java 中将 JSON 解析为 EPUB
url_ignore: /zh/java/conversion/json-to-epub/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: EPUB
otherformats: DOTX EPUB PCL MOBI WORDML OTT FLATOPC PS DOT DOC WORD RTF ODT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 JSON 格式转换为 EPUB" h2="无需使用 Microsoft<sup>&reg;</sup> Word 即可将 JSON 解析为 EPUB 的本地 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 Java 应用程序中的 JSON 转换为 EPUB。首先，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 JSON 解析为 PDF。第二步，您可以使用 Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 PDF 转换为 EPUB。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 JSON 格式转换为 EPUB" %}}
1. 创建一个新的 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 对象并从文件中读取有效的 JSON 数据
2. 使用 [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) 类和 [Save](https://reference.aspose.com/) 将 JSON 文件导入工作表单元格/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) PDF
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 PDF 文档
4. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 EPUB 格式)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 设置布局 & 将 JSON 格式转换为 EPUB" %}}
此外，API 允许您在使用 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 将 JSON 解析为 EPUB 时为 JSON 设置布局选项。它允许您将 Array 处理为表格、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 JSON 格式转换为带水印的 EPUB" %}}
使用 API，您还可以将 JSON 解析为带有水印的 EPUB。为了给您的 EPUB 文档添加水印，您可以先将 JSON 文件转换为 PDF 并为其添加水印。为了添加水印，使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载新创建的 PDF 文件，创建 TextWatermarkOptions 的实例并设置它的属性，调用 Watermark.setText 方法并传递水印文本和 TextWatermarkOptions 的对象。添加水印后，您可以将文档保存到 EPUB。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
将 **JSON 转换为 EPUB** 对于从结构化数据集生成 **数字电子书** 至关重要。EPUB 文件提供了一种广泛支持的可重排格式，可在电子阅读器、移动设备和学习平台上传递知识。通过将 JSON 转换为 EPUB，组织可以自动化内容发布，创建交互式电子学习材料，并以便携数字格式分发标准化的知识资源。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

- **自动化发布** – 将数据集转换为可阅读的数字电子书。
- **电子学习材料** – 以 EPUB 格式提供交互式结构化课程资料。
- **数据驱动的电子书** – 直接从 JSON 输入生成动态出版物。
- **研究出版物** – 将学术发现和结构化研究成果发布为电子书。
- **企业知识分发** – 通过数字图书馆标准化内部知识共享。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

- **JSON 到 EPUB 流水线** – 从结构化数据源自动创建电子书。
- **实时电子书生成** – 直接从实时 JSON 源生成最新出版物。
- **自动化课程资料发布** – 为机构简化电子学习材料制作流程。
- **数字图书馆集成** – 将基于 JSON 的 EPUB 集成到企业和学术知识库中。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}