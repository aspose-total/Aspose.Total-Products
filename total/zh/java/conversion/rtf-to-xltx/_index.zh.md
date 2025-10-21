---
title: Java API 将 RTF 转换为 XLTX 或使用免费的在线转换器
description: 通过 Java 将 RTF 转换为 XLTX 或在线应用程序，而不使用 Microsoft Word 或 Microsoft Excel 或在线。在集成代码之前快速测试免费的 RTF 到 XLTX 在线转换器。 
url_ignore: /zh/java/conversion/rtf-to-xltx/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: XLTX
otherformats: XLTM ODS XLAM XLS XLSB FODS XLT XLTX TSV XLSM XLSX SXC EXCEL DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 RTF 转换为 XLTX 或在线应用程序" h2="无需使用 Microsoft<sup>&reg;</sup> Word 或 Microsoft<sup>&reg;</sup> Excel 即可将 RTF 转换为 XLTX 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过 [Aspose.Total for Java](https://products.aspose.com/total/java/) 将 RTF 转换为 XLTX 是一个简单的两步过程。通过使用功能丰富的文档操作和转换 API [Aspose.Words for Java](https://products.aspose.com/words/java/)，您可以将 RTF 导出为 HTML。之后，通过使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java/)，您可以将 HTML 转换为 XLTX。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="将 RTF 转换为 XLTX 的 Java API" %}}
1. 使用 [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 类打开 RTF 文件
2. 使用 [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) 将 RTF 转换为 HTML ) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 HTML 文档
4. 使用 [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) 将文档保存为 XLTX 格式方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>免费的 RTF 到 XLTX 在线转换器</h3>

<iframe title="rtf 到 xltx 转换在线工具" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=xltx&from=rtf" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="通过 Java 从 RTF 文档中删除未使用的信息" %}}
在将 RTF 转换为 XLTX 之前，您可以通过 [Aspose.Words for Java](https://products.aspose.com/words/java/) 从 RTF 文档中删除未使用的信息。有时您可能需要删除未使用或重复的信息以减少输出文档的大小和处理时间。 [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) 类允许您指定文档清理的选项。要从文档中删除重复的样式或仅未使用的样式或列表，您可以使用 [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()) 方法。您可以使用 [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) 和 [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) 属性来检测和删除标记为“未使用”的样式。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-Document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions))
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 XLTX 文件保存到流" %}}
将 RTF 转换为 XLTX 后，[Aspose.Cells for Java](https://products.aspose.com/cells/java/) 使您能够将文档保存为流式传输。如果您需要将文件保存到 Stream 那么您应该创建一个 FileOutputStream 对象，然后 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) 通过调用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 的 save 方法将文件保存到该 Stream 对象目的。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

将RTF转换为XLTX（Excel模板开放XML格式）使组织能够在现代Excel环境中无需宏重复使用文档布局。它被广泛用于报告、数据输入和专业文档格式设置。

{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}

* 将基于RTF的财务摘要转换为可重复使用的XLTX模板。
* 为报告和表单构建标准化的Excel布局。
* 将公司文档转换为现代电子表格格式。
* 从RTF数据文件准备部门模板。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* 用于企业报告工作流程的自动化RTF到XLTX生成。
* 与文档自动化系统集成，用于标准化表单。
* 从存档的RTF文档定期创建Excel模板。
* 支持现代Excel和Office 365兼容性的批量转换。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}