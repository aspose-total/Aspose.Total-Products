---
title: قم بإزالة التعليقات التوضيحية DOTX عبر الإنترنت أو قم بإدارة التعليقات التوضيحية باستخدام تطبيقات Android للجوال
description: حذف التعليقات من ملف DOTX من خلال التطبيق عبر الإنترنت مجانًا.كود Android API لإدارة تعليقات ملفات DOTX.

family: total
platformtag: Android
feature: Annotate
informat: DOTX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="امسح التعليقات من مستند DOTX عبر الإنترنت أو قم بإدارتها عبر تطبيقات Android" h2="قم بتطوير تطبيق أداة مساعدة للتعليقات التوضيحية للمستندات DOTX قوي يعمل بنظام Android.الكود المدرج لإدارة التعليقات على ملف DOTX." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="إزالة التعليقات التوضيحية لـ DOTX عبر الإنترنت" %}}

1. قم باستيراد ملف DOTX لحذف التعليقات عن طريق تحميله
1. قم بذلك عن طريق النقر داخل منطقة الإفلات عبر السحب والإسقاط لتطبيق التعليقات التوضيحية
1. اعتمادًا على حجم ملف DOTX وسرعة الإنترنت، انتظر لبضع ثوانٍ
1. انقر فوق الزر "إزالة" لمسح التعليقات
1. قم بتنزيل الملف على الفور

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="قم بإزالة تعليقات مستند DOTX عبر تطبيق Android" %}}

1. إضافة مرجع المكتبة إلى مشروع android
1. قم بتحميل المستند عبر كائن فئة المستند
1. احصل على كافة التعليقات من جميع العقد باستخدام [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) وNodeType.COMMENT
1. قم باستدعاء طريقة [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) لحذف جميع التعليقات
1. اتصل بطريقة الحفظ لحفظ الملف.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="الكود: حذف التعليقات من ملف DOTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="إزالة وإضافة تعليق الرد DOTX" %}}

1. إضافة مرجع المكتبة إلى مشروع android
1. قم بتحميل المستند عبر كائن فئة المستند
1. احصل على تعليق باستخدام getChild
1. استخدم [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) لإزالة الرد المحدد على هذا التعليق
1. استخدم [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) لإضافة أي رد على هذا التعليق
1. اتصل بطريقة الحفظ لحفظ الملف

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="أضف تعليقات عبر تطبيق Android" %}}

1. إضافة مرجع المكتبة إلى مشروع android
1. إنشاء كائن فئة المستند
1. استخدم [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) لإنشاء التعليق
1. استخدم getParagraphs().add و getFirstParagraph().getRuns().add
1. اتصل بطريقة الحفظ لحفظ الملف with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="الكود: إزالة وإضافة تعليق الرد من ملف DOTX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="الكود: إضافة تعليقات" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>تطوير تطبيق Android للتعليق على المستندات DOTX</h2>

هل تحتاج إلى تطوير تطبيق جوال للتعليقات التوضيحية DOTX أو أداة مساعدة لتقديم التعليقات أو تقديم الاقتراحات أو التعاون مع الآخرين في المستند؟باستخدام [Aspose.Words for Android via Java](https://products.aspose.com/words/ar/android-java/)، وهي واجهة برمجة تطبيقات فرعية لـ [Aspose.Total for Android via Java](https://products.aspose.com/total/ar/android-java/)، يمكن لأي مطور Android دمج كود واجهة برمجة التطبيقات أعلاه داخل تطبيق التعليقات التوضيحية للمستند الخاص به.مكتبة أندرويد قوية تسمح ببرمجة أي حل للتعليقات التوضيحية للمستندات.علاوة على ذلك، يمكنه دعم العديد من التنسيقات الشائعة بما في ذلك تنسيق DOTX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="مكتبة Android للتعليق على ملفات DOTX" %}}

- نستضيف حزم Java الخاصة بنا في [مستودعات مافن](https://releases.aspose.com/java/repo/com/aspose/aspose-words/). 
- Aspose.Words for Java هو ملف JAR شائع يحتوي على رمز بايت.
- اتبع [تعليمات خطوه بخطوه](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) لمعرفة كيفية تثبيت Aspose.Words for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

- يتم دعم Java SE 7 وإصدارات Java الأحدث.
- حزمة منفصلة لـ Java SE 6 في حالة اضطرار المرء لاستخدام JRE قديم.
- حزمة Java عبارة عن منصة مشتركة وتعمل على جميع أنظمة التشغيل مع تطبيق JVM.
- تشمل أنظمة التشغيل Microsoft Windows وLinux وmacOS وAndroid وiOS.

<br />
لمزيد من التفاصيل حول تبعيات الحزمة الاختيارية، مثل JogAmp JOGL ومحرك الخطوط Harfbuzz وJava Advanced Imaging JAI، يرجى الرجوع إلى [توثيق المنتج](https://docs.aspose.com/words/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}