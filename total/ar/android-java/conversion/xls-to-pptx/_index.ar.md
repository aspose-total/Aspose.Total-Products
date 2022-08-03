---
title: تصدير XLS إلى PPTX في Android
description: Android API لتحويل XLS إلى PPTX دون استخدام Microsoft Word
url: /ar/android-java/conversion/xls-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: PPTX
otherformats: WORD POWERPOINT DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم XLS إلى PPTX على Android عبر Java" h2="قم بتحويل ملف XLS إلى PPTX داخل تطبيقات Android بدون استخدام Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total لنظام Android عبر Java](https://products.aspose.com/total/android-java/) عبارة عن حزمة من واجهات برمجة التطبيقات القوية لأتمتة الملفات. باستخدام اثنين من واجهات برمجة التطبيقات الخاصة به ، يمكنك دمج ميزة تحويل XLS إلى PPTX داخل تطبيقات Android. في الخطوة الأولى ، يمكنك تصدير XLS إلى PDF باستخدام [Aspose.Cells لنظام Android عبر Java](https://products.aspose.com/cells/android-java/). بعد ذلك ، باستخدام [Aspose.PDF لنظام Android عبر Java](https://products.aspose.com/pdf/android-java/) ، يمكنك تحويل PDF إلى PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API لتصدير XLS إلى PPTX" %}}
1. افتح ملف XLS باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. تحويل XLS إلى PDF وتعيين SaveFormat على AUTO
3. قم بتحميل ملف PDF المحول باستخدام فئة [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. احفظ المستند بتنسيق PPTX باستخدام [حفظ](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) طريقة
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total لنظام Android عبر Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.PDF لنظام Android عبر Java](https://pptxs.aspose.com/pdf/androidjava/installation/) و [Aspose.Cells لنظام Android عبر Java](https://pptxs.aspose.com/cells / java / aspose-cells-for-android-via-java-Installation / # install-asposecells-for-android-via-java-from-maven-repository) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بإزالة الخصائص المخصصة من ملف XLS في Android عبر Java" %}}
بصرف النظر عن تحويل المستندات ، يوفر [Aspose.Cells لنظام Android عبر Java](https://products.aspose.com/cells/android-java/) العديد من الميزات الأخرى أيضًا. قبل عملية التحويل ، يمكنك إزالة الخصائص المخصصة لمستند XLS. لإزالة الخصائص المخصصة ، اتصل بالطريقة [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove (java.lang.String)) ومرر اسم خاصية المستند المراد إزالتها.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xls-to-word/" name="XLS إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xls-to-powerpoint/" name="XLS إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xls-to-pptx/" name="XLS إلى PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xls-to-pptxx/" name="XLS إلى PPTXX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}