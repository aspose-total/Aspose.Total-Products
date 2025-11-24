---
title: تحويل MD إلى SWF عبر Java API
description: Java API لتحويل MD إلى SWF دون استخدام Microsoft Word
url_ignore: /ar/java/conversion/md-to-swf/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: SWF
otherformats: PPSX PPSM PPT POT POTM POWERPOINT OTP SWF XAML PPTM POTX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتصدير MD إلى SWF" h2="قم بتصدير MD إلى SWF عبر واجهة برمجة تطبيقات Java في الشركة دون استخدام Microsoft<sup>&reg;</sup> PowerPoint أو Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك بسهولة تحويل MD إلى SWF داخل أي تطبيق Java J2SE و J2EE و J2ME. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) ، يمكنك تصدير MD إلى PPTX. بعد ذلك ، باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API ، يمكنك تحويل PPTX إلى SWF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API لتحويل MD إلى SWF" %}}
1. افتح ملف MD باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل MD إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. احفظ المستند بتنسيق SWF باستخدام طريقة [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) واضبط `` Swf` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
أثناء تحميل تنسيق ملف MD ، قد يكون المستند محميًا بكلمة مرور. يسمح لك [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) بفتح المستندات المشفرة أيضًا. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String) فئة وتمرير اسم الملف وكلمة المرور كوسائط.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open MD document
Document doc = new Document("input.md", "Your@Password");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="افتح ملف MD المشفر عبر Java" %}}
بعد تحويل MD إلى SWF ، يمكنك أيضًا إضافة نوع عرض محدد مسبقًا لعرضك التقديمي. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) يوفر وسيلة لتعيين نوع العرض للعرض التقديمي الذي تم إنشاؤه عند فتحه في PowerPoint من خلال [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) فئة. تُستخدم خاصية [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) لتعيين نوع العرض باستخدام  العداد. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



تحويل Markdown (MD) إلى SWF (Shockwave Flash) يسمح بتحويل النصوص والرسوم التخطيطية والرسوم البيانية إلى تحريكات فلاش تفاعلية. SWF مثالي للمحتوى التعليمي التقليدي، والبرامج التعليمية، والعروض التقديمية على الويب.



{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}



* تحويل البرامج التعليمية Markdown إلى محتوى SWF تفاعلي.

* رسوم تخطيطية متحركة لوحدات التعلم الإلكتروني التي تم إنشاؤها من Markdown.

* عروض تقديمية تقليدية مبنية على Flash لتقديمها على الويب.

* تضمين رسوم بيانية تفاعلية من Markdown في منصات تعليمية.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات الأتمتة" %}}



* خط أنابيب تحويل Markdown إلى SWF تلقائي لمواد التدريب عبر الإنترنت.

* تحويل دفعي لمحتوى MD إلى ملفات فلاش تفاعلية.

* تحديثات مجدولة لوحدات التعلم SWF المستمدة من Markdown.

* إنشاء رسوم بيانية SWF بناءً على طلب لمنصات الويب التقليدية.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}