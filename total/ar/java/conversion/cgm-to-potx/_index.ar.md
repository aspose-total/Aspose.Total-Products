---
title: تحويل CGM إلى POTX عبر Java API
description: Java API لتحويل CGM إلى POTX دون استخدام Microsoft Word
url_ignore: /ar/java/conversion/cgm-to-potx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POTX
otherformats: PPTM POT PPS PPSX PPSM POTM POTX OTP PPT SWF XAML POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتصدير CGM إلى POTX" h2="قم بتصدير CGM إلى POTX عبر واجهة برمجة تطبيقات Java في الشركة دون استخدام Microsoft<sup>&reg;</sup> PowerPoint أو Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك بسهولة تحويل CGM إلى POTX داخل أي تطبيق Java J2SE و J2EE و J2ME. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) ، يمكنك تصدير CGM إلى PPTX. بعد ذلك ، باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API ، يمكنك تحويل PPTX إلى POTX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API لتحويل CGM إلى POTX" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل CGM إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. احفظ المستند بتنسيق POTX باستخدام طريقة [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) واضبط `` Potx` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
أثناء تحميل تنسيق ملف CGM ، قد يكون المستند محميًا بكلمة مرور. يسمح لك [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) بفتح المستندات المشفرة أيضًا. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String) فئة وتمرير اسم الملف وكلمة المرور كوسائط.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="افتح ملف CGM المشفر عبر Java" %}}
بعد تحويل CGM إلى POTX ، يمكنك أيضًا إضافة نوع عرض محدد مسبقًا لعرضك التقديمي. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) يوفر وسيلة لتعيين نوع العرض للعرض التقديمي الذي تم إنشاؤه عند فتحه في PowerPoint من خلال [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) فئة. تُستخدم خاصية [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) لتعيين نوع العرض باستخدام  العداد. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potx format
presentation.save("output.potx", SaveFormat.Potx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
```
تحويل CGM إلى POTX (قالب عرض Open XML) يوفر تنسيق قالب مرن وحديث لسير العمل في العروض التقديمية للأعمال والهندسة. يدعم POTX الرسومات الناقلة، مما يجعله مثاليًا للرسوم البيانية التقنية المعتمدة على CGM التي تحتاج إلى إعادة استخدامها عبر عروض شرائح متعددة.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}
- **تقارير بصرية معيارية للصناعة** – إعداد تخطيطات احترافية لعروض العملاء وأصحاب المصلحة.
- **قوالب تصميم الهندسة** – تضمين الرسوم البيانية الناقلة القابلة للتوسيع في تخطيطات قابلة لإعادة الاستخدام.
- **شرائح معلوماتية قابلة لإعادة الاستخدام** – ضمان هوية الشركة المتسقة عبر الأقسام المختلفة.

## ⚙️ سيناريوهات التأتير
- **أنظمة الوثائق Open XML القائمة على Java** – أتمتة تحويل CGM إلى POTX باستخدام واجهات برمجة التطبيقات Apache POI XSLF.
- **أتمتة محتوى المؤسسات** – تبسيط إنشاء مكتبات القوالب المميزة.
- **أنابيب العروض المقننة** – دمجها في أنابيب CI/CD لإعداد العروض التلقائي.
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}