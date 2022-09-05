---
title: Document Conversion via Android API 
url: /android-java/conversion/
description: Convert Word, Excel, PowerPoint, HTML, PDF and Image formats using Android conversion API. Android convert Office docx, xlsx, pptx to PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Document Conversion using Android API" h2="Convert Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Images and various other formats using Aspose.Total for Android via Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) provides the document conversion and mangement solution for Android applications without relying on any other software. Programmers can automate the document management and manipulation solution eaisly by integrating API within new developed applications or in existing applications. By integrating the API, Programmer can easily add functionality to create, edit or convert various format documents within the application. PDF Converter API in Android handles conversion cases like Office DOCX, XLSX, PPTX to PDF or vice versa. Moreover, Few cases that API deals listed below and few links given for the relevant conversion cases. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to CSV" %}}
Total Android API supports PDF to Excel XLSX and CSV conversion. It's a two step process. Two Total APIs [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) and [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) involved. Process is you can covert PDF to Excel XLSX format firstly and then XLSX to CSV. In more detail, Load PDF file via [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class and render to XLSX via [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method. Next load the rendered XLSX document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class and invoke [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) method.

{{% blocks/products/pf/feature-page-code h3="Android - PDF to Excel Conversion" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Excel to Word Conversion" %}}
Android API handles Excel conversion as well. Process is, Load EXCEL XLSX file using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class and convert EXCEL to PDF by setting SaveFormat to AUTO firstly. Nex load the saved PDF file using [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) class and invoke [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) method to save the document to Word DOC / DOCX format.

{{% blocks/products/pf/feature-page-code h3="Android - Excel to Word Conversion" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert POWERPOINT to HTML and MHTML" %}}
Android Total API deals with various formats including PowerPoint files so can convert presentations to HTML and MHTML. Process is, Load POWERPOINT PPT/ PPTX file using [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) class and invoke [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) method to convert POWERPOINT to HTML. Moreover, Now load the converted HTML document by using [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class and call [save](https://reference.aspose.com/cells/java/com.aspose.cells/) method for MHTML conversion. 
{{% blocks/products/pf/feature-page-code h3="Android - PowerPoint Slides to HTML and MHTML Conversion" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}