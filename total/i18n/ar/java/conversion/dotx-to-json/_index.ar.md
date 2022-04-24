---
title: تحويل DOTX إلى تنسيق JSON عبر Java
description: قم بتحويل تنسيق DOTX إلى تنسيق JSON عبر Java دون استخدام Microsoft Word أو Microsoft Excel
url: /ar/java/conversion/dotx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل DOTX إلى تنسيق JSON عبر Java" h2="في Premise Java API لتحويل DOTX إلى JSON بدون استخدام Microsoft <sup> & reg؛ </sup> Word أو Microsoft <sup> & reg؛ </sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
تحويل DOTX إلى تنسيق JSON عبر [Aspose.Total for Java] (https://products.aspose.com/total/java/) هي عملية بسيطة من خطوتين. باستخدام واجهة برمجة تطبيقات معالجة المستندات والتحويل الغنية بالميزات [Aspose.Words for Java] (https://products.aspose.com/words/java/) ، يمكنك تصدير DOTX إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for Java] (https://products.aspose.com/cells/java/) ، يمكنك تحويل HTML إلى JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل DOTX إلى تنسيق JSON عبر Java" %}}
1. افتح ملف DOTX باستخدام فئة [Dotxument] (https://apireference.aspose.com/words/java/com.aspose.words/Dotxument)
2. تحويل DOTX إلى HTML باستخدام [حفظ] (https://apireference.aspose.com/words/java/com.aspose.words/Dotxument#save (java.lang.String، com.aspose.words.SaveOptions) ) طريقة
3. قم بتحميل مستند HTML باستخدام فئة [Workbook] (https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق JSON باستخدام [حفظ] (https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save (java.lang.String،٪ 20com.aspose.cells. SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven] (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
باستخدام API ، يمكنك أيضًا فتح المستند المحمي بكلمة مرور. إذا كان مستند DOTX الذي تم إدخاله محميًا بكلمة مرور ، فلا يمكنك تحويله إلى تنسيق JSON دون استخدام كلمة المرور. تسمح لك واجهة برمجة التطبيقات بفتح المستند المشفر عن طريق تمرير كلمة المرور الصحيحة في كائن LoadOptions. يوضح المثال التالي من التعليمات البرمجية كيفية محاولة فتح مستند مشفر بكلمة مرور:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل DOTX المحمي إلى تنسيق JSON عبر Java" %}}
أثناء قيامك بتحويل DOTX إلى JSON ، يمكنك أيضًا ضبط النطاق على تنسيق JSON الناتج. لتعيين النطاق ، يمكنك فتح HTML المحول باستخدام فئة Workbook ، وإنشاء نطاق من البيانات ليتم تصديرها باستخدام طريقة Cells.createRange ، واستدعاء طريقة JsonUtility.exportRangeToJson مع مراجع Range & ExportRangeToJsonOptions وكتابة سلسلة بيانات JSON إلى ملف عبر طريقة BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-xlam/" name="DOTX ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-xlt/" name="DOTX ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-csv/" name="DOTX ل CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-xlsx/" name="DOTX ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-fods/" name="DOTX ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-xltm/" name="DOTX ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-xlsm/" name="DOTX ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-xltx/" name="DOTX ل XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-ods/" name="DOTX ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-xlsb/" name="DOTX ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-excel/" name="DOTX ل EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-sxc/" name="DOTX ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-tsv/" name="DOTX ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dotx-to-dif/" name="DOTX ل DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}