---
title: قم بإزالة التعليقات التوضيحية PDF عبر الإنترنت أو قم بإدارة التعليقات التوضيحية باستخدام تطبيقات Android للجوال
description: حذف التعليقات من ملف PDF من خلال التطبيق عبر الإنترنت مجانًا.كود Android API لإدارة تعليقات ملفات PDF.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="امسح التعليقات من مستند PDF عبر الإنترنت أو قم بإدارتها عبر تطبيقات Android" h2="قم بتطوير تطبيق أداة مساعدة للتعليقات التوضيحية للمستندات PDF قوي يعمل بنظام Android.الكود المدرج لإدارة التعليقات على ملف PDF." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="إزالة التعليقات التوضيحية لـ PDF عبر الإنترنت" %}}

1. قم باستيراد ملف PDF لحذف التعليقات عن طريق تحميله
1. قم بذلك عن طريق النقر داخل منطقة الإفلات عبر السحب والإسقاط لتطبيق التعليقات التوضيحية
1. اعتمادًا على حجم ملف PDF وسرعة الإنترنت، انتظر لبضع ثوانٍ
1. انقر فوق الزر "إزالة" لمسح التعليقات
1. قم بتنزيل الملف على الفور

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="قم بإزالة تعليقات مستند PDF عبر Android App API" %}}

1. إضافة مرجع المكتبة إلى مشروع android
1. قم بتحميل المستند عبر كائن فئة المستند
1. حدد الصفحة المحددة عبر getPages().get_Item(Index)
1. استخدم AnnotationSelector واحصل على جميع التعليقات التوضيحية النصية عبر annotationSelector.getSelected()
1. قم بالتكرار خلال كل تعليق توضيحي واستدعاء طريقة الحذف لإزالته.
1. اتصل بطريقة الحفظ لحفظ الملف.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="الكود: حذف التعليقات من ملف PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="أضف تعليقًا توضيحيًا عبر Android App API" %}}

1. إضافة مرجع المكتبة إلى مشروع android
1. إنشاء كائن فئة المستند
1. أضف الصفحة الجديدة والمحتوى الجديد باستخدام getPages().add()
1. استخدم getPages().get_Item(Index) لفئة TextAnnotation
1. قم بتعيين التعليقات التوضيحية ذات الصلة مثل العنوان والموضوع والمحتوى وما إلى ذلك
1. استخدم getAnnotations().add لإضافة التعليقات التوضيحية
1. اتصل بطريقة الحفظ لحفظ الملف مع التعليقات المضافة
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="الكود: إضافة تعليق توضيحي لـ PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>تطوير تطبيق Android للتعليق على المستندات PDF</h2>

هل تحتاج إلى تطوير تطبيق جوال للتعليقات التوضيحية PDF أو أداة مساعدة لتقديم التعليقات أو تقديم الاقتراحات أو التعاون مع الآخرين في المستند؟باستخدام [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/ar/android-java/)، وهي واجهة برمجة تطبيقات فرعية لـ [Aspose.Total for Android via Java](https://products.aspose.com/total/ar/android-java/)، يمكن لأي مطور Android دمج رمز واجهة برمجة التطبيقات أعلاه في تطبيق التعليقات التوضيحية للمستند الخاص به.مكتبة أندرويد قوية تسمح ببرمجة أي حل للتعليقات التوضيحية للمستندات.علاوة على ذلك، يمكنه دعم العديد من التنسيقات الشائعة بما في ذلك تنسيق PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="مكتبة Android للتعليق على ملفات PDF" %}}

- نستضيف حزم Java الخاصة بنا في [مستودعات مافن](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java هو ملف JAR شائع يحتوي على رمز بايت.
- اتبع [تعليمات خطوه بخطوه](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) لمعرفة كيفية تثبيت Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

- أندرويد API 31 و 32
- أندرويد 4.0 وما فوق
- أدوات Android Studio وSDK

<br />
لمزيد من التفاصيل حول تبعيات الحزمة الاختيارية، مثل JogAmp JOGL ومحرك الخطوط Harfbuzz وJava Advanced Imaging JAI، يرجى الرجوع إلى [توثيق المنتج](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}