---
title: Java API لتقديم SVG إلى XLSM
description: قم بتصدير SVG إلى XLSM عبر Java API دون استخدام Microsoft Excel أو Adobe Reader
url_ignore: /ar/java/conversion/svg-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: XLSM
otherformats: TXT EXCEL XLTX DIF TSV ODS XLT XLAM FODS XLTM MD XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير SVG إلى XLSM عبر Java" h2="قم بتحويل ملف SVG إلى XLSM باستخدام Java API داخل أي تطبيقات Java J2SE و J2EE و J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك دمج ميزة تحويل SVG إلى XLSM في تطبيقات Java في عملية من خطوتين. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) يمكنك تحويل SVG إلى XLSX. في الخطوة الثانية ، يمكنك تحويل XLSX إلى XLSM باستخدام Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف SVG إلى XLSM عبر Java" %}}
1. افتح ملف SVG باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل SVG إلى XLSX باستخدام [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) طريقة
3. قم بتحميل مستند XLSX باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق XLSM باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String%D8%8C%D9%AA20com.aspose.cells.%20SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) في ملف pom.xml الخاص بك.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
إذا كان مستند SVG الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى XLSM بدون كلمة المرور. باستخدام واجهة برمجة التطبيقات ، يمكنك أولاً فتح المستند المحمي باستخدام كلمة مرور صالحة وتحويلها بعد ذلك. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-%20java.lang.String) فئة وتمرير اسم الملف وكلمة المرور كوسيطات.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل Protected SVG إلى XLSM عبر Java" %}}
أثناء تحويل ملف SVG إلى XLSM ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف XLSM الناتج. لإضافة علامة مائية ، قم بإنشاء مصنف جديد لفتح ملف XLSX المحول. حدد ورقة العمل عبر الفهرس الخاص بها ، وأنشئ شكلًا واستخدم وظيفة addTextEffect الخاصة به ، وقم بتعيين الألوان والشفافية والمزيد. بعد ذلك يمكنك حفظ مستند XLSX كملف XLSM مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

تحويل SVG إلى XLSM (Excel Macro-Enabled Workbook) يجمع بين وضوح الرسومات الناقلة مع ماكرو Excel، مما يسمح بالتشغيل الديناميكي والتفاعل في الدفاتر.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}

* لوحات القيادة SVG المدمجة في ملفات XLSM مع ماكرو VBA لفرق الشؤون المالية.
* حلول التقارير الآلية التي تضمن تضمين النصوص مع الرسوم الناقلة.
* تحويل مخططات عمليات الهندسة إلى أوراق Excel تفاعلية ممكنة للماكرو.
* مواد تعليمية تفاعلية وبرامج تعليمية مع ماكرو في دفاتر العمل XLSM.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات التشغيل التلقائي" %}}

* تحويلات SVG-to-XLSM المجدولة للتقارير الدورية ذات الماكرو.
* حقن النصوص البرمجية الآلية في ملفات XLSM التي تم إنشاؤها من SVGs.
* التكامل مع أنظمة الذكاء التجاري التي تحتاج إلى دفاتر عمل تفاعلية.
* تدفقات عمليات التصدير المُشغَّلة للوحات القيادة الديناميكية والتقارير التشغيلية.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}