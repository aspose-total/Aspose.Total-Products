---
title: 将 PS 渲染为 SXC 的 Java API
description: 通过 Java API 将 PS 导出为 SXC，无需使用 Microsoft Excel 或 Adobe Reader
url_ignore: /zh/java/conversion/ps-to-sxc/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SXC
otherformats: FODS XLT SXC XLAM TXT XLTX XLSM XLTM MD EXCEL DIF ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 PS 导出为 SXC" h2="在任何 Java J2SE、J2EE、J2ME 应用程序中使用本地 Java API 将 PS 文件转换为 SXC" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 PS 到 SXC 转换功能集成到您的 Java 应用程序中。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 PS 渲染为 XLSX。在第二步中，您可以使用电子表格编程 API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) 将 XLSX 转换为 SXC。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 PS 文件转换为 SXC" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开PS文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- 将 PS 转换为 XLSX ) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 XLSX 文档
4. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) 将文档保存为 SXC 格式方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将受保护的 PS 转换为 SXC" %}}
如果您的 PS 文档受密码保护，则您无法在没有密码的情况下将其转换为 SXC。使用 API，您可以先使用有效密码打开受保护的文档，然后再进行转换。为了打开加密文件，可以初始化一个新的[Document]实例(https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 类并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 PS 文件转换为带水印的 SXC" %}}
在将 PS 文件转换为 SXC 时，您还可以在输出的 SXC 文件格式中添加水印。为了添加水印，请创建一个新工作簿以打开转换后的 XLSX 文件。通过其索引选择 Worksheet，创建一个 Shape 并使用其 addTextEffect 函数，设置颜色、透明度等。之后，您可以将 XLSX 文档保存为带水印的 SXC。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

将PS（PostScript）文件转换为SXC（StarOffice/Calc电子表格）可使结构化的PostScript表格和图表在传统的OpenOffice或StarOffice应用程序中使用。这确保了在较旧的开源电子表格环境中实现数据可移植性。

{{% blocks/products/pf/agp/feature-section-col title="主要用途" %}}

* 从PS报告中提取财务或运营表格到SXC电子表格中。
* 将工程或实验数据从PostScript图表转换为分析用途。
* 从PS布局准备与传统版本兼容的电子表格文件。
* 将PS文档转换为可在开源工具中重复使用的电子表格模板。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

* 批量进行PS到SXC的转换，用于存档或传统系统使用。
* 集成到ETL管道中，用于结构化电子表格分析。
* 从PS布局中自动提取表格和图表。
* 用于协作电子表格环境的基于云的转换。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}