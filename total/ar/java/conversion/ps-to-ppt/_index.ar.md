---
title: تحويل PS إلى PPT عبر Java API
description: Java API لتحويل PS إلى PPT دون استخدام Microsoft Word
url_ignore: /ar/java/conversion/ps-to-ppt/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPT
otherformats: SWF XAML OTP POTM POWERPOINT POT PPTM PPSM POTX PPT PPSX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتصدير PS إلى PPT" h2="قم بتصدير PS إلى PPT عبر واجهة برمجة تطبيقات Java في الشركة دون استخدام Microsoft<sup>&reg;</sup> PowerPoint أو Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك بسهولة تحويل PS إلى PPT داخل أي تطبيق Java J2SE و J2EE و J2ME. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) ، يمكنك تصدير PS إلى PPTX. بعد ذلك ، باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API ، يمكنك تحويل PPTX إلى PPT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API لتحويل PS إلى PPT" %}}
1. افتح ملف PS باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل PS إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. احفظ المستند بتنسيق PPT باستخدام طريقة [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) واضبط `` Ppt` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
أثناء تحميل تنسيق ملف PS ، قد يكون المستند محميًا بكلمة مرور. يسمح لك [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) بفتح المستندات المشفرة أيضًا. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String) فئة وتمرير اسم الملف وكلمة المرور كوسائط.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="افتح ملف PS المشفر عبر Java" %}}
بعد تحويل PS إلى PPT ، يمكنك أيضًا إضافة نوع عرض محدد مسبقًا لعرضك التقديمي. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) يوفر وسيلة لتعيين نوع العرض للعرض التقديمي الذي تم إنشاؤه عند فتحه في PowerPoint من خلال [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) فئة. تُستخدم خاصية [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) لتعيين نوع العرض باستخدام  العداد. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

تحويل ملفات PS (PostScript) إلى PPT (تنسيق باوربوينت القديم) يسمح للمؤسسات بالحفاظ على التوافق مع الإصدارات القديمة من Microsoft Office. يضمن تنسيق PPT أن يمكن تحرير شرائح PostScript وعرضها عبر مجموعة واسعة من البيئات.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}

* تحويل العروض التقديمية القائمة على PS لبيئات Office القديمة.
* إعداد شرائح تدريبية أو تسويقية أو تجارية بتنسيق PPT.
* إعادة استخدام الرسوم التخطيطية والتخطيطات الخاصة بـ PostScript للحصول على التوافق الخلفي.
* ترحيل الرسوم البيانية التقنية إلى عروض باوربوينت قابلة للتحرير بالإصدارات القديمة.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات التشغيل التلقائي" %}}

* تحويل دفعة من PS إلى PPT لأرشيفات الشركات.
* التكامل مع أدوات سير العمل لتوليد PPT تلقائيًا.
* تحويل مجدول لتقارير PS إلى تنسيقات عروض العرض القديمة.
* استخراج مساعد بالذكاء الاصطناعي للرسوم البيانية والتخطيطات لشرائح PPT قابلة للتحرير.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}