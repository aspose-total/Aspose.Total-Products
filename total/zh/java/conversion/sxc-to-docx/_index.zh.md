---
title: 使用 Java 将 SXC 转换为 DOCX
description: 使用 Excel 或 Word 将 SXC 导出为 DOCX 的 Java API
url_ignore: /zh/java/conversion/sxc-to-docx/
family: total
platformtag: net
feature: conversion
informat: SXC
outformat: DOCXX
otherformats: PPTX WORD POWERPOINT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="用于将 SXC 导出为 DOCX 的 Java API" h2="无需依赖 Microsoft Excel 即可将 SXC 导出为 DOCX 的 On Premise Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
将 SXC 渲染到 DOCX 是一个两步过程。您将首先使用 [Aspose.Cells for Java](https://products.aspose.com/cells/java) API 将给定的 SXC 文档转换为 PDF，然后使用 [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API，您可以轻松地将您的 PDF 文档转换为 DOCX。这两个 API 都属于 [Aspose.Total for Java](https://products.aspose.com/total/java/) 文件格式自动化库的集合。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何通过 Java API 将 SXC 转换为 DOCX" %}}
1. 使用 [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 类打开 SXC 文件
2. 将 SXC 转换为 PDF 并将 SaveFormat 设置为 AUTO
3.使用[Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)类加载转换后的PDF文件
4. 使用[save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)将文档保存为DOCX格式-) 方法并将 Docx 设置为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您必须直接从基于 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 的项目中使用 Aspose.Total for Java并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://downloads.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// save SXC as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/sxc-to-docxx/" name="SXC 到 DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/sxc-to-pptx/" name="SXC 到 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/sxc-to-powerpoint/" name="SXC 到 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/sxc-to-word/" name="SXC 到 WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}