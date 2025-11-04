---
title: 将 TEX 渲染为 CSV 的 Java API
description: 通过 Java API 将 TEX 导出为 CSV，无需使用 Microsoft Excel 或 Adobe Reader
url_ignore: /zh/java/conversion/tex-to-csv/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: CSV
otherformats: XLAM SXC MD FODS XLTM TXT EXCEL ODS XLT XLSM XLTX TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 TEX 导出为 CSV" h2="在任何 Java J2SE、J2EE、J2ME 应用程序中使用本地 Java API 将 TEX 文件转换为 CSV" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 TEX 到 CSV 转换功能集成到您的 Java 应用程序中。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 TEX 渲染为 XLSX。在第二步中，您可以使用电子表格编程 API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) 将 XLSX 转换为 CSV。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 TEX 文件转换为 CSV" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开TEX文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- 将 TEX 转换为 XLSX ) 方法
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
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将受保护的 TEX 转换为 CSV" %}}
如果您的 TEX 文档受密码保护，则您无法在没有密码的情况下将其转换为 CSV。使用 API，您可以先使用有效密码打开受保护的文档，然后再进行转换。为了打开加密文件，可以初始化一个新的[Document]实例(https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 类并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 TEX 文件转换为带水印的 CSV" %}}
在将 TEX 文件转换为 CSV 时，您还可以在输出的 CSV 文件格式中添加水印。为了添加水印，请创建一个新工作簿以打开转换后的 XLSX 文件。通过其索引选择 Worksheet，创建一个 Shape 并使用其 addTextEffect 函数，设置颜色、透明度等。之后，您可以将 XLSX 文档保存为带水印的 CSV。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



将TEX文件转换为**CSV（逗号分隔值）**可将LaTeX文档转换为适用于电子表格、数据库和分析应用程序的轻量级表格数据。这对于在LaTeX中处理数值数据集的研究人员和分析师非常理想。



{{% blocks/products/pf/agp/feature-section-col title="主要用途" %}}



* 将LaTeX生成的表格导出为CSV进行数据分析。

* 用于统计软件和Python/R处理的学术数据集。

* 将以LaTeX格式化的财务或工程报告转换为电子表格进行审阅。

* 以通用CSV格式共享开源项目数据。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}



* 在ETL流水线中批量进行TEX到CSV转换。

* 从研究论文中自动提取表格。

* 集成到基于人工智能的分析平台中。

* 为协作数据集触发CSV生成。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}