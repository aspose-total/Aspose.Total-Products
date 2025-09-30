---
title: Java API لتقديم PDF إلى MD
description: قم بتصدير PDF إلى MD عبر Java API دون استخدام Microsoft Excel أو Adobe Reader
url_ignore: /ar/java/conversion/pdf-to-md/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: MD
otherformats: FODS XLTX XLSB XLSM MD SXC EXCEL DIF XLAM TSV ODS TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير PDF إلى MD عبر Java" h2="قم بتحويل ملف PDF إلى MD باستخدام Java API داخل أي تطبيقات Java J2SE و J2EE و J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك دمج ميزة تحويل PDF إلى MD في تطبيقات Java في عملية من خطوتين. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) يمكنك تحويل PDF إلى XLSX. في الخطوة الثانية ، يمكنك تحويل XLSX إلى MD باستخدام Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف PDF إلى MD عبر Java" %}}
1. افتح ملف PDF باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل PDF إلى XLSX باستخدام [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) طريقة
3. قم بتحميل مستند XLSX باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق MD باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String%D8%8C%D9%AA20com.aspose.cells.%20SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) في ملف pom.xml الخاص بك.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
إذا كان مستند PDF الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى MD بدون كلمة المرور. باستخدام واجهة برمجة التطبيقات ، يمكنك أولاً فتح المستند المحمي باستخدام كلمة مرور صالحة وتحويلها بعد ذلك. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-%20java.lang.String) فئة وتمرير اسم الملف وكلمة المرور كوسيطات.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل Protected PDF إلى MD عبر Java" %}}
أثناء تحويل ملف PDF إلى MD ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف MD الناتج. لإضافة علامة مائية ، قم بإنشاء مصنف جديد لفتح ملف XLSX المحول. حدد ورقة العمل عبر الفهرس الخاص بها ، وأنشئ شكلًا واستخدم وظيفة addTextEffect الخاصة به ، وقم بتعيين الألوان والشفافية والمزيد. بعد ذلك يمكنك حفظ مستند XLSX كملف MD مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
حالة تحويل **PDF إلى MD** تركز على تحويل ملفات PDF إلى تنسيق **Markdown (.md)**، الذي يستخدم على نطاق واسع في **توثيق المطورين، المدونات التقنية، وأنابيب التشغيل التلقائي للمحتوى**. يتيح إعادة استخدام النصوص المنظمة في ملفات PDF، والجداول، ومقاطع الشفرة في محررات Markdown.
{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}
- ترحيل توثيق المطورين من PDF إلى MD
- تحويل الدلائل الفنية من PDF إلى Markdown للتحرير
- سير العمل في المدونات التقنية باستخدام محتوى MD
- تخزين توثيق المشاريع مفتوحة المصدر على شكل Markdown
- إنشاء قواعد معرفية من التقارير بتنسيق PDF المنظمة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات التشغيل التلقائي" %}}
- أنابيب **تحويل PDF إلى MD تلقائية للمطورين**
- تحويل دفعي لملفات PDF إلى مستودعات Markdown
- سير العمل المعتمد على Git يدمج تصدير PDF إلى MD
- معالجة تحويل PDF إلى MD مدفوعة بواسطة واجهة برمجة التطبيقات لمنصات إدارة نظم إدارة المحتوى
- تشغيل الأتمتة لترحيل مستندات PDF إلى MD
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}