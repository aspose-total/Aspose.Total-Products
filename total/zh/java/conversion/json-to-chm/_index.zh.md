---
title: 通过 Java 将 JSON 格式转换为 CHM
description: 在不使用 Microsoft Word 的情况下在 Java 中将 JSON 解析为 CHM
url: /zh/java/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: FLATOPC DOCM WORD WORDML ODT RTF DOC MOBI OTT DOTX PCL DOT EPUB PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 JSON 格式转换为 CHM" h2="无需使用 Microsoft<sup>&reg;</sup> Word 即可将 JSON 解析为 CHM 的本地 Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 Java 应用程序中的 JSON 转换为 CHM。首先，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 JSON 解析为 PDF。第二步，您可以使用 Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) 将 PDF 转换为 CHM。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 JSON 格式转换为 CHM" %}}
1. 创建一个新的 [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 对象并从文件中读取有效的 JSON 数据
2. 使用 [JsonUtility](https://apireference.aspose.com/cells/java/com.aspose.cells/JsonUtility) 类和 [Save](https://apireference.aspose.com/) 将 JSON 文件导入工作表单元格/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) PDF
3. 使用 [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) 类加载 PDF 文档
4. 使用 [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将文档保存为 CHM 格式）） 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。。

或者，您可以从 [下载](https://downloads.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 设置布局 & 将 JSON 格式转换为 CHM" %}}
此外，API 允许您在使用 [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) 将 JSON 解析为 CHM 时为 JSON 设置布局选项。它允许您将 Array 处理为表格、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 JSON 格式转换为带水印的 CHM" %}}
使用 API，您还可以将 JSON 解析为带有水印的 CHM。为了给您的 CHM 文档添加水印，您可以先将 JSON 文件转换为 PDF 并为其添加水印。为了添加水印，使用 [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) 类加载新创建的 PDF 文件，创建 TextWatermarkOptions 的实例并设置它的属性，调用 Watermark.setText 方法并传递水印文本和 TextWatermarkOptions 的对象。添加水印后，您可以将文档保存到 CHM。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-flatopc/" name="JSON 到 FLA到PC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-docm/" name="JSON 到 DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-word/" name="JSON 到 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-wordml/" name="JSON 到 WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-odt/" name="JSON 到 ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-rtf/" name="JSON 到 RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-doc/" name="JSON 到 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-mobi/" name="JSON 到 MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-ott/" name="JSON 到 OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-dotx/" name="JSON 到 DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-pcl/" name="JSON 到 PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-dot/" name="JSON 到 DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-epub/" name="JSON 到 EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/json-to-ps/" name="JSON 到 PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}