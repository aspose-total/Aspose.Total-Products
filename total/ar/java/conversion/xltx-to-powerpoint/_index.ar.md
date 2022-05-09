---
title: تحويل XLTX إلى POWERPOINT باستخدام Java
description: Java API لتصدير XLTX إلى POWERPOINT باستخدام Excel أو Word
url_ignore: /ar/java/conversion/xltx-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: PPTX
otherformats: POWERPOINT PPTX WORD POWERPOINTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتصدير XLTX إلى POWERPOINT" h2="في Premise Java API لتصدير XLTX إلى POWERPOINT دون الاعتماد على Microsoft Excel & reg ؛" >}}
{{% blocks/products/pf/feature-page-summary %}}
يعتبر تحويل XLTX إلى POWERPOINT عملية من خطوتين. ستستخدم أولاً واجهة برمجة تطبيقات [Aspose.Cells for Java](https://products.aspose.com/cells/java) لتحويل مستند XLTX المحدد إلى PDF ، ثم باستخدام [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API ، يمكنك بسهولة تحويل مستند PDF إلى POWERPOINT. تأتي كلتا واجهات برمجة التطبيقات ضمن مجموعة مكتبات أتمتة تنسيق الملفات [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل XLTX إلى POWERPOINT عبر Java API" %}}
1. افتح ملف XLTX باستخدام فئة [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. تحويل XLTX إلى PDF وتعيين SaveFormat على AUTO
3. قم بتحميل ملف PDF المحول باستخدام فئة [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. احفظ المستند بتنسيق POWERPOINT باستخدام [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) طريقة وتعيين Powerpoint كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يجب عليك استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// save XLTX as PDF
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xltx-to-powerpointx/" name="XLTX ل POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xltx-to-pptx/" name="XLTX ل PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xltx-to-powerpoint/" name="XLTX ل POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xltx-to-word/" name="XLTX ل WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}