---
title: تحويل تنسيق JSON إلى EMZ عبر Java
description: تحليل JSON إلى EMZ في Java بدون استخدام Microsoft PowerPoint
url_ignore: /ar/java/conversion/json-to-emz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: EMZ
otherformats: EMZ SVGZ DXF JPEG2000 PSD WMF WMZ TGA DICOM IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل تنسيق JSON إلى EMZ عبر Java" h2="Java API لتحليل تنسيق JSON إلى EMZ في أي تطبيقات Java J2SE و J2EE و J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) ، يمكنك تحويل تنسيق JSON إلى EMZ داخل أي تطبيق Java في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/java/) ، يمكنك تحليل JSON إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) ، يمكنك تحويل JPEG إلى EMZ.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى EMZ عبر Java" %}}
1. قم بإنشاء كائن [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) جديد  وافتح ملف JSON
2. احفظ JSON بتنسيق JPEG باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String،٪20com.aspose.cells.SaveOptions)) طريقة
3. قم بتحميل مستند JPEG باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. احفظ المستند بتنسيق EMZ باستخدام [Save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) طريقة
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
علاوة على ذلك ، تسمح لك API بتحليل JSON إلى EMZ بخيارات تخطيط محددة. لتحديد خيارات التخطيط ، يمكنك استخدام فئة [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). يسمح لك بمعالجة مصفوفة كجدول ، وتجاهل القيم الخالية ، وتجاهل عنوان المصفوفة ، وتجاهل عنوان الكائن ، وتحويل السلسلة إلى رقم أو تاريخ ، وتعيين تنسيق التاريخ والأرقام ، وتعيين نمط العنوان. تتيح لك كل هذه الخيارات تقديم بياناتك وفقًا لاحتياجاتك. يوضح لك مقتطف الشفرة التالي كيفية تعيين خيارات التخطيط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بتعيين التخطيط وتحويل تنسيق JSON إلى EMZ عبر Java" %}}
باستخدام API ، يمكنك أيضًا تحويل JSON إلى EMZ بعلامة مائية في مستند EMZ الخاص بك. لإضافة علامة مائية ، يمكنك أولاً تحويل JSON إلى JPEG وإضافة علامة مائية فيه. لإضافة علامة مائية ، قم بتحميل ملف صورة باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) ، قم بإنشاء كائن من [Grpahics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) فئة وتهيئتها باستخدام كائن صورة ، وإنشاء [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) وقم بتعيين الترجمة والتحويل إلى الزاوية المطلوبة وإضافة علامة مائية باستخدام [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). بعد إضافة العلامة المائية في صورتك ، يمكنك حفظ JPEG بتنسيق EMZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
تحويل **JSON إلى EMZ (ملف تعريف محسن مضغوط)** أمر حاسم لإنشاء **رسومات ناقلة مضغوطة** من مجموعات البيانات المهيكلة. تقوم ملفات EMZ بتخزين صور عالية الجودة بحجم ملف أقل، مما يجعلها مثالية للاستخدام المتنقل وعبر المنصات. يمكن تحويل JSON إلى EMZ لتمكين عرض فعال للبيانات المهيكلة في صور احترافية ومخططات ورسوم توضيحية بينما يتم تحسين التخزين والأداء.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}

- **رسوم بيانية قابلة للتوسيع** – إنشاء رسوم بيانية مدعومة بالبيانات من JSON للعروض التقديمية والتقارير.
- **مخططات الأعمال** – بناء مخططات تنظيمية ومخططات تدفق ورسوم بصرية للعمليات.
- **رسوم توضيحية قائمة على JSON** – تحويل مجموعات بيانات مهيكلة إلى رسوم توضيحية ناقلة تقنية.
- **تخزين ناقل خفيف الوزن** – ضغط ملفات ناقلة كبيرة لتسهيل التوزيع والتخزين.
- **تكامل الرسومات عبر المنصات** – ضمان التوافق عبر تطبيقات الشركات والمنصات.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات الأتمتة" %}}

- **أنابيب JSON-to-EMZ** – أتمتة تحويل البيانات المهيكلة إلى رسومات ناقلة مضغوطة.
- **ضغط الرسوم البيانية التلقائي** – تبسيط سير العمل مع إخراجات رسوم ناقلة مضغوطة مسبقًا.
- **رسوم بيانية لتقارير مدفوعة بـ JSON** – إنشاء رسوم بصرية خفيفة الوزن وقابلة للتوسيع مباشرة من مجموعات البيانات.
- **توحيد الرسومات على مستوى الشركات** – ضمان تنسيقات رسوم ناقلة مضغوطة متسقة عبر سير العمل التنظيمية.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}