---
title: Dokumentkonvertering via Android API 
url: /sv/android-java/conversion/
description: Konvertera Word-, Excel-, PowerPoint-, HTML-, PDF- och bildformat med Android-konverterings-API. Android konverterar Office docx, xlsx, pptx till PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Dokumentkonvertering med Android API" h2="Konvertera Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, bilder och olika andra format med Aspose.Total för Android via Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) tillhandahåller dokumentkonverterings- och hanteringslösningen för Android-applikationer utan att förlita sig på någon annan programvara. Programmerare kan enkelt automatisera dokumenthanterings- och manipuleringslösningen genom att integrera API i nyutvecklade applikationer eller i befintliga applikationer. Genom att integrera API:t kan programmeraren enkelt lägga till funktionalitet för att skapa, redigera eller konvertera dokument i olika format i applikationen. PDF Converter API i Android hanterar konverteringsfall som Office DOCX, XLSX, PPTX till PDF eller vice versa. Dessutom, några få fall som API handlar listade nedan och få länkar för relevanta konverteringsfall. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera PDF till CSV" %}}
Total Android API stöder PDF till Excel XLSX och CSV-konvertering. Det är en process i två steg. Två totala API:er [Aspose.PDF för Android via Java](https://products.aspose.com/pdf/android-java/) och Aspose.Cells för Android via Java](https://products.aspose.com/celler/android-java/) involverade. Processen är att du först kan dold PDF till Excel XLSX-format och sedan XLSX till CSV. Mer detaljerat, ladda PDF-filen via klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) och rendera till XLSX via [spara](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-). Ladda sedan det renderade XLSX-dokumentet genom att använda klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) och anropa [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metod.

{{% blocks/products/pf/feature-page-code h3="Android - Konvertering av PDF till Excel" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Excel till Word-konvertering" %}}
Android API hanterar även Excel-konvertering. Processen är, ladda EXCEL XLSX-fil med [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) klass och konvertera EXCEL till PDF genom att först ställa in SaveFormat till AUTO. Ladda sedan den sparade PDF-filen med klassen [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) och anropa [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metod för att spara dokumentet i Word DOC/DOCX-format.

{{% blocks/products/pf/feature-page-code h3="Android - Excel till Word-konvertering" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera POWERPOINT till HTML och MHTML" %}}
Android Total API hanterar olika format inklusive PowerPoint-filer så kan konvertera presentationer till HTML och MHTML. Processen är, ladda POWERPOINT PPT/PPTX-fil med [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) klass och anropa [save](https://reference.aspose) .com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) metod för att konvertera POWERPOINT till HTML. Dessutom, ladda nu det konverterade HTML-dokumentet genom att använda klassen [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) och anropa [save](https://reference.aspose) .com/cells/java/com.aspose.cells/) metod för MHTML-konvertering. 
{{% blocks/products/pf/feature-page-code h3="Android - PowerPoint-bilder till HTML och MHTML-konvertering" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}