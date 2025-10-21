---
title: Java API لتقديم PS إلى ODS
description: قم بتصدير PS إلى ODS عبر Java API دون استخدام Microsoft Excel أو Adobe Reader
url_ignore: /ar/java/conversion/ps-to-ods/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: ODS
otherformats: ODS EXCEL XLTM XLTX TXT DIF XLSB XLSM XLT MD FODS SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير PS إلى ODS عبر Java" h2="قم بتحويل ملف PS إلى ODS باستخدام Java API داخل أي تطبيقات Java J2SE و J2EE و J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك دمج ميزة تحويل PS إلى ODS في تطبيقات Java في عملية من خطوتين. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) يمكنك تحويل PS إلى XLSX. في الخطوة الثانية ، يمكنك تحويل XLSX إلى ODS باستخدام Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف PS إلى ODS عبر Java" %}}
1. افتح ملف PS باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل PS إلى XLSX باستخدام [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) طريقة
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
إذا كان مستند PS الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى ODS بدون كلمة المرور. باستخدام واجهة برمجة التطبيقات ، يمكنك أولاً فتح المستند المحمي باستخدام كلمة مرور صالحة وتحويلها بعد ذلك. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-%20java.lang.String) فئة وتمرير اسم الملف وكلمة المرور كوسيطات.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل Protected PS إلى ODS عبر Java" %}}
أثناء تحويل ملف PS إلى ODS ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف ODS الناتج. لإضافة علامة مائية ، قم بإنشاء مصنف جديد لفتح ملف XLSX المحول. حدد ورقة العمل عبر الفهرس الخاص بها ، وأنشئ شكلًا واستخدم وظيفة addTextEffect الخاصة به ، وقم بتعيين الألوان والشفافية والمزيد. بعد ذلك يمكنك حفظ مستند XLSX كملف ODS مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

تحويل ملفات PS (PostScript) إلى ODS (OpenDocument Spreadsheet) يسمح باستيراد البيانات الجدولية والرسوم البيانية والمحتوى المنظم من مستندات PS إلى LibreOffice Calc أو منصات جداول بيانات أخرى. يضمن هذا نقل البيانات والتوافق عبر بيئات مفتوحة المصدر.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}

* استخراج الجداول المالية أو التشغيلية من تقارير PS إلى جداول بيانات ODS.
* تحويل الرسوم البيانية الهندسية أو العلمية PS لتحليل مفتوح المصدر.
* إعداد مجموعات البيانات لإدارة المشاريع التعاونية باستخدام LibreOffice.
* تحويل تخطيطات PS إلى قوالب جداول بيانات للتقارير المتكررة.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات الأتمتة" %}}

* تحويل PS إلى ODS تلقائيًا في خطوط معالجة البيانات.
* تحويل دفعة من التقارير التي تم إنشاؤها بواسطة PostScript لتحليل الجداول.
* الدمج في حلول جداول البيانات مفتوحة المصدر المستندة إلى السحابة.
* استخراج الرسوم البيانية والجداول من PS بمساعدة الذكاء الاصطناعي إلى تنسيق ODS.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}