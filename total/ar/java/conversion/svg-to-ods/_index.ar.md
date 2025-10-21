---
title: Java API لتقديم SVG إلى ODS
description: قم بتصدير SVG إلى ODS عبر Java API دون استخدام Microsoft Excel أو Adobe Reader
url_ignore: /ar/java/conversion/svg-to-ods/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: ODS
otherformats: XLSB MD FODS XLTX XLAM DIF XLSM XLT XLTM ODS SXC EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير SVG إلى ODS عبر Java" h2="قم بتحويل ملف SVG إلى ODS باستخدام Java API داخل أي تطبيقات Java J2SE و J2EE و J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك دمج ميزة تحويل SVG إلى ODS في تطبيقات Java في عملية من خطوتين. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) يمكنك تحويل SVG إلى XLSX. في الخطوة الثانية ، يمكنك تحويل XLSX إلى ODS باستخدام Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف SVG إلى ODS عبر Java" %}}
1. افتح ملف SVG باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل SVG إلى XLSX باستخدام [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) طريقة
3. قم بتحميل مستند XLSX باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق ODS باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String%D8%8C%D9%AA20com.aspose.cells.%20SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) في ملف pom.xml الخاص بك.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
إذا كان مستند SVG الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى ODS بدون كلمة المرور. باستخدام واجهة برمجة التطبيقات ، يمكنك أولاً فتح المستند المحمي باستخدام كلمة مرور صالحة وتحويلها بعد ذلك. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-%20java.lang.String) فئة وتمرير اسم الملف وكلمة المرور كوسيطات.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل Protected SVG إلى ODS عبر Java" %}}
أثناء تحويل ملف SVG إلى ODS ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف ODS الناتج. لإضافة علامة مائية ، قم بإنشاء مصنف جديد لفتح ملف XLSX المحول. حدد ورقة العمل عبر الفهرس الخاص بها ، وأنشئ شكلًا واستخدم وظيفة addTextEffect الخاصة به ، وقم بتعيين الألوان والشفافية والمزيد. بعد ذلك يمكنك حفظ مستند XLSX كملف ODS مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

تحويل ملفات SVG إلى ODS (جدول بيانات OpenDocument) يمكن تضمين الرسوم البيانية القائمة على النواة في جداول بيانات قياسية مفتوحة. ODS مثالي لتحليل البيانات عبر الأنظمة الأساسية، وإعداد التقارير، ولوحات التحكم التفاعلية.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}

* تضمين لوحات البيانات المالية القائمة على النواة في جداول بيانات ODS للتحليل.
* مشاركة البيانات البحثية أو الهندسية مع رسوم بيانية قائمة على النواة في تنسيقات مفتوحة.
* تصدير البيانات الأكاديمية والمشروعات كجداول بيانات قابلة للتحرير وغير معتمدة على النظام الأساسي.
* توحيد لوحات تتبع المشروعات بتنسيق ODS.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات التلقائية" %}}

* تحويل SVG إلى ODS تلقائيًا لأنابيب التقارير.
* تصدير البيانات البحثية أو التشغيلية بانتظام مع الرسوم البيانية المضمنة.
* التكامل مع حزم البرامج المكتبية مفتوحة المصدر التي تتطلب توافق الجداول.
* توليد لوحات قائمة على النواة بناءً على SVG للتعاون في الفريق.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}