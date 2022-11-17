---
title: 在 Android 中將 TSV 導出為 DOCX
description: 無需使用 Microsoft Word 即可將 TSV 轉換為 DOCX 的 Android API

family: total
platformtag: cpp
feature: conversion
informat: TSV
outformat: DOCX
otherformats: WORD DOC POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Java 在 Android 上將 TSV 渲染為 DOCX" h2="在您的 Android 應用程序中將 TSV 轉換為 DOCX，而無需使用 Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 是一個強大的文件自動化 API 包。通過使用它的兩個 API，您可以在 Android 應用程序中集成 TSV 到 DOCX 的轉換功能。在第一步中，您可以使用 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 將 TSV 導出為 PDF。之後，通過使用 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)，您可以將 PDF 轉換為 DOCX。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於將 TSV 導出為 DOCX 的 Android API" %}}
1. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類打開 TSV 文件
2. 將 TSV 轉換為 PDF 並將 SaveFormat 設置為 AUTO
3.使用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)類加載轉換後的PDF文件
4. 使用[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions)將文檔保存為DOCX格式-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通過 Java 輕鬆使用 Aspose.Total for Android 和安裝 [Aspose.PDF for Android via Java](https://docxs.aspose.com/pdf/androidjava/installation/) 和 [Aspose.Cells for Android via Java](https://docxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) 在您的應用程序中。

或者，您可以從 [下載](https://downloads.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// save TSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOCX format
document.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 從 Android 中的 TSV 文件中刪除自定義屬性" %}}Document
除了文檔轉換，[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 還提供了大量其他功能。在轉換過程之前，您可以刪除 TSV 文檔的自定義屬性。要刪除自定義屬性，請調用 [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/documentpropertycollection#remove(java.lang.String)) 方法並傳遞名稱要刪除的文檔屬性。
{{% blocks/products/pf/feature-page-code %}}

```java
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
Documentve a list of all custom document properties of the Excel fileDocument
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom document property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/tsv-to-word/" name="TSV 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/tsv-to-docx/" name="TSV 至 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/tsv-to-powerpoint/" name="TSV 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/tsv-to-pptx/" name="TSV 至 PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}