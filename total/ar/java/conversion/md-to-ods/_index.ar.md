---
title: Java API لتقديم MD إلى ODS
description: قم بتصدير MD إلى ODS عبر Java API دون استخدام Microsoft Excel أو Adobe Reader
url_ignore: /ar/java/conversion/md-to-ods/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: ODS
otherformats: TXT XLT TSV ODS XLAM EXCEL XLTX DIF FODS SXC XLSB XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير MD إلى ODS عبر Java" h2="قم بتحويل ملف MD إلى ODS باستخدام Java API داخل أي تطبيقات Java J2SE و J2EE و J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك دمج ميزة تحويل MD إلى ODS في تطبيقات Java في عملية من خطوتين. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) يمكنك تحويل MD إلى XLSX. في الخطوة الثانية ، يمكنك تحويل XLSX إلى ODS باستخدام Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف MD إلى ODS عبر Java" %}}
1. افتح ملف MD باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل MD إلى XLSX باستخدام [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) طريقة
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
إذا كان مستند MD الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى ODS بدون كلمة المرور. باستخدام واجهة برمجة التطبيقات ، يمكنك أولاً فتح المستند المحمي باستخدام كلمة مرور صالحة وتحويلها بعد ذلك. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-%20java.lang.String) فئة وتمرير اسم الملف وكلمة المرور كوسيطات.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل Protected MD إلى ODS عبر Java" %}}
أثناء تحويل ملف MD إلى ODS ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف ODS الناتج. لإضافة علامة مائية ، قم بإنشاء مصنف جديد لفتح ملف XLSX المحول. حدد ورقة العمل عبر الفهرس الخاص بها ، وأنشئ شكلًا واستخدم وظيفة addTextEffect الخاصة به ، وقم بتعيين الألوان والشفافية والمزيد. بعد ذلك يمكنك حفظ مستند XLSX كملف ODS مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



تحويل Markdown (MD) إلى ODS (جدول بيانات OpenDocument) يوفر بديلاً قويًا ومفتوح المصدر لـ Excel. ODS مثالي للفرق التي تستخدم LibreOffice أو OpenOffice ويدعم الصيغ الرياضية والرسوم البيانية وتنسيق الجداول المُنظمة.



{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}



* استيراد قوائم Markdown إلى لوحات تحكم ODS.

* بناء أوراق تحليلية لبيئات المكاتب مفتوحة المصدر.

* إنشاء متتبعات ميزانية بتنسيق ODS مستمدة من محتوى MD.

* تحويل وثائق MD التقنية إلى بيانات جاهزة للجداول الإلكترونية.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات الأتمتة" %}}



* توليد ODS المجدول لفرق البيانات مفتوحة المصدر.

* أنابيب العمل عبر الأنظمة تغذي Markdown إلى جداول بيانات ODS.

* تحويل دفعة من جداول الوثائق إلى تنسيق ODS.

* بناء ODS تلقائي للفرق الموزعة التي تحتاج إلى جداول بيانات قابلة للتحرير.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}