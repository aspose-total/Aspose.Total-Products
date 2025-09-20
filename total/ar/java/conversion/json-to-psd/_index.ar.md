---
title: تحويل تنسيق JSON إلى PSD عبر Java
description: تحليل JSON إلى PSD في Java بدون استخدام Microsoft PowerPoint
url_ignore: /ar/java/conversion/json-to-psd/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PSD
otherformats: SVGZ WMF DICOM DXF IMAGE TGA EMZ PSD WMZ JPEG2000
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل تنسيق JSON إلى PSD عبر Java" h2="Java API لتحليل تنسيق JSON إلى PSD في أي تطبيقات Java J2SE و J2EE و J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) ، يمكنك تحويل تنسيق JSON إلى PSD داخل أي تطبيق Java في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/java/) ، يمكنك تحليل JSON إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) ، يمكنك تحويل JPEG إلى PSD.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى PSD عبر Java" %}}
1. قم بإنشاء كائن [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) جديد  وافتح ملف JSON
2. احفظ JSON بتنسيق JPEG باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String،٪20com.aspose.cells.SaveOptions)) طريقة
3. قم بتحميل مستند JPEG باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. احفظ المستند بتنسيق PSD باستخدام [Save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) طريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
علاوة على ذلك ، تسمح لك API بتحليل JSON إلى PSD بخيارات تخطيط محددة. لتحديد خيارات التخطيط ، يمكنك استخدام فئة [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). يسمح لك بمعالجة مصفوفة كجدول ، وتجاهل القيم الخالية ، وتجاهل عنوان المصفوفة ، وتجاهل عنوان الكائن ، وتحويل السلسلة إلى رقم أو تاريخ ، وتعيين تنسيق التاريخ والأرقام ، وتعيين نمط العنوان. تتيح لك كل هذه الخيارات تقديم بياناتك وفقًا لاحتياجاتك. يوضح لك مقتطف الشفرة التالي كيفية تعيين خيارات التخطيط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بتعيين التخطيط وتحويل تنسيق JSON إلى PSD عبر Java" %}}
باستخدام API ، يمكنك أيضًا تحويل JSON إلى PSD بعلامة مائية في مستند PSD الخاص بك. لإضافة علامة مائية ، يمكنك أولاً تحويل JSON إلى JPEG وإضافة علامة مائية فيه. لإضافة علامة مائية ، قم بتحميل ملف صورة باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) ، قم بإنشاء كائن من [Grpahics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) فئة وتهيئتها باستخدام كائن صورة ، وإنشاء [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) وقم بتعيين الترجمة والتحويل إلى الزاوية المطلوبة وإضافة علامة مائية باستخدام [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). بعد إضافة العلامة المائية في صورتك ، يمكنك حفظ JPEG بتنسيق PSD. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
تحويل **JSON إلى PSD** ضروري لإنشاء **ملفات تصميم Photoshop من البيانات المنظمة**. تحتفظ ملفات PSD بالطبقات والنصوص والتأثيرات، مما يتيح للمصممين العمل مع رسومات قابلة للتحرير بالكامل تم إنشاؤها من مجموعات بيانات ديناميكية. من خلال تحويل JSON إلى PSD، يمكن للمؤسسات تبسيط سير العمل الإبداعي، وتأتيمين الرسومات التسويقية، وإنتاج أصول تصميم شخصية، جاهزة للطباعة أو الرقمية بكفاءة.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}

- **تصميم رسومي ديناميكي** – إنشاء ملفات تصميم متعددة الطبقات تتكيف مع تغيير مجموعات البيانات.
- **إنشاء إبداعي تسويقي مؤتمت** – إنتاج لافتات، وسائل التواصل الاجتماعي، ورسومات حملات تلقائيًا.
- **قوالب صور شخصية** – إنشاء قوالب مخصصة لمحتوى محدد للعملاء.
- **نماذج واجهة مواقع الويب والتطبيقات** – بناء نماذج تفاعلية لمواقع الويب وتطبيقات الجوال.
- **أعمال فنية جاهزة للطباعة** – إعداد ملفات PSD عالية الجودة للطباعة المهنية.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات التأتيم" %}}

- **أنابيب JSON-to-PSD** – أتمتة تحويل البيانات المنظمة إلى ملفات Photoshop متعددة الطبقات.
- **إنشاء طبقات Photoshop مؤتمتة** – إنشاء طبقات قابلة للتحرير برمجيًا لتحقيق الكفاءة.
- **سير العمل التصميمية المدفوعة بالبيانات** – دمج مجموعات البيانات مباشرة في العمليات الإبداعية.
- **أتمتة الإبداع المدفوع بـ JSON** – توسيع إنتاج التصميم عبر مشاريع التسويق، والويب، والطباعة.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}