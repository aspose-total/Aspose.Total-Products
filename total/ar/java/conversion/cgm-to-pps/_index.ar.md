---
title: تحويل CGM إلى PPS عبر Java API
description: Java API لتحويل CGM إلى PPS دون استخدام Microsoft Word
url_ignore: /ar/java/conversion/cgm-to-pps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPS
otherformats: PPTM POTM SWF POTX POT POWERPOINT PPSM PPS PPT OTP XAML PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتصدير CGM إلى PPS" h2="قم بتصدير CGM إلى PPS عبر واجهة برمجة تطبيقات Java في الشركة دون استخدام Microsoft<sup>&reg;</sup> PowerPoint أو Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك بسهولة تحويل CGM إلى PPS داخل أي تطبيق Java J2SE و J2EE و J2ME. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) ، يمكنك تصدير CGM إلى PPTX. بعد ذلك ، باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API ، يمكنك تحويل PPTX إلى PPS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API لتحويل CGM إلى PPS" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل CGM إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. احفظ المستند بتنسيق PPS باستخدام طريقة [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) واضبط `` Pps` كـ SaveFormat
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
بعد تحويل CGM إلى PPS ، يمكنك أيضًا إضافة نوع عرض محدد مسبقًا لعرضك التقديمي. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) يوفر وسيلة لتعيين نوع العرض للعرض التقديمي الذي تم إنشاؤه عند فتحه في PowerPoint من خلال [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) فئة. تُستخدم خاصية [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) لتعيين نوع العرض باستخدام  العداد. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
```
تحويل ملفات CGM إلى PPS (عرض PowerPoint) يسمح بعروض جاهزة للتشغيل تفتح في وضع عرض الشرائح، مثالية للعروض التي لا تحتاج إلى تدخل أو لعروض بنمط كشك. يمكن لفرق الهندسة والشركات استخدام هذا للجولات المرئية وعروض الرسوم الثابتة.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}
- **عروض قائمة على الكشك** – حلقات عرض آلية في المعارض والمؤتمرات.
- **جولات تصميم الهندسة** – شروحات بصرية لجلسات استعراض التصميم.
- **شرائح العرض للقراءة فقط** – منع التعديلات غير المقصودة أثناء المشاركة.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات الأتمتة" %}}
- **تطبيقات الكشك بناءً على Java** – إنشاء ملفات PPS من الرسوم التخطيطية CGM للعروض العامة.
- **منشئات عروض الشرائح الديناميكية** – إنشاء عروض تكرارية تلقائيًا من البيانات الهندسية.
- **عروض تقارير غير مراقبة** – جدولة التشغيل التلقائي لدورات التقارير.
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}