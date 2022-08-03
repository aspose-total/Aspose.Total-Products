---
title: تصدير MD إلى PPTM في Android
description: Android API لتحويل MD إلى PPTM دون استخدام Microsoft Word
url: /ar/android-java/conversion/md-to-pptm/
family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: PPTM
otherformats: POT OTP PPSX POTX XAML PPS PPSM SWF POWERPOINT POTM PPT ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل MD إلى PPTM على Android عبر Java" h2="تحويل MD إلى PPTM داخل تطبيقات Android دون استخدام Microsoft <sup>&reg;</sup> PowerPoint أو Adobe <sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك دمج ميزة تحويل MD إلى PPTM داخل تطبيقات Android باستخدام خطوتين بسيطتين. في الخطوة الأولى ، يمكنك تصدير MD إلى PPTX باستخدام [Aspose.PDF لنظام Android عبر Java](https://products.aspose.com/pdf/android-java/). بعد ذلك ، باستخدام [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) ، يمكنك تحويل PPTX إلى PPTM. تأتي كلتا واجهتي برمجة التطبيقات ضمن حزمة [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API لتصدير MD إلى PPTM" %}}
1. افتح ملف MD باستخدام فئة [المستند](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل MD إلى PPTX باستخدام طريقة [حفظ](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. احفظ المستند بتنسيق PPTM باستخدام طريقة [حفظ](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) واضبط `` Pptm` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total لنظام Android عبر Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.PDF لنظام Android عبر Java](https://docs.aspose.com/pdf/androidjava/installation/) و [Aspose.Slides لنظام Android عبر Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="افتح ملف MD المحمي بكلمة مرور في Android عبر Java" %}}
أثناء تحميل تنسيق ملف MD ، قد يكون المستند محميًا بكلمة مرور. يسمح لك [Aspose.PDF لنظام Android عبر Java](https://products.aspose.com/pdf/android-java/) بفتح المستندات المشفرة أيضًا. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [المستند](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) فئة وتمرير اسم الملف وكلمة المرور كوسائط.
{{% blocks/products/pf/feature-page-code %}}

```java
// open MD document
Document doc = new Document("input.md", "Your@Password");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="قم بإنشاء صورة مصغرة لملف PPTM في تطبيقات Android" %}}
بعد تحويل MD إلى PPTM ، يمكنك أيضًا إنشاء صور مصغرة للمستند الناتج. باستخدام ميزة غنية [Aspose.Slides لنظام Android عبر Java](https://products.aspose.com/slides/android-java/) ، يمكنك إنشاء صور مصغرة للشرائح عن طريق إنشاء ومثال [العرض التقديمي]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) فئة. بعد ذلك ، يمكنك الحصول على مرجع أي شريحة مرغوبة باستخدام معرفها أو فهرسها والحصول على صورة مصغرة للشريحة المشار إليها بمقياس محدد.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("output.pptm");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-pot/" name="MD إلى POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-otp/" name="MD إلى OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-ppsx/" name="MD إلى PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-potx/" name="MD إلى POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-xaml/" name="MD إلى XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-pps/" name="MD إلى PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-ppsm/" name="MD إلى PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-swf/" name="MD إلى SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-powerpoint/" name="MD إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-potm/" name="MD إلى POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-ppt/" name="MD إلى PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/md-to-pptm/" name="MD إلى PPTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}