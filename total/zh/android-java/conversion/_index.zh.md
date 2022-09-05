---
title: 通过 Android API 进行文档转换 
url: /zh/android-java/conversion/
description: 使用 Android 转换 API 转换 Word、Excel、PowerPoint、HTML、PDF 和图像格式。 Android 将 Office docx、xlsx、pptx 转换为 PDF。 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Android API 进行文档转换" h2="使用 Aspose.Total for Android 通过 Java 转换 Microsoft<sup>&reg;</sup> Office Word、Excel、PowerPoint、PDF、图像和各种其他格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) 为Android应用程序提供文档转换和管理解决方案，无需依赖任何其他软件。 程序员可以通过将 API 集成到新开发的应用程序或现有应用程序中轻松地自动化文档管理和操作解决方案。 通过集成 API，程序员可以轻松地添加功能以在应用程序中创建、编辑或转换各种格式的文档。 Android 中的 PDF Converter API 可处理 Office DOCX、XLSX、PPTX 到 PDF 等转换案例，反之亦然。此外，下面列出的 API 处理的案例很少，相关转换案例的链接也很少。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="将 PDF 转换为 CSV" %}}
Total Android API 支持 PDF 到 Excel XLSX 和 CSV 转换。这是一个两步的过程。 两个总 API [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) 和 Aspose.Cells for Android via Java](https://products.aspose.com/涉及细胞/android-java/)。过程是您可以先将 PDF 转换为 Excel XLSX 格式，然后再将 XLSX 转换为 CSV。 更详细地说，通过 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 类加载 PDF 文件并通过 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) 方法。 接下来使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载渲染的 XLSX 文档并调用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) 方法。

{{% blocks/products/pf/feature-page-code h3="Android - PDF 到 Excel 转换" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Excel 到 Word 的转换" %}}
Android API 也处理 Excel 转换。 过程是，使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载 EXCEL XLSX 文件，并通过首先将 SaveFormat 设置为 AUTO 将 EXCEL 转换为 PDF。 接下来使用 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 类加载保存的 PDF 文件并调用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-)方法将文档保存为Word DOC/DOCX格式。

{{% blocks/products/pf/feature-page-code h3="Android - Excel 到 Word 的转换" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="将 POWERPOINT 转换为 HTML 和 MHTML" %}}
Android Total API 处理各种格式，包括 PowerPoint 文件，因此可以将演示文稿转换为 HTML 和 MHTML。 过程是，使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 类加载 POWERPOINT PPT/PPTX 文件并调用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) 方法将 POWERPOINT 转换为 HTML。 此外，现在使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类加载转换后的 HTML 文档并调用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/) 方法用于 MHTML 转换。 
{{% blocks/products/pf/feature-page-code h3="Android - PowerPoint 幻灯片到 HTML 和 MHTML 转换" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}