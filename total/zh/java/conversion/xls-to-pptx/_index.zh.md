---
title: 使用 Java 将 XLS 转换为 PPTX
description: 使用 Excel 或 Word 将 XLS 导出为 PPTX 的 Java API
url_ignore: /zh/java/conversion/xls-to-pptx/
family: total
platformtag: net
feature: conversion
informat: XLS
outformat: PPTX
otherformats: PPTXX PPTX POWERPOINT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="用于将 XLS 导出为 PPTX 的 Java API" h2="无需依赖 Microsoft Excel 即可将 XLS 导出为 PPTX 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
将 XLS 渲染到 PPTX 是一个两步过程。您将首先使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java) API 将给定的 XLS 文档转换为 PDF，然后使用 [Aspose.Pdf for Java](https ://products.aspose.com/pdf/java) API，您可以轻松地将您的 PDF 文档转换为 PPTX。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 文件格式自动化库的集合。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何通过 Java API 将 XLS 转换为 PPTX" %}}
1. 使用 [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 类打开 XLS 文件
2. 将 XLS 转换为 PDF 并将 SaveFormat 设置为 AUTO
3.使用[Pptxument](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)类加载转换后的PDF文件
4. 使用[save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions)将文档保存为PPTX格式-) 方法并将 Pptx 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您必须直接从基于 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 的项目中使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://downloads.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/xls-to-pptxx/" name="XLS 到 PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/xls-to-pptx/" name="XLS 到 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/xls-to-powerpoint/" name="XLS 到 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/xls-to-word/" name="XLS 到 WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}