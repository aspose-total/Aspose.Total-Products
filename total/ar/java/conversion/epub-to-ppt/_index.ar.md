---
title: تحويل EPUB إلى PPT عبر Java API
description: Java API لتحويل EPUB إلى PPT دون استخدام Microsoft Word
url_ignore: /ar/java/conversion/epub-to-ppt/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPT
otherformats: POWERPOINT PPT PPS PPTM XAML SWF POT OTP POTX PPSX POTM PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتصدير EPUB إلى PPT" h2="قم بتصدير EPUB إلى PPT عبر واجهة برمجة تطبيقات Java في الشركة دون استخدام Microsoft<sup>&reg;</sup> PowerPoint أو Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك بسهولة تحويل EPUB إلى PPT داخل أي تطبيق Java J2SE و J2EE و J2ME. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) ، يمكنك تصدير EPUB إلى PPTX. بعد ذلك ، باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API ، يمكنك تحويل PPTX إلى PPT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API لتحويل EPUB إلى PPT" %}}
1. افتح ملف EPUB باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل EPUB إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. احفظ المستند بتنسيق PPT باستخدام طريقة [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) واضبط `` Ppt` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
أثناء تحميل تنسيق ملف EPUB ، قد يكون المستند محميًا بكلمة مرور. يسمح لك [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) بفتح المستندات المشفرة أيضًا. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String) فئة وتمرير اسم الملف وكلمة المرور كوسائط.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="افتح ملف EPUB المشفر عبر Java" %}}
بعد تحويل EPUB إلى PPT ، يمكنك أيضًا إضافة نوع عرض محدد مسبقًا لعرضك التقديمي. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) يوفر وسيلة لتعيين نوع العرض للعرض التقديمي الذي تم إنشاؤه عند فتحه في PowerPoint من خلال [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) فئة. تُستخدم خاصية [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) لتعيين نوع العرض باستخدام  العداد. 
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
تحويل **EPUB إلى PPT (عرض تقديمي بوربوينت)** أمر أساسي لإنشاء **ملفات عروض تقديمية قابلة للتحرير** من النشرات الرقمية. تتيح ملفات PPT تحويل محتوى الكتب الإلكترونية إلى شرائح قابلة للتخصيص بالكامل، مما يتيح للمعلمين والباحثين والشركات إنشاء عروض تقديمية احترافية بكفاءة. من خلال تحويل EPUB إلى PPT، يمكن للمؤسسات تبسيط إنشاء الشرائح، والحفاظ على توحيد المحتوى، وتعزيز سير العمل لمشاركة المعرفة.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}
- **شرائح أكاديمية** – تحويل فصول الكتب الدراسية إلى عروض محاضرات منظمة وقابلة للتحرير.
- **عروض شركات** – إنشاء عروض تقديمية للأعمال من النشرات والتقارير الصناعية.
- **عروض بحثية** – إنشاء شرائح احترافية للمؤتمرات والندوات.
- **مواد دار النشر** – إعادة استخدام محتوى الكتب الإلكترونية لصنع عروض تسويقية وترويجية.
- **جلسات تدريب تعليمية** – تطوير شرائح تعليمية لورش العمل وبرامج التعلم الإلكتروني.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات التأتير" %}}
- **أنابيب EPUB-to-PPT** – أتمتة تحويل الكتب الإلكترونية إلى شرائح بوربوينت.
- **إنشاء عروض تقديمية مؤتمتة** – إنشاء عروض جاهزة للتحرير بسرعة من عدة منشورات.
- **تحويل النشر الجماعي إلى PPT** – تحويل مجموعات كبيرة من الكتب الإلكترونية بكفاءة إلى شرائح.
- **أتمتة العروض التقديمية للشركات** – دمج إنشاء PPT في سير العمل التعليمي ومشاركة المعرفة في المؤسسات.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}