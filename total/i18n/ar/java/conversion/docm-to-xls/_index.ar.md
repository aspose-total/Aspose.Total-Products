---
title: Java API لتحويل DOCM إلى XLS
description: قم بتحويل DOCM إلى XLS عبر Java دون استخدام Microsoft Word أو Microsoft Excel
url: /ar/java/conversion/docm-to-xls/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: XLS
otherformats: XLTM XLS XLAM ODS EXCEL XLT XLSX FODS XLTX SXC XLSB TSV XLSM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل DOCM إلى XLS عبر Java" h2="في Premise Java API لتحويل DOCM إلى XLS بدون استخدام Microsoft <sup> & reg؛ </sup> Word أو Microsoft <sup> & reg؛ </sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
تحويل DOCM إلى XLS عبر [Aspose.Total for Java] (https://products.aspose.com/total/java/) هي عملية بسيطة من خطوتين. باستخدام واجهة برمجة تطبيقات معالجة المستندات والتحويل الغنية بالميزات [Aspose.Words for Java] (https://products.aspose.com/words/java/) ، يمكنك تصدير DOCM إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for Java] (https://products.aspose.com/cells/java/) ، يمكنك تحويل HTML إلى XLS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C ++ API لتحويل DOCM إلى XLS" %}}
1. افتح ملف DOCM باستخدام فئة [Docmument] (https://apireference.aspose.com/words/java/com.aspose.words/Docmument)
2. تحويل DOCM إلى HTML باستخدام [Save] (https://apireference.aspose.com/words/java/com.aspose.words/Docmument#save (java.lang.String، com.aspose.words.SaveOptions) ) طريقة
3. قم بتحميل مستند HTML باستخدام فئة [Workbook] (https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق XLS باستخدام [Save] (https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save (java.lang.String،٪ 20com.aspose.cells. SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven] (https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتشمل [Aspose.Words for Java] (https://docms.aspose.com/words/java/installation/) و [Aspose.Cells for Java] (https://docms.aspose.com/cells/java/ التثبيت /) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
قبل تحويل DOCM إلى XLS ، يمكنك إزالة المعلومات غير المستخدمة من مستند DOCM عبر [Aspose.Words for Java] (https://products.aspose.com/words/java/). قد تحتاج أحيانًا إلى إزالة المعلومات غير المستخدمة أو المكررة لتقليل حجم المستند الناتج ووقت المعالجة. تتيح لك فئة [CleanupOptions] (https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) تحديد خيارات لتنظيف المستند. لإزالة الأنماط المكررة أو الأنماط أو القوائم غير المستخدمة من المستند ، يمكنك استخدام طريقة [Cleanup] (https://apireference.aspose.com/words/java/com.aspose.words/Docmument#cleanup ()). يمكنك استخدام [UnusedStyles] (https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) و [UnusedBuiltinStyles] (https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) لاكتشاف وإزالة الأنماط التي تم تمييزها على أنها "غير مستخدمة".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}[Save]
{{% blocks/products/pf/feature-page-section  h2="قم بإزالة المعلومات غير المستخدمة من مستند DOCM عبر Java" %}}
بعد تحويل DOCM إلى XLS ، يمكّنك [Aspose.Cells for Java] (https://products.aspose.com/cells/java/) من حفظ مستندك للدفق. إذا كنت بحاجة إلى حفظ الملفات في Stream ، فيجب عليك إنشاء كائن FileOutputStream ثم [حفظ] (https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save (java.io. OutputStream،٪ 20com.aspose.cells.SaveOptions)) الملف إلى كائن Stream هذا عن طريق استدعاء طريقة الحفظ [Workbook] (https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) هدف. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xlsm/" name="DOCM ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xlt/" name="DOCM ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-ods/" name="DOCM ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-tsv/" name="DOCM ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xls/" name="DOCM ل XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xlsb/" name="DOCM ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-fods/" name="DOCM ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-dif/" name="DOCM ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xltx/" name="DOCM ل XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xlam/" name="DOCM ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xlsx/" name="DOCM ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xltm/" name="DOCM ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-sxc/" name="DOCM ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-excel/" name="DOCM ل EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}