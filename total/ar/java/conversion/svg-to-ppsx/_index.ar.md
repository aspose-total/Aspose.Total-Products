---
title: تحويل SVG إلى PPSX عبر Java API
description: Java API لتحويل SVG إلى PPSX دون استخدام Microsoft Word
url: /ar/java/conversion/svg-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: PPSX
otherformats: PPSM PPSX POTX SWF PPS XAML PPTM POT OTP POTM PPT POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتصدير SVG إلى PPSX" h2="قم بتصدير SVG إلى PPSX عبر واجهة برمجة تطبيقات Java في الشركة دون استخدام Microsoft<sup>&reg;</sup> PowerPoint أو Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك بسهولة تحويل SVG إلى PPSX داخل أي تطبيق Java J2SE و J2EE و J2ME. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) ، يمكنك تصدير SVG إلى PPTX. بعد ذلك ، باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API ، يمكنك تحويل PPTX إلى PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API لتحويل SVG إلى PPSX" %}}
1. افتح ملف SVG باستخدام فئة [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل SVG إلى PPTX باستخدام طريقة [Save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. احفظ المستند بتنسيق PPSX باستخدام طريقة [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) واضبط `` Ppsx` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Slides for Java](https://docs.aspose.com/slides/java/ التثبيت /) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
أثناء تحميل تنسيق ملف SVG ، قد يكون المستند محميًا بكلمة مرور. يسمح لك [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) بفتح المستندات المشفرة أيضًا. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String) فئة وتمرير اسم الملف وكلمة المرور كوسائط.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open SVG document
Document doc = new Document("input.svg", "Your@Password");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="افتح ملف SVG المشفر عبر Java" %}}
بعد تحويل SVG إلى PPSX ، يمكنك أيضًا إضافة نوع عرض محدد مسبقًا لعرضك التقديمي. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) يوفر وسيلة لتعيين نوع العرض للعرض التقديمي الذي تم إنشاؤه عند فتحه في PowerPoint من خلال [ViewProperties](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) فئة. تُستخدم خاصية [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) [ViewType](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewType) لتعيين نوع العرض باستخدام  العداد. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-pps/" name="SVG ل PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-swf/" name="SVG ل SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-potx/" name="SVG ل POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-ppsx/" name="SVG ل PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-potm/" name="SVG ل POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-ppt/" name="SVG ل PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-ppsm/" name="SVG ل PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-xaml/" name="SVG ل XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-otp/" name="SVG ل OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-pptm/" name="SVG ل PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-pot/" name="SVG ل POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/svg-to-powerpoint/" name="SVG ل POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}