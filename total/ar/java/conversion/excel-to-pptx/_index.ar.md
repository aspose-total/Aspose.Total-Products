---
title: تحويل EXCEL إلى PPTX باستخدام Java
description: Java API لتصدير EXCEL إلى PPTX باستخدام Excel أو Word
url_ignore: /ar/java/conversion/excel-to-pptx/
family: total
platformtag: net
feature: conversion
informat: EXCEL
outformat: PPTX
otherformats: WORD PPTX POWERPOINT PPTXX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتصدير EXCEL إلى PPTX" h2="في Premise Java API لتصدير EXCEL إلى PPTX دون الاعتماد على Microsoft Excel & reg ؛" >}}
{{% blocks/products/pf/feature-page-summary %}}
يعتبر تحويل EXCEL إلى PPTX عملية من خطوتين. ستستخدم أولاً واجهة برمجة تطبيقات [Aspose.Cells for Java](https://products.aspose.com/cells/java) لتحويل مستند EXCEL المحدد إلى PDF ، ثم باستخدام [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API ، يمكنك بسهولة تحويل مستند PDF إلى PPTX. تأتي كلتا واجهات برمجة التطبيقات ضمن مجموعة مكتبات أتمتة تنسيق الملفات [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل EXCEL إلى PPTX عبر Java API" %}}
1. افتح ملف EXCEL باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. تحويل EXCEL إلى PDF وتعيين SaveFormat على AUTO
3. قم بتحميل ملف PDF المحول باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. احفظ المستند بتنسيق PPTX باستخدام [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) طريقة وتعيين Pptx كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يجب عليك استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/excel-to-pptxx/" name="EXCEL ل PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/excel-to-pptx/" name="EXCEL ل PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/excel-to-powerpoint/" name="EXCEL ل POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/excel-to-word/" name="EXCEL ل WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}