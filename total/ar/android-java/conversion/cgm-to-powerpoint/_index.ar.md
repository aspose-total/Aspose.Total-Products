---
title: تصدير CGM إلى POWERPOINT في Android
description: Android API لتحويل CGM إلى POWERPOINT دون استخدام Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: PPT
otherformats: PPTM XAML PPSM PPS OTP POT SWF POTM POTX ODP PPSX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل CGM إلى POWERPOINT على Android عبر Java" h2="تحويل CGM إلى POWERPOINT داخل تطبيقات Android دون استخدام Microsoft <sup>&reg;</sup> PowerPoint أو Adobe <sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك دمج ميزة تحويل CGM إلى POWERPOINT داخل تطبيقات Android باستخدام خطوتين بسيطتين. في الخطوة الأولى ، يمكنك تصدير CGM إلى PPTX باستخدام [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). بعد ذلك ، باستخدام [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) ، يمكنك تحويل PPTX إلى POWERPOINT. تأتي كلتا واجهتي برمجة التطبيقات ضمن حزمة [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API لتصدير CGM إلى POWERPOINT" %}}
1. افتح ملف CGM باستخدام فئة [المستند](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل CGM إلى PPTX باستخدام طريقة [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. احفظ المستند بتنسيق POWERPOINT باستخدام طريقة [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) واضبط `` Powerpoint` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://releases.aspose.com/total/java/) و تثبيت [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) و [Aspose.Slides لنظام Android عبر Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load CGM file with an instance of Document class
Document document = new Document("template.cgm");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="افتح ملف CGM المحمي بكلمة مرور في Android عبر Java" %}}
أثناء تحميل تنسيق ملف CGM ، قد يكون المستند محميًا بكلمة مرور. يسمح لك [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) بفتح المستندات المشفرة أيضًا. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [المستند](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) فئة وتمرير اسم الملف وكلمة المرور كوسائط.
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="قم بإنشاء صورة مصغرة لملف POWERPOINT في تطبيقات Android" %}}
بعد تحويل CGM إلى POWERPOINT ، يمكنك أيضًا إنشاء صور مصغرة للمستند الناتج. باستخدام ميزة غنية [Aspose.Slides لنظام Android عبر Java](https://products.aspose.com/slides/android-java/) ، يمكنك إنشاء صور مصغرة للشرائح عن طريق إنشاء ومثال [العرض التقديمي](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) فئة. بعد ذلك ، يمكنك الحصول على مرجع أي شريحة مرغوبة باستخدام معرفها أو فهرسها والحصول على صورة مصغرة للشريحة المشار إليها بمقياس محدد.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("output.powerpoint");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-pptm/" name="CGM إلى PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-xaml/" name="CGM إلى XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-ppsm/" name="CGM إلى PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-pps/" name="CGM إلى PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-otp/" name="CGM إلى OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-pot/" name="CGM إلى POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-swf/" name="CGM إلى SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-potm/" name="CGM إلى POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-potx/" name="CGM إلى POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-powerpoint/" name="CGM إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-ppsx/" name="CGM إلى PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/cgm-to-ppt/" name="CGM إلى PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}