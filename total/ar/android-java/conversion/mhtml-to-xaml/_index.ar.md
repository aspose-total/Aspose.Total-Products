---
title: تصدير MHTML إلى XAML في Android
description: Android API لتحويل MHTML إلى XAML دون استخدام Microsoft Word
url: /ar/android-java/conversion/mhtml-to-xaml/
family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: XAML
otherformats: POTX PPTM POT PPT PPSX PPS ODP PPSM OTP POWERPOINT SWF POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل MHTML إلى XAML على Android عبر Java" h2="تحويل MHTML إلى XAML داخل تطبيقات Android دون استخدام Microsoft <sup>&reg;</sup> PowerPoint أو Adobe <sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك دمج ميزة تحويل MHTML إلى XAML داخل تطبيقات Android باستخدام خطوتين بسيطتين. في الخطوة الأولى ، يمكنك تصدير MHTML إلى PPTX باستخدام [Aspose.PDF لنظام Android عبر Java](https://products.aspose.com/pdf/android-java/). بعد ذلك ، باستخدام [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) ، يمكنك تحويل PPTX إلى XAML. تأتي كلتا واجهتي برمجة التطبيقات ضمن حزمة [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API لتصدير MHTML إلى XAML" %}}
1. افتح ملف MHTML باستخدام فئة [المستند](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل MHTML إلى PPTX باستخدام طريقة [حفظ](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. احفظ المستند بتنسيق XAML باستخدام طريقة [حفظ](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) واضبط `` Xaml` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total لنظام Android عبر Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.PDF لنظام Android عبر Java](https://docs.aspose.com/pdf/androidjava/installation/) و [Aspose.Slides لنظام Android عبر Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Xaml format
presentation.save("output.xaml", SaveFormat.Xaml);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="افتح ملف MHTML المحمي بكلمة مرور في Android عبر Java" %}}
أثناء تحميل تنسيق ملف MHTML ، قد يكون المستند محميًا بكلمة مرور. يسمح لك [Aspose.PDF لنظام Android عبر Java](https://products.aspose.com/pdf/android-java/) بفتح المستندات المشفرة أيضًا. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [المستند](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) فئة وتمرير اسم الملف وكلمة المرور كوسائط.
{{% blocks/products/pf/feature-page-code %}}

```java
// open MHTML document
Document doc = new Document("input.mhtml", "Your@Password");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="قم بإنشاء صورة مصغرة لملف XAML في تطبيقات Android" %}}
بعد تحويل MHTML إلى XAML ، يمكنك أيضًا إنشاء صور مصغرة للمستند الناتج. باستخدام ميزة غنية [Aspose.Slides لنظام Android عبر Java](https://products.aspose.com/slides/android-java/) ، يمكنك إنشاء صور مصغرة للشرائح عن طريق إنشاء ومثال [العرض التقديمي]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) فئة. بعد ذلك ، يمكنك الحصول على مرجع أي شريحة مرغوبة باستخدام معرفها أو فهرسها والحصول على صورة مصغرة للشريحة المشار إليها بمقياس محدد.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a XAML file
Presentation presentation = new Presentation("output.xaml");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-potx/" name="MHTML إلى POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-pptm/" name="MHTML إلى PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-pot/" name="MHTML إلى POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-ppt/" name="MHTML إلى PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-ppsx/" name="MHTML إلى PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-pps/" name="MHTML إلى PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-xaml/" name="MHTML إلى XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-ppsm/" name="MHTML إلى PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-otp/" name="MHTML إلى OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-powerpoint/" name="MHTML إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-swf/" name="MHTML إلى SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/mhtml-to-potm/" name="MHTML إلى POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}