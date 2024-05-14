---
title: قم بإزالة التعليقات التوضيحية CSV عبر الإنترنت أو قم بإدارة التعليقات التوضيحية باستخدام تطبيقات Android للجوال
description: حذف التعليقات من ملف CSV من خلال التطبيق عبر الإنترنت مجانًا.كود Android API لإدارة تعليقات ملفات CSV.

family: total
platformtag: Android
feature: Annotate
informat: CSV
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="امسح التعليقات من مستند CSV عبر الإنترنت أو قم بإدارتها عبر تطبيقات Android" h2="قم بتطوير تطبيق أداة مساعدة للتعليقات التوضيحية للمستندات CSV قوي يعمل بنظام Android.الكود المدرج لإدارة التعليقات على ملف CSV." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="إزالة التعليقات التوضيحية لـ CSV عبر الإنترنت" %}}

1. قم باستيراد ملف CSV لحذف التعليقات عن طريق تحميله
1. قم بذلك عن طريق النقر داخل منطقة الإفلات عبر السحب والإسقاط لتطبيق التعليقات التوضيحية
1. اعتمادًا على حجم ملف CSV وسرعة الإنترنت، انتظر لبضع ثوانٍ
1. انقر فوق الزر "إزالة" لمسح التعليقات
1. قم بتنزيل الملف على الفور

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="قم بإزالة تعليقات مستند CSV عبر Android App API" %}}

1. إضافة مرجع المكتبة إلى مشروع Android
1. قم بتحميل المستند عبر كائن فئة المصنف
1. حدد ورقة العمل المحددة
1. احصل على كافة التعليقات من استخدام [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)
1. احصل على جميع التعليقات المترابطة عبر getThreadedComments
1. استخدم RemoveAt لإزالة التعليقات والمؤلفين على التوالي
1. اتصل بطريقة الحفظ لحفظ الملف
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="الكود: إزالة التعليقات من مستند CSV" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحديث تعليقات CSV المترابطة" %}}

1. قم بتحميل المستند عبر كائن فئة المصنف
1. احصل على ورقة العمل المحددة
1. احصل على التعليق المترابط باستخدام getComments().getThreadedComments(Index).get(Index)
1. استخدم طريقة setNotes لتحديث التعليق
1. اتصل بطريقة الحفظ لحفظ الملف

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="أضف تعليقات عبر Android App API" %}}

1. إنشاء مستند عبر كائن فئة المصنف
1. احصل على ورقة العمل المحددة
1. إضافة فهرس التعليق عبر getComments().add
1. استخدم طريقة setNotes لإضافة تعليق
1. اتصل بطريقة الحفظ لحفظ الملف with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="الكود: تحديث التعليق المترابط لملف CSV" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="الكود: إضافة تعليقات" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>تطوير تطبيق Android للتعليق على المستندات CSV</h2>

هل تحتاج إلى تطوير تطبيق أو أداة مساعدة للتعليقات التوضيحية CSV تعتمد على نظام Android لتقديم التعليقات أو تقديم الاقتراحات أو التعاون مع الآخرين في المستند؟باستخدام [Aspose.Cells for Android via Java](https://products.aspose.com/cells/ar/android-java/)، وهي واجهة برمجة تطبيقات فرعية لـ [Aspose.Total for Android via Java](https://products.aspose.com/total/ar/android-java/)، يمكن لأي مطور Android دمج رمز واجهة برمجة التطبيقات أعلاه في تطبيق التعليقات التوضيحية للمستند الخاص به.مكتبة أندرويد قوية تسمح ببرمجة أي حل للتعليقات التوضيحية للمستندات.علاوة على ذلك، يمكنه دعم العديد من التنسيقات الشائعة بما في ذلك تنسيق CSV.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API لتعليق ملفات CSV" %}}

- نستضيف حزم Java الخاصة بنا في [مستودعات مافن](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/). 
- Aspose.Cells for Java هو ملف JAR شائع يحتوي على رمز بايت.
- اتبع [تعليمات خطوه بخطوه](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) لمعرفة كيفية تثبيت Aspose.Cells for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

- نظام التشغيل أندرويد 2.0 أو أعلى.
- حزمة Java عبارة عن منصة مشتركة وتعمل على جميع أنظمة التشغيل مع تطبيق JVM.

<br />
لمزيد من التفاصيل يرجى الرجوع إلى [توثيق المنتج](https://docs.aspose.com/cells/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}