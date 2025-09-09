---
title: 将 CGM 渲染为 CSV 的 Java API
description: 通过 Java API 将 CGM 导出为 CSV，无需使用 Microsoft Excel 或 Adobe Reader
url_ignore: /zh/java/conversion/cgm-to-csv/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: CSV
otherformats: DIF XLTX MD FODS XLTM EXCEL XLSM XLAM XLT XLSB ODS SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 CGM 导出为 CSV" h2="在任何 Java J2SE、J2EE、J2ME 应用程序中使用本地 Java API 将 CGM 文件转换为 CSV" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 CGM 到 CSV 转换功能集成到您的 Java 应用程序中。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 CGM 渲染为 XLSX。在第二步中，您可以使用电子表格编程 API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) 将 XLSX 转换为 CSV。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 CGM 文件转换为 CSV" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开CGM文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- 将 CGM 转换为 XLSX 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 XLSX 文档
4. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) 将文档保存为 CSV 格式方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将受保护的 CGM 转换为 CSV" %}}
如果您的 CGM 文档受密码保护，则您无法在没有密码的情况下将其转换为 CSV。使用 API，您可以先使用有效密码打开受保护的文档，然后再进行转换。为了打开加密文件，可以初始化一个新的[Document]实例(https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 类并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 CGM 文件转换为带水印的 CSV" %}}
在将 CGM 文件转换为 CSV 时，您还可以在输出的 CSV 文件格式中添加水印。为了添加水印，请创建一个新工作簿以打开转换后的 XLSX 文件。通过其索引选择 Worksheet，创建一个 Shape 并使用其 addTextEffect 函数，设置颜色、透明度等。之后，您可以将 XLSX 文档保存为带水印的 CSV。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
```
将 CGM（计算机图形元文件）文件转换为 CSV（逗号分隔值）在基于 Java 的环境中，可以让工程、制造和数据分析团队将图形矢量数据转换为结构化表格格式。这样可以轻松提取属性、分析元数据，并与基于 Java 的分析流程集成。使用 Java CSV 库，如 **OpenCSV**，CGM 到 CSV 的工作流程可以自动化大规模处理，同时确保与 BI 工具和报告平台兼容。

{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}
- 从 CGM 图表中提取属性以进行质量控制文档编制。
- 将 CGM 元数据转换为 CSV 表格进行统计分析。
- 解析结构化工程数据以供报告和仪表板使用。
- 与 Excel、Google Sheets 和 BI 平台兼容。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}
- 批量将 CGM 文件转换为 CSV。
- 在基于 Java 的制造系统中安排 CGM 到 CSV 的流程。
- 与基于 Java 的 BI 仪表板集成，实现实时更新。
- 为存档和合规性自动生成 CSV。
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}