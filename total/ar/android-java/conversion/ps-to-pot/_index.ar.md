---
title: تصدير PS إلى POT في Android
description: Android API لتحويل PS إلى POT دون استخدام Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: POT
otherformats: PPTM POTX OTP PPSM PPT PPSX POTM XAML PPS POWERPOINT SWF ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل PS إلى POT على Android عبر Java" h2="تحويل PS إلى POT داخل تطبيقات Android دون استخدام Microsoft <sup>&reg;</sup> PowerPoint أو Adobe <sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك دمج ميزة تحويل PS إلى POT داخل تطبيقات Android باستخدام خطوتين بسيطتين. في الخطوة الأولى ، يمكنك تصدير PS إلى PPTX باستخدام [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). بعد ذلك ، باستخدام [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) ، يمكنك تحويل PPTX إلى POT. تأتي كلتا واجهتي برمجة التطبيقات ضمن حزمة [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API لتصدير PS إلى POT" %}}
1. افتح ملف PS باستخدام فئة [المستند](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل PS إلى PPTX باستخدام طريقة [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. احفظ المستند بتنسيق POT باستخدام طريقة [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) واضبط `` Pot` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) و [Aspose.Slides لنظام Android عبر Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS file with an instance of Document class
Document document = new Document("template.ps");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="افتح ملف PS المحمي بكلمة مرور في Android عبر Java" %}}
أثناء تحميل تنسيق ملف PS ، قد يكون المستند محميًا بكلمة مرور. يسمح لك [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) بفتح المستندات المشفرة أيضًا. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [المستند](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) فئة وتمرير اسم الملف وكلمة المرور كوسائط.
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="قم بإنشاء صورة مصغرة لملف POT في تطبيقات Android" %}}
بعد تحويل PS إلى POT ، يمكنك أيضًا إنشاء صور مصغرة للمستند الناتج. باستخدام ميزة غنية [Aspose.Slides لنظام Android عبر Java](https://products.aspose.com/slides/android-java/) ، يمكنك إنشاء صور مصغرة للشرائح عن طريق إنشاء ومثال [العرض التقديمي](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) فئة. بعد ذلك ، يمكنك الحصول على مرجع أي شريحة مرغوبة باستخدام معرفها أو فهرسها والحصول على صورة مصغرة للشريحة المشار إليها بمقياس محدد.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("output.pot");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-pptm/" name="PS إلى PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-potx/" name="PS إلى POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-otp/" name="PS إلى OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-ppsm/" name="PS إلى PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-ppt/" name="PS إلى PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-ppsx/" name="PS إلى PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-potm/" name="PS إلى POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-xaml/" name="PS إلى XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-pps/" name="PS إلى PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-powerpoint/" name="PS إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-swf/" name="PS إلى SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ps-to-pot/" name="PS إلى POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}