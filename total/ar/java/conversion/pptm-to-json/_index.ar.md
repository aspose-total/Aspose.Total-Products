---
title: تحويل PPTM إلى تنسيق JSON عبر Java
description: قم بتحويل تنسيق PPTM إلى JSON عبر Java دون استخدام Microsoft Excel أو PowerPoint
url_ignore: /ar/java/conversion/pptm-to-json/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل PPTM إلى تنسيق JSON عبر Java" h2="في Premise Java API لتصدير PPTM إلى JSON بدون استخدام Microsoft<sup>&reg;</sup> Excel أو PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
تحويل PPTM إلى تنسيق JSON عبر [Aspose.Total for Java](https://products.aspose.com/total/java/) هي عملية بسيطة من خطوتين. في الخطوة الأولى ، يمكنك تصدير PPTM إلى HTML باستخدام [Aspose.Slides for Java](https://products.aspose.com/slides/java/). ثانيًا ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/java/) ، يمكنك تحويل HTML إلى JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل PPTM إلى تنسيق JSON عبر Java" %}}
1. افتح ملف PPTM باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. تحويل PPTM إلى HTML باستخدام [Save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) طريقة
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق JSON باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String%D8%8C%D9%AA20com.aspose.cells.%20SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
باستخدام API ، يمكنك أيضًا فتح المستند المحمي بكلمة مرور. إذا كان مستند PPTM الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى تنسيق JSON دون استخدام كلمة المرور. تسمح لك واجهة برمجة التطبيقات بفتح المستند المشفر عن طريق تمرير كلمة المرور الصحيحة في كائن LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل المحمي PPTM إلى تنسيق JSON عبر جافا" %}}
أثناء قيامك بتحويل PPTM إلى JSON ، يمكنك أيضًا ضبط النطاق على تنسيق JSON الناتج. لتعيين النطاق ، يمكنك فتح HTML المحول باستخدام فئة Workbook ، وإنشاء نطاق من البيانات ليتم تصديرها باستخدام طريقة Cells.createRange ، واستدعاء طريقة JsonUtility.exportRangeToJson مع مراجع Range & ExportRangeToJsonOptions وكتابة سلسلة بيانات JSON إلى ملف عبر طريقة BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



**تحويل PPTM إلى JSON** يحول محتوى الشرائح إلى تنسيق JavaScript Object Notation المهيكل، مما يتيح الوصول البرمجي والتكامل مع واجهات برمجة التطبيقات. هذا مثالي للمطورين وأنابيب الأتمتة وتطبيقات الذكاء الاصطناعي.



{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}



* تصدير بيانات الشرائح لوحات تحكم الويب الديناميكية.

* تحويل محتوى العرض إلى بيانات منظمة للتحليل.

* دمج مقاييس العرض في تطبيقات البرمجيات.

* أرشفة الشرائح في JSON لمشاريع تعتمد على البيانات وسير العمل للذكاء الاصطناعي.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات الأتمتة" %}}



* تحويل دُفعة من PPTM إلى JSON لأنابيب تكامل البيانات.

* استخراج مجدول لمحتوى الشرائح إلى تنسيقات منظمة.

* توليد JSON مُحفز لتطبيقات الويب في الوقت الحقيقي.

* التكامل في أنابيب ETL للتحليل والإبلاغ التلقائي.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}