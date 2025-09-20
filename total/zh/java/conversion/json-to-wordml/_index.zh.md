---
title: 通过 Java 将 JSON 格式转换为 WORDML
description: 在不使用 Microsoft Word 的情况下在 Java 中将 JSON 解析为 WORDML
url_ignore: /zh/java/conversion/json-to-wordml/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WORDML
otherformats: FLATOPC PS RTF DOC MOBI WORDML DOCM DOT PCL DOTX EPUB OTT WORD ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 JSON 格式转换为 WORDML" h2="无需使用 Microsoft<sup>&reg;</sup> Word 即可将 JSON 解析为 WORDML 的本地 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 Java 应用程序中的 JSON 转换为 WORDML。首先，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 JSON 解析为 PDF。第二步，您可以使用 Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 PDF 转换为 WORDML。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 JSON 格式转换为 WORDML" %}}
1. 创建一个新的 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 对象并从文件中读取有效的 JSON 数据
2. 使用 [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) 类和 [Save](https://reference.aspose.com/) 将 JSON 文件导入工作表单元格/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) PDF
3. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载 PDF 文档
4. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 WORDML 格式)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 设置布局 & 将 JSON 格式转换为 WORDML" %}}
此外，API 允许您在使用 [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 将 JSON 解析为 WORDML 时为 JSON 设置布局选项。它允许您将 Array 处理为表格、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 JSON 格式转换为带水印的 WORDML" %}}
使用 API，您还可以将 JSON 解析为带有水印的 WORDML。为了给您的 WORDML 文档添加水印，您可以先将 JSON 文件转换为 PDF 并为其添加水印。为了添加水印，使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类加载新创建的 PDF 文件，创建 TextWatermarkOptions 的实例并设置它的属性，调用 Watermark.setText 方法并传递水印文本和 TextWatermarkOptions 的对象。添加水印后，您可以将文档保存到 WORDML。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
将 **JSON 转换为 WORDML** 对于从结构化数据生成 **WordprocessingML（基于 XML 的 Word 文档）** 是至关重要的。WORDML 可实现无缝数据交换、基于模板驱动的文档创建，并与基于 XML 的工作流兼容。通过将 JSON 转换为 WORDML，组织可以自动化文档生成，保持结构化内容完整性，并有效支持企业、政府和学术出版。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}

- **系统间数据交换** – 为企业应用程序提供互操作的文档格式。
- **企业文档存储** – 为长期存储维护结构化、基于 XML 的 Word 文件。
- **基于模板的生成** – 从模板自动创建标准化文档。
- **政府数字档案** – 为官方记录生成符合标准的、准备好 XML 的 Word 文档。
- **结构化学术出版** – 以结构化格式生成研究论文和教育内容。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

- **JSON 到 WordML 管道** – 自动化将结构化数据转换为基于 XML 的 Word 文档。
- **自动化 XML 文档生成** – 简化大量文档创建，同时保持结构。
- **基于 JSON 的文档工作流** – 直接从结构化数据集填充 WordML 文件。
- **企业级结构化报告** – 高效扩展跨部门的自动化、结构化文档生成。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}