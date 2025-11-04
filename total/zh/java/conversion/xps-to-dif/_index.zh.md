---
title: 将 XPS 渲染为 DIF 的 Java API
description: 通过 Java API 将 XPS 导出为 DIF，无需使用 Microsoft Excel 或 Adobe Reader
url_ignore: /zh/java/conversion/xps-to-dif/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: DIF
otherformats: TSV XLSB EXCEL MD TXT XLT FODS DIF XLSM ODS XLAM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 XPS 导出为 DIF" h2="在任何 Java J2SE、J2EE、J2ME 应用程序中使用本地 Java API 将 XPS 文件转换为 DIF" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 XPS 到 DIF 转换功能集成到您的 Java 应用程序中。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 XPS 渲染为 XLSX。在第二步中，您可以使用电子表格编程 API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) 将 XLSX 转换为 DIF。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 XPS 文件转换为 DIF" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开XPS文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- 将 XPS 转换为 XLSX ) 方法
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
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将受保护的 XPS 转换为 DIF" %}}
如果您的 XPS 文档受密码保护，则您无法在没有密码的情况下将其转换为 DIF。使用 API，您可以先使用有效密码打开受保护的文档，然后再进行转换。为了打开加密文件，可以初始化一个新的[Document]实例(https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 类并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 XPS 文件转换为带水印的 DIF" %}}
在将 XPS 文件转换为 DIF 时，您还可以在输出的 DIF 文件格式中添加水印。为了添加水印，请创建一个新工作簿以打开转换后的 XLSX 文件。通过其索引选择 Worksheet，创建一个 Shape 并使用其 addTextEffect 函数，设置颜色、透明度等。之后，您可以将 XLSX 文档保存为带水印的 DIF。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



将 XPS 文件转换为 **DIF（数据交换格式）** 可以与传统电子表格软件兼容，同时保持数字和表格数据的完整性。DIF 对于维护旧财务和 ERP 系统的组织来说是理想的选择。



{{% blocks/products/pf/agp/feature-section-col title="主要用途" %}}



* 历史财务记录迁移。

* 将基于 XPS 的报告导入传统会计软件。

* 保留数字数据集以进行监管审计。

* 在跨平台电子表格工具之间进行数据交换。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}



* 用于归档 XPS 数据集的自动批量转换。

* 集成到 ERP 流程中进行财务报告。

* 定期更新以 DIF 格式存储的历史数据。

* 从 XPS 迁移至现代分析平台的流程优化。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}