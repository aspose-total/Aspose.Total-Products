---
title: Java API لتقديم XPS إلى TXT
description: قم بتصدير XPS إلى TXT عبر Java API دون استخدام Microsoft Excel أو Adobe Reader
url_ignore: /ar/java/conversion/xps-to-txt/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: TXT
otherformats: XLSB TSV TXT FODS ODS EXCEL DIF MD XLAM XLSM XLT XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير XPS إلى TXT عبر Java" h2="قم بتحويل ملف XPS إلى TXT باستخدام Java API داخل أي تطبيقات Java J2SE و J2EE و J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك دمج ميزة تحويل XPS إلى TXT في تطبيقات Java في عملية من خطوتين. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) يمكنك تحويل XPS إلى XLSX. في الخطوة الثانية ، يمكنك تحويل XLSX إلى TXT باستخدام Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف XPS إلى TXT عبر Java" %}}
1. افتح ملف XPS باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل XPS إلى XLSX باستخدام [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) طريقة
3. قم بتحميل مستند XLSX باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق TXT باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String%D8%8C%D9%AA20com.aspose.cells.%20SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) في ملف pom.xml الخاص بك.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
إذا كان مستند XPS الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى TXT بدون كلمة المرور. باستخدام واجهة برمجة التطبيقات ، يمكنك أولاً فتح المستند المحمي باستخدام كلمة مرور صالحة وتحويلها بعد ذلك. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-%20java.lang.String) فئة وتمرير اسم الملف وكلمة المرور كوسيطات.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل Protected XPS إلى TXT عبر Java" %}}
أثناء تحويل ملف XPS إلى TXT ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف TXT الناتج. لإضافة علامة مائية ، قم بإنشاء مصنف جديد لفتح ملف XLSX المحول. حدد ورقة العمل عبر الفهرس الخاص بها ، وأنشئ شكلًا واستخدم وظيفة addTextEffect الخاصة به ، وقم بتعيين الألوان والشفافية والمزيد. بعد ذلك يمكنك حفظ مستند XLSX كملف TXT مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



تحويل ملف XPS إلى **TXT (نص عادي)** يستخرج محتوى النص الخام لضمان أقصى قدر من التوافقية وسهولة التحرير والاستخدام في النصوص، قواعد البيانات، أو التحليلات.



{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}



* استخراج البيانات النصية لتحليل النصوص أو تحليل المشاعر.

* تحضير المحتوى لمشاريع معالجة اللغة الطبيعية (NLP).

* تحرير سريع أو إعادة استخدام محتوى المستند.

* أرشفة المحتوى النصي في تنسيق قابل للقراءة على نطاق واسع.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات الأتمتة" %}}



* استخراج دفعي آلي لمحتوى XPS إلى TXT للمعالجة.

* دمج مع خطوط أنابيب البيانات لتنقيب النصوص والتحليل.

* إنشاء نسخ نصية عادية بشكل مجدول للتقارير المتكررة.

* سير عمل مبسط لاستخراج النص من أرشيفات XPS الكبيرة.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}