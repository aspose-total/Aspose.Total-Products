---
title: تصدير CSV إلى PPTX في Android
description: Android API لتحويل CSV إلى PPTX دون استخدام Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: PPTX
otherformats: POWERPOINT DOC WORD DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم CSV إلى PPTX على Android عبر Java" h2="قم بتحويل ملف CSV إلى PPTX داخل تطبيقات Android بدون استخدام Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) عبارة عن حزمة من واجهات برمجة التطبيقات القوية لأتمتة الملفات. باستخدام اثنين من واجهات برمجة التطبيقات الخاصة به ، يمكنك دمج ميزة تحويل CSV إلى PPTX داخل تطبيقات Android. في الخطوة الأولى ، يمكنك تصدير CSV إلى PDF باستخدام [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). بعد ذلك ، باستخدام [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) ، يمكنك تحويل PDF إلى PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API لتصدير CSV إلى PPTX" %}}
1. افتح ملف CSV باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. تحويل CSV إلى PDF وتعيين SaveFormat على AUTO
3. قم بتحميل ملف PDF المحول باستخدام فئة [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. احفظ المستند بتنسيق PPTX باستخدام [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) طريقة
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.PDF for Android via Java](https://pptxs.aspose.com/pdf/androidjava/installation/) و [Aspose.Cells for Android via Java](https://pptxs.aspose.com/cells / java / aspose-cells-for-android-via-java-Installation / # install-asposecells-for-android-via-java-from-maven-repository) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the CSV file using Workbook class
Workbook book = new Workbook("input.csv");
// save CSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بإزالة الخصائص المخصصة من ملف CSV في Android عبر Java" %}}
بصرف النظر عن تحويل المستندات ، يوفر [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) العديد من الميزات الأخرى أيضًا. قبل عملية التحويل ، يمكنك إزالة الخصائص المخصصة لمستند CSV. لإزالة الخصائص المخصصة ، اتصل بالطريقة [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove (java.lang.String)) ومرر اسم خاصية المستند المراد إزالتها.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the CSV file using Workbook class
Workbook book = new Workbook("input.csv");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/csv-to-powerpoint/" name="CSV إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/csv-to-pptx/" name="CSV إلى PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/csv-to-word/" name="CSV إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/csv-to-pptxx/" name="CSV إلى PPTXX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}