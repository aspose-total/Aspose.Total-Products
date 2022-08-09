---
title: 在 Android 中將 XLT 導出為 WORD
description: 無需使用 Microsoft Word 即可將 XLT 轉換為 WORD 的 Android API
url: /zh-hant/android-java/conversion/xlt-to-word/
family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: DOC
otherformats: PPTX POWERPOINT DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Java 在 Android 上將 XLT 渲染為 WORD" h2="在您的 Android 應用程序中將 XLT 轉換為 WORD，而無需使用 Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 是一個強大的文件自動化 API 包。通過使用它的兩個 API，您可以在 Android 應用程序中集成 XLT 到 WORD 的轉換功能。在第一步中，您可以使用 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 將 XLT 導出為 PDF。之後，通過使用 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)，您可以將 PDF 轉換為 WORD。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於將 XLT 導出為 WORD 的 Android API" %}}
1. 使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類打開 XLT 文件
2. 將 XLT 轉換為 PDF 並將 SaveFormat 設置為 AUTO
3.使用[Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)類加載轉換後的PDF文件
4. 使用[save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions)將文檔保存為WORD格式-) 方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通過 Java 輕鬆使用 Aspose.Total for Android 和安裝 [Aspose.PDF for Android via Java](https://words.aspose.com/pdf/androidjava/installation/) 和 [Aspose.Cells for Android via Java](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) 在您的應用程序中。

或者，您可以從 [下載](https://downloads.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// save XLT as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 從 Android 中的 XLT 文件中刪除自定義屬性" %}}
除了文檔轉換，[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 還提供了大量其他功能。在轉換過程之前，您可以刪除 XLT 文檔的自定義屬性。要刪除自定義屬性，請調用 [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) 方法並傳遞名稱要刪除的文檔屬性。
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xlt-to-pptx/" name="XLT 至 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xlt-to-powerpoint/" name="XLT 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xlt-to-word/" name="XLT 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xlt-to-wordx/" name="XLT 至 WORDX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}