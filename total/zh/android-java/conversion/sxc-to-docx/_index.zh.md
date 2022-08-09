---
title: 在 Android 中将 SXC 导出为 DOCX
description: 无需使用 Microsoft Word 即可将 SXC 转换为 DOCX 的 Android API
url: /zh/android-java/conversion/sxc-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: SXC
outformat: DOCX
otherformats: PPTX WORD POWERPOINT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Java 在 Android 上将 SXC 渲染为 DOCX" h2="在您的 Android 应用程序中将 SXC 转换为 DOCX，而无需使用 Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 是一个强大的文件自动化 API 包。通过使用它的两个 API，您可以在 Android 应用程序中集成 SXC 到 DOCX 的转换功能。在第一步中，您可以使用 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 将 SXC 导出为 PDF。之后，通过使用 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)，您可以将 PDF 转换为 DOCX。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于将 SXC 导出为 DOCX 的 Android API" %}}
1. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类打开 SXC 文件
2. 将 SXC 转换为 PDF 并将 SaveFormat 设置为 AUTO
3.使用[Docxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument)类加载转换后的PDF文件
4. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions) 将文档保存为 DOCX 格式-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通过 Java 轻松使用 Aspose.Total for Android 和安装 [Aspose.PDF for Android via Java](https://docxs.aspose.com/pdf/androidjava/installation/) 和 [Aspose.Cells for Android via Java](https://docxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) 在您的应用程序中。

或者，您可以从 [下载](https://downloads.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// save SXC as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 从 Android 中的 SXC 文件中删除自定义属性" %}}
除了文档转换之外，[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 还提供了大量其他功能。在转换过程之前，您可以删除 SXC 文档的自定义属性。要删除自定义属性，请调用 [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove(java.lang.String)) 方法并传递名称要删除的文档属性。
{{% blocks/products/pf/feature-page-code %}}

```java
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/sxc-to-pptx/" name="SXC 至 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/sxc-to-word/" name="SXC 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/sxc-to-powerpoint/" name="SXC 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/sxc-to-docx/" name="SXC 至 DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}