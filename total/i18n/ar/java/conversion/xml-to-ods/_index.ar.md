---
title: Java API لتقديم XML إلى ODS
description: قم بتصدير XML إلى ODS عبر Java API دون استخدام Microsoft Excel أو Adobe Reader
url: /ar/java/conversion/xml-to-ods/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: ODS
otherformats: XLTM XLT XLAM SXC TXT XLSM DIF EXCEL XLTX TSV MD XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير XML إلى ODS عبر Java" h2="قم بتحويل ملف XML إلى ODS باستخدام Java API داخل أي تطبيقات Java J2SE و J2EE و J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java] (https://products.aspose.com/total/java/) يمكنك دمج ميزة تحويل XML إلى ODS في تطبيقات Java في عملية من خطوتين. أولاً ، باستخدام [Aspose.PDF for Java] (https://products.aspose.com/pdf/java/) يمكنك تحويل XML إلى XLSX. في الخطوة الثانية ، يمكنك تحويل XLSX إلى ODS باستخدام Spreadsheet Programming API [Aspose.Cells for Java] (https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف XML إلى ODS عبر Java" %}}
1. افتح ملف XML باستخدام فئة [Document] (https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل XML إلى XLSX باستخدام [حفظ] (https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) طريقة
3. قم بتحميل مستند XLSX باستخدام فئة [Workbook] (https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق ODS باستخدام [حفظ] (https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save (java.lang.String،٪ 20com.aspose.cells. SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven] (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتشمل [Aspose.PDF for Java] (https://docs.aspose.com/pdf/java/installation/) و [Aspose.Cells for Java] (https://docs.aspose.com/cells/java/ التثبيت /) في ملف pom.xml الخاص بك.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
إذا كان مستند XML الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى ODS بدون كلمة المرور. باستخدام واجهة برمجة التطبيقات ، يمكنك أولاً فتح المستند المحمي باستخدام كلمة مرور صالحة وتحويلها بعد ذلك. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من [المستند] (https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- java.lang.String-) فئة وتمرير اسم الملف وكلمة المرور كوسيطات.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل Protected XML إلى ODS عبر Java" %}}
أثناء تحويل ملف XML إلى ODS ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف ODS الناتج. لإضافة علامة مائية ، قم بإنشاء مصنف جديد لفتح ملف XLSX المحول. حدد ورقة العمل عبر الفهرس الخاص بها ، وأنشئ شكلًا واستخدم وظيفة addTextEffect الخاصة به ، وقم بتعيين الألوان والشفافية والمزيد. بعد ذلك يمكنك حفظ مستند XLSX كملف ODS مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-dif/" name="XML ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-xltx/" name="XML ل XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-md/" name="XML ل MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-fods/" name="XML ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-xltm/" name="XML ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-excel/" name="XML ل EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-xlsm/" name="XML ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-xlam/" name="XML ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-xlt/" name="XML ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-xlsb/" name="XML ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-ods/" name="XML ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xml-to-sxc/" name="XML ل SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}