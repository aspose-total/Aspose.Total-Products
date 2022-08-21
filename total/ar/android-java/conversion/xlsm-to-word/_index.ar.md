---
title: تصدير XLSM إلى WORD في Android
description: Android API لتحويل XLSM إلى WORD دون استخدام Microsoft Word
url: /ar/android-java/conversion/xlsm-to-word/
family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: DOC
otherformats: PPTX DOCX DOC POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم XLSM إلى WORD على Android عبر Java" h2="قم بتحويل ملف XLSM إلى WORD داخل تطبيقات Android بدون استخدام Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) عبارة عن حزمة من واجهات برمجة التطبيقات القوية لأتمتة الملفات. باستخدام اثنين من واجهات برمجة التطبيقات الخاصة به ، يمكنك دمج ميزة تحويل XLSM إلى WORD داخل تطبيقات Android. في الخطوة الأولى ، يمكنك تصدير XLSM إلى PDF باستخدام [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). بعد ذلك ، باستخدام [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) ، يمكنك تحويل PDF إلى WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API لتصدير XLSM إلى WORD" %}}
1. افتح ملف XLSM باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. تحويل XLSM إلى PDF وتعيين SaveFormat على AUTO
3. قم بتحميل ملف PDF المحول باستخدام فئة [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. احفظ المستند بتنسيق WORD باستخدام [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) طريقة
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.PDF for Android via Java](https://words.aspose.com/pdf/androidjava/installation/) و [Aspose.Cells for Android via Java](https://words.aspose.com/cells / java / aspose-cells-for-android-via-java-Installation / # install-asposecells-for-android-via-java-from-maven-repository) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بإزالة الخصائص المخصصة من ملف XLSM في Android عبر Java" %}}
بصرف النظر عن تحويل المستندات ، يوفر [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) العديد من الميزات الأخرى أيضًا. قبل عملية التحويل ، يمكنك إزالة الخصائص المخصصة لمستند XLSM. لإزالة الخصائص المخصصة ، اتصل بالطريقة [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove (java.lang.String)) ومرر اسم خاصية المستند المراد إزالتها.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xlsm-to-pptx/" name="XLSM إلى PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xlsm-to-wordx/" name="XLSM إلى WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xlsm-to-word/" name="XLSM إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xlsm-to-powerpoint/" name="XLSM إلى POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}