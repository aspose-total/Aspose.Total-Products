---
title: تحويل تنسيق JSON إلى WMF عبر Java
description: تحليل JSON إلى WMF في Java بدون استخدام Microsoft PowerPoint
url_ignore: /ar/java/conversion/json-to-wmf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WMF
otherformats: TGA DICOM JPEG2000 WMZ EMZ PSD WMF DXF SVGZ IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل تنسيق JSON إلى WMF عبر Java" h2="Java API لتحليل تنسيق JSON إلى WMF في أي تطبيقات Java J2SE و J2EE و J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) ، يمكنك تحويل تنسيق JSON إلى WMF داخل أي تطبيق Java في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/java/) ، يمكنك تحليل JSON إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) ، يمكنك تحويل JPEG إلى WMF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى WMF عبر Java" %}}
1. قم بإنشاء كائن [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) جديد  وافتح ملف JSON
2. احفظ JSON بتنسيق JPEG باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String،٪20com.aspose.cells.SaveOptions)) طريقة
3. قم بتحميل مستند JPEG باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. احفظ المستند بتنسيق WMF باستخدام [Save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) طريقة
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
علاوة على ذلك ، تسمح لك API بتحليل JSON إلى WMF بخيارات تخطيط محددة. لتحديد خيارات التخطيط ، يمكنك استخدام فئة [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). يسمح لك بمعالجة مصفوفة كجدول ، وتجاهل القيم الخالية ، وتجاهل عنوان المصفوفة ، وتجاهل عنوان الكائن ، وتحويل السلسلة إلى رقم أو تاريخ ، وتعيين تنسيق التاريخ والأرقام ، وتعيين نمط العنوان. تتيح لك كل هذه الخيارات تقديم بياناتك وفقًا لاحتياجاتك. يوضح لك مقتطف الشفرة التالي كيفية تعيين خيارات التخطيط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بتعيين التخطيط وتحويل تنسيق JSON إلى WMF عبر Java" %}}
باستخدام API ، يمكنك أيضًا تحويل JSON إلى WMF بعلامة مائية في مستند WMF الخاص بك. لإضافة علامة مائية ، يمكنك أولاً تحويل JSON إلى JPEG وإضافة علامة مائية فيه. لإضافة علامة مائية ، قم بتحميل ملف صورة باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) ، قم بإنشاء كائن من [Grpahics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) فئة وتهيئتها باستخدام كائن صورة ، وإنشاء [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) وقم بتعيين الترجمة والتحويل إلى الزاوية المطلوبة وإضافة علامة مائية باستخدام [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). بعد إضافة العلامة المائية في صورتك ، يمكنك حفظ JPEG بتنسيق WMF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
تحويل **JSON إلى WMF** ضروري لإنتاج **رسومات Windows Metafile من البيانات المهيكلة**. توفر ملفات WMF رسومات ناقلة قابلة للتوسيع متوافقة مع تطبيقات Windows القديمة ومستندات Office. من خلال تحويل JSON إلى WMF، يمكن للمؤسسات أتمتة إنشاء الرسوم التخطيطية والمخططات والرسوم التوضيحية التقنية مع ضمان الاتساق والتوافق عبر سير العمل الشركات.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}

- **تطبيقات Windows القديمة** – الحفاظ على التوافق مع البرامج القديمة التي تتطلب رسومات WMF.
- **الرسوم التخطيطية القابلة للتوسيع** – إنشاء رسوم تخطيطية قائمة على الناقل تتحسن دون فقدان الجودة.
- **تكامل مستندات Office** – تضمين رسومات WMF مباشرة في ملفات Word وPowerPoint وExcel.
- **مخططات الأعمال** – أتمتة إنشاء المخططات من مجموعات البيانات المهيكلة للإبلاغ الشركات.
- **الرسوم التوضيحية التقنية** – إنشاء رسوم توضيحية دقيقة وقائمة على البيانات للدلائل والوثائق الهندسية.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات التأتير الآلي" %}}

- **أنابيب JSON-to-WMF** – أتمتة تحويل البيانات المهيكلة إلى رسومات ناقلة WMF.
- **إنشاء رسوم ناقلة آليًا** – تقليل إنشاء الرسوم التخطيطية والرسوم التوضيحية يدويًا.
- **عرض المخططات المدفوعة بـ JSON** – ملء المخططات والرسوم البصرية مباشرة من مجموعات البيانات.
- **سير العمل للرسوم التوضيحية على مستوى المؤسسة** – دمج إنتاج WMF في أنابيب توثيق الشركات.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}