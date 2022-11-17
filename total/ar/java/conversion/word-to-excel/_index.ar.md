---
title: Java API لتحويل WORD إلى EXCEL
description: قم بتحويل WORD إلى EXCEL عبر Java دون استخدام Microsoft Word أو Microsoft Excel
url_ignore: /ar/java/conversion/word-to-excel/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: XLSX
otherformats: SXC EXCEL ODS XLSX EXCEL XLAM XLT XLSM XLTX TSV XLTM FODS XLSB XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل WORD إلى EXCEL عبر Java" h2="في Premise Java API لتحويل WORD إلى EXCEL بدون استخدام Microsoft<sup>&reg;</sup> Word أو Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
تحويل WORD إلى EXCEL عبر [Aspose.Total for Java](https://products.aspose.com/total/java/) هي عملية بسيطة من خطوتين. باستخدام واجهة برمجة تطبيقات معالجة المستندات والتحويل الغنية بالميزات [Aspose.Words for Java](https://products.aspose.com/words/java/) ، يمكنك تصدير WORD إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/java/) ، يمكنك تحويل HTML إلى EXCEL.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل WORD إلى EXCEL" %}}
1. افتح ملف WORD باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. تحويل WORD إلى HTML باستخدام [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String.com.aspose.words.SaveOptions)) طريقة
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق EXCEL باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String%D8%8C%D9%AA20com.aspose.cells.%20SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتشمل [Aspose.Words for Java](https://words.aspose.com/words/java/installation/) و [Aspose.Cells for Java](https://words.aspose.com/cells/java/ التثبيت /) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
قبل تحويل WORD إلى EXCEL ، يمكنك إزالة المعلومات غير المستخدمة من مستند WORD عبر [Aspose.Words for Java](https://products.aspose.com/words/java/). قد تحتاج أحيانًا إلى إزالة المعلومات غير المستخدمة أو المكررة لتقليل حجم المستند الناتج ووقت المعالجة. تتيح لك فئة [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) تحديد خيارات لتنظيف المستند. لإزالة الأنماط المكررة أو الأنماط أو القوائم غير المستخدمة من المستند ، يمكنك استخدام طريقة [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()). يمكنك استخدام [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) و [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) لاكتشاف وإزالة الأنماط التي تم تمييزها على أنها "غير مستخدمة".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بإزالة المعلومات غير المستخدمة من مستند WORD عبر Java" %}}
بعد تحويل WORD إلى EXCEL ، يمكّنك [Aspose.Cells for Java](https://products.aspose.com/cells/java/) من حفظ مستندك للدفق. إذا كنت بحاجة إلى حفظ الملفات في Stream ، فيجب عليك إنشاء كائن FileOutputStream ثم [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.٪20com.aspose.cells.SaveOptions)) الملف إلى كائن Stream هذا عن طريق استدعاء طريقة الحفظ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) هدف. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xlsm/" name="WORD ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xlt/" name="WORD ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-ods/" name="WORD ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-tsv/" name="WORD ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xls/" name="WORD ل XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xlsb/" name="WORD ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-fods/" name="WORD ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-dif/" name="WORD ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xltx/" name="WORD ل XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xlam/" name="WORD ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xlsx/" name="WORD ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xltm/" name="WORD ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-sxc/" name="WORD ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-excel/" name="WORD ل EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}