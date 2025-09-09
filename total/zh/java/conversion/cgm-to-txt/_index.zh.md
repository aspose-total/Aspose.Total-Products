---
title: 将 CGM 渲染为 TXT 的 Java API
description: 通过 Java API 将 CGM 导出为 TXT，无需使用 Microsoft Excel 或 Adobe Reader
url_ignore: /zh/java/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLAM FODS XLTM ODS MD DIF EXCEL TXT XLTX XLT SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 CGM 导出为 TXT" h2="在任何 Java J2SE、J2EE、J2ME 应用程序中使用本地 Java API 将 CGM 文件转换为 TXT" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 CGM 到 TXT 转换功能集成到您的 Java 应用程序中。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 CGM 渲染为 XLSX。在第二步中，您可以使用电子表格编程 API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) 将 XLSX 转换为 TXT。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 CGM 文件转换为 TXT" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开CGM文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- 将 CGM 转换为 XLSX 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 XLSX 文档
4. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) 将文档保存为 TXT 格式方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将受保护的 CGM 转换为 TXT" %}}
如果您的 CGM 文档受密码保护，则您无法在没有密码的情况下将其转换为 TXT。使用 API，您可以先使用有效密码打开受保护的文档，然后再进行转换。为了打开加密文件，可以初始化一个新的[Document]实例(https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 类并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 CGM 文件转换为带水印的 TXT" %}}
在将 CGM 文件转换为 TXT 时，您还可以在输出的 TXT 文件格式中添加水印。为了添加水印，请创建一个新工作簿以打开转换后的 XLSX 文件。通过其索引选择 Worksheet，创建一个 Shape 并使用其 addTextEffect 函数，设置颜色、透明度等。之后，您可以将 XLSX 文档保存为带水印的 TXT。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
```
将**计算机图形元文件（CGM）**文件转换为**TXT（纯文本）**格式对于以轻量级、人类可读形式提取、记录和处理矢量图形信息非常有价值。在**基于Java的数据处理管道**中，此转换使得可以将CGM图表转换为基于文本的表示形式，用于日志记录、元数据存储或下游分析。通过在TXT中捕获CGM文件的描述元素，组织可以简化与其他系统的集成，实现快速搜索和索引，并保持长期兼容性。



{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}

- **图表的文本记录**  
  将CGM图表信息存储为纯文本，用于审计、调试或归档目的。

- **提取矢量图形描述**  
  将CGM结构转换为TXT以进行解析、搜索索引或与分析工具集成。

- **工程元数据文档**  
  在TXT文件中记录与CGM相关的工程数据，以便快速参考和轻量级存储。


{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

- **用于转换的Java I/O库**  
  使用标准的Java文件处理API以及CGM解析器来提取和写入内容到TXT文件。

- **文件监视器服务**  
  通过使用Java的`WatchService`监视目录中的新文件事件，自动化CGM到TXT的转换。

- **批量转换作业**  
  在计划的Java作业中处理大量的CGM文件，将文本表示导出用于归档或分析。

- **ETL管道中的纯文本导出器**  
  将CGM解析和TXT导出集成到基于Java的提取-转换-加载工作流中，用于结构化数据处理。
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}