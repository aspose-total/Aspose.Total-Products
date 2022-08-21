---
title: تصدير XLS إلى DOCX في Android
description: Android API لتحويل XLS إلى DOCX دون استخدام Microsoft Word
url: /ar/android-java/conversion/xls-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: DOCX
otherformats: WORD DOC POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم XLS إلى DOCX على Android عبر Java" h2="قم بتحويل ملف XLS إلى DOCX داخل تطبيقات Android بدون استخدام Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) عبارة عن حزمة من واجهات برمجة التطبيقات القوية لأتمتة الملفات. باستخدام اثنين من واجهات برمجة التطبيقات الخاصة به ، يمكنك دمج ميزة تحويل XLS إلى DOCX داخل تطبيقات Android. في الخطوة الأولى ، يمكنك تصدير XLS إلى PDF باستخدام [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). بعد ذلك ، باستخدام [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) ، يمكنك تحويل PDF إلى DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API لتصدير XLS إلى DOCX" %}}
1. افتح ملف XLS باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. تحويل XLS إلى PDF وتعيين SaveFormat على AUTO
3. قم بتحميل ملف PDF المحول باستخدام فئة [Docxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument)
4. احفظ المستند بتنسيق DOCX باستخدام [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) طريقة
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.PDF for Android via Java](https://docxs.aspose.com/pdf/androidjava/installation/) و [Aspose.Cells for Android via Java](https://docxs.aspose.com/cells / java / aspose-cells-for-android-via-java-Installation / # install-asposecells-for-android-via-java-from-maven-repository) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بإزالة الخصائص المخصصة من ملف XLS في Android عبر Java" %}}
بصرف النظر عن تحويل المستندات ، يوفر [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) العديد من الميزات الأخرى أيضًا. قبل عملية التحويل ، يمكنك إزالة الخصائص المخصصة لمستند XLS. لإزالة الخصائص المخصصة ، اتصل بالطريقة [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove (java.lang.String)) ومرر اسم خاصية المستند المراد إزالتها.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xls-to-word/" name="XLS إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xls-to-docx/" name="XLS إلى DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xls-to-powerpoint/" name="XLS إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/xls-to-pptx/" name="XLS إلى PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}