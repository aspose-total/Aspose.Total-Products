---
title: 将 CGM 渲染为 DIF 的 Java API
description: 通过 Java API 将 CGM 导出为 DIF，无需使用 Microsoft Excel 或 Adobe Reader
url_ignore: /zh/java/conversion/cgm-to-dif/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DIF
otherformats: XLT XLSB XLAM DIF XLTX XLTM SXC TXT EXCEL ODS MD XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 CGM 导出为 DIF" h2="在任何 Java J2SE、J2EE、J2ME 应用程序中使用本地 Java API 将 CGM 文件转换为 DIF" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 CGM 到 DIF 转换功能集成到您的 Java 应用程序中。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 CGM 渲染为 XLSX。在第二步中，您可以使用电子表格编程 API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) 将 XLSX 转换为 DIF。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 CGM 文件转换为 DIF" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开CGM文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- 将 CGM 转换为 XLSX 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 XLSX 文档
4. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将受保护的 CGM 转换为 DIF" %}}
如果您的 CGM 文档受密码保护，则您无法在没有密码的情况下将其转换为 DIF。使用 API，您可以先使用有效密码打开受保护的文档，然后再进行转换。为了打开加密文件，可以初始化一个新的[Document]实例(https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 类并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 CGM 文件转换为带水印的 DIF" %}}
在将 CGM 文件转换为 DIF 时，您还可以在输出的 DIF 文件格式中添加水印。为了添加水印，请创建一个新工作簿以打开转换后的 XLSX 文件。通过其索引选择 Worksheet，创建一个 Shape 并使用其 addTextEffect 函数，设置颜色、透明度等。之后，您可以将 XLSX 文档保存为带水印的 DIF。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
## 将 **计算机图形元文件（CGM）** 文件转换为 **DIF（数据交换格式）** 对于需要将视觉或结构化内容集成到传统电子表格系统和科学计算工作流程中的组织非常有价值。在 **基于Java的企业和研究环境** 中，此转换使得从旧格式平滑迁移成为可能，支持与统计工具的兼容性，并促进工程应用的结构化数据建模。通过将CGM图表转换为DIF表，团队可以统一视觉数据和数值数据集，提高跨平台的可访问性和分析能力。


{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}

- **传统电子表格系统迁移**  
  将CGM数据转换为DIF，以便无缝导入仍在企业环境中使用的旧电子表格程序。

- **科学计算平台**  
  将图形CGM数据转换为DIF，以便与物理、化学和环境建模中的数值分析工具兼容。

- **工程应用中的结构化数据建模**  
  使用DIF以结构化表格形式表示基于CGM的原理图，用于工程模拟和CAD数据集成。


{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}

- **用于电子表格转换的Java库**  
  使用处理与电子表格兼容格式的Java API实现自动化的CGM到DIF转换。

- **ETL工具中的批处理**  
  将转换步骤集成到基于Java的抽取-转换-加载流水线中，以处理大量工程或研究数据。

- **与统计计算流水线集成**  
  通过基于Java的工作流编排自动将转换后的DIF文件馈送到R、MATLAB或Python统计分析模块中。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}