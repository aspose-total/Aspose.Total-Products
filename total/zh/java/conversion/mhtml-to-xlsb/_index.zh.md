---
title: 将 MHTML 渲染为 XLSB 的 Java API
description: 通过 Java API 将 MHTML 导出为 XLSB，无需使用 Microsoft Excel 或 Adobe Reader
url: /zh/java/conversion/mhtml-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: XLSB
otherformats: TXT ODS MD XLSM SXC XLT EXCEL DIF XLTX XLSB TSV FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Java 将 MHTML 导出为 XLSB" h2="在任何 Java J2SE、J2EE、J2ME 应用程序中使用本地 Java API 将 MHTML 文件转换为 XLSB" >}}
{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以分两步将 MHTML 到 XLSB 转换功能集成到您的 Java 应用程序中。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 MHTML 渲染为 XLSX。在第二步中，您可以使用电子表格编程 API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) 将 XLSX 转换为 XLSB。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 MHTML 文件转换为 XLSB" %}}
1.使用[Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开MHTML文件
2. 使用 [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- 将 MHTML 转换为 XLSX ） 方法
3. 使用 [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 XLSX 文档
4. 使用 [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) 将文档保存为 XLSB 格式。 SaveOptions)) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。。

或者，您可以从 [下载](https://downloads.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将受保护的 MHTML 转换为 XLSB" %}}
如果您的 MHTML 文档受密码保护，则您无法在没有密码的情况下将其转换为 XLSB。使用 API，您可以先使用有效密码打开受保护的文档，然后再进行转换。为了打开加密文件，可以初始化一个新的[Document]实例(https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- java.lang.String-) 类并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 将 MHTML 文件转换为带水印的 XLSB" %}}
在将 MHTML 文件转换为 XLSB 时，您还可以在输出的 XLSB 文件格式中添加水印。为了添加水印，请创建一个新工作簿以打开转换后的 XLSX 文件。通过其索引选择 Worksheet，创建一个 Shape 并使用其 addTextEffect 函数，设置颜色、透明度等。之后，您可以将 XLSX 文档保存为带水印的 XLSB。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-dif/" name="MHTML 到 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-xltx/" name="MHTML 到 XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-md/" name="MHTML 到 MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-fods/" name="MHTML 到 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-xltm/" name="MHTML 到 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-excel/" name="MHTML 到 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-xlsm/" name="MHTML 到 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-xlam/" name="MHTML 到 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-xlt/" name="MHTML 到 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-xlsb/" name="MHTML 到 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-ods/" name="MHTML 到 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/mhtml-to-sxc/" name="MHTML 到 SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}