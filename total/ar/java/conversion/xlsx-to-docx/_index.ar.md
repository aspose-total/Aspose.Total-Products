---
title: تحويل XLSX إلى DOCX باستخدام Java
description: Java API لتصدير XLSX إلى DOCX باستخدام Excel أو Word
url_ignore: /ar/java/conversion/xlsx-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSX
outformat: DOCXX
otherformats: POWERPOINT DOCX PPTX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتصدير XLSX إلى DOCX" h2="في Premise Java API لتصدير XLSX إلى DOCX دون الاعتماد على Microsoft Excel & reg ؛" >}}
{{% blocks/products/pf/feature-page-summary %}}
يعتبر تحويل XLSX إلى DOCX عملية من خطوتين. ستستخدم أولاً واجهة برمجة تطبيقات [Aspose.Cells for Java](https://products.aspose.com/cells/java) لتحويل مستند XLSX المحدد إلى PDF ، ثم باستخدام [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API ، يمكنك بسهولة تحويل مستند PDF إلى DOCX. تأتي كلتا واجهات برمجة التطبيقات ضمن مجموعة مكتبات أتمتة تنسيق الملفات [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل XLSX إلى DOCX عبر Java API" %}}
1. افتح ملف XLSX باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. تحويل XLSX إلى PDF وتعيين SaveFormat على AUTO
3. قم بتحميل ملف PDF المحول باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. احفظ المستند بتنسيق DOCX باستخدام [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) طريقة وتعيين Docx كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يجب عليك استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xlsx-to-docxx/" name="XLSX ل DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xlsx-to-pptx/" name="XLSX ل PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xlsx-to-powerpoint/" name="XLSX ل POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xlsx-to-word/" name="XLSX ل WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}