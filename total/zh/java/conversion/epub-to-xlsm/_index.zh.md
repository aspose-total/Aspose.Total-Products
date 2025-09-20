---
title: 将 EPUB 渲染为 XLSM 的 Java API
description: 通过 Java API 将 EPUB 导出为 XLSM，无需使用 Microsoft Excel 或 Adobe Reader
url_ignore: /zh/java/conversion/epub-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: XLSM
otherformats: MD XLSM XLTX XLTM TSV ODS XLSB DIF SXC TXT EXCEL FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 EPUB 导出为 XLSM" h2="在任何 Java J2SE、J2EE、J2ME 应用程序中使用本地 Java API 将 EPUB 文件转换为 XLSM" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 EPUB 到 XLSM 转换功能集成到您的 Java 应用程序中。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 EPUB 渲染为 XLSX。在第二步中，您可以使用电子表格编程 API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) 将 XLSX 转换为 XLSM。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 EPUB 文件转换为 XLSM" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开EPUB文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- 将 EPUB 转换为 XLSX ) 方法
3. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 XLSX 文档
4. 使用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) 将文档保存为 XLSM 格式方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将受保护的 EPUB 转换为 XLSM" %}}
如果您的 EPUB 文档受密码保护，则您无法在没有密码的情况下将其转换为 XLSM。使用 API，您可以先使用有效密码打开受保护的文档，然后再进行转换。为了打开加密文件，可以初始化一个新的[Document]实例(https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 类并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 EPUB 文件转换为带水印的 XLSM" %}}
在将 EPUB 文件转换为 XLSM 时，您还可以在输出的 XLSM 文件格式中添加水印。为了添加水印，请创建一个新工作簿以打开转换后的 XLSX 文件。通过其索引选择 Worksheet，创建一个 Shape 并使用其 addTextEffect 函数，设置颜色、透明度等。之后，您可以将 XLSX 文档保存为带水印的 XLSM。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
将 **EPUB 转换为 XLSM** 对于将数字出版物转换为 **启用宏的 Excel 工作簿** 至关重要，从而实现高级自动化、互动性和动态数据处理。通过在提取的电子书数据中嵌入宏，组织和研究人员可以简化工作流程，生成交互式仪表板，并构建符合其需求的自动报告系统。

{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}
- **自动报告** – 直接从出版数据生成基于宏的报告。
- **交互式仪表板** – 为实时洞察力创建动态仪表板。
- **自定义数据模型** – 开发由 Excel 宏驱动的定制模型。
- **使用宏进行学术分析** – 从电子书内容启用高级研究工作流程。
- **具有自动化的发布工作流程** – 简化编辑和生产流程。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}
- **EPUB 到 XLSM 转换流水线** – 自动化结构化转换为启用宏的文件。
- **自动化的启用宏工作簿分发** – 大规模交付 XLSM 报告。
- **基于元数据的报告** – 将出版元数据提取为可操作的 Excel 报告。
- **企业发布自动化** – 将启用宏的 Excel 集成到大规模发布系统中。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}