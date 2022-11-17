---
title: 通過 Android API 進行文檔轉換 

description: 使用 Android 轉換 API 轉換 Word、Excel、PowerPoint、HTML、PDF 和圖像格式。 Android 將 Office docx、xlsx、pptx 轉換為 PDF。 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Android API 進行文檔轉換" h2="使用 Aspose.Total for Android 通過 Java 轉換 Microsoft<sup>&reg;</sup> Office Word、Excel、PowerPoint、PDF、圖像和各種其他格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}
【Total Android API】（https://products.aspose.com/total/android-java/）為Android應用程序提供文檔轉換和管理解決方案，無需依賴任何其他軟件。 通過將 API 集成到新開發的應用程序或現有應用程序中，程序員可以輕鬆地自動化文檔管理和操作解決方案。 通過集成 API，程序員可以輕鬆地添加功能以在應用程序中創建、編輯或轉換各種格式的文檔。 Android 中的 PDF Converter API 可處理 Office DOCX、XLSX、PPTX 到 PDF 等轉換案例，反之亦然。此外，下面列出的 API 處理的案例很少，相關轉換案例的鏈接也很少。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="將 PDF 轉換為 CSV" %}}
Total Android API 支持 PDF 到 Excel XLSX 和 CSV 轉換。這是一個兩步的過程。 兩個總 API [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) 和 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) 涉及。過程是您可以先將 PDF 轉換為 Excel XLSX 格式，然後再將 XLSX 轉換為 CSV。 更詳細地說，通過 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 類加載 PDF 文件並通過 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) 方法。 接下來使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類加載渲染的 XLSX 文檔並調用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) 方法。

{{% blocks/products/pf/feature-page-code h3="Android - PDF 到 Excel 轉換" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Excel 到 Word 的轉換" %}}
Android API 也處理 Excel 轉換。 過程是，使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類加載 EXCEL XLSX 文件，並通過首先將 SaveFormat 設置為 AUTO 將 EXCEL 轉換為 PDF。 接下來使用 [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) 類加載保存的 PDF 文件並調用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-)方法將文檔保存為Word DOC/DOCX格式。

{{% blocks/products/pf/feature-page-code h3="Android - Excel 到 Word 的轉換" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="將 POWERPOINT 轉換為 HTML 和 MHTML" %}}
Android Total API 處理各種格式，包括 PowerPoint 文件，因此可以將演示文稿轉換為 HTML 和 MHTML。 過程是，使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 類加載 POWERPOINT PPT/PPTX 文件並調用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) 方法將 POWERPOINT 轉換為 HTML。 此外，現在使用 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 類加載轉換後的 HTML 文檔並調用 [save](https://reference.aspose.com/cells/java/com.aspose.cells/) 方法用於 MHTML 轉換。 
{{% blocks/products/pf/feature-page-code h3="Android - PowerPoint 幻燈片到 HTML 和 MHTML 轉換" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}