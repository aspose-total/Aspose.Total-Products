---
title: Java API لتحويل RTF إلى XLS
description: قم بتحويل RTF إلى XLS عبر Java دون استخدام Microsoft Word أو Microsoft Excel
url: /ar/java/conversion/rtf-to-xls/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: XLS
otherformats: TSV XLSM DIF XLTM SXC XLT XLS EXCEL FODS XLSB XLTX XLAM ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل RTF إلى XLS عبر Java" h2="في Premise Java API لتحويل RTF إلى XLS بدون استخدام Microsoft<sup>&reg;</sup> Word أو Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
تحويل RTF إلى XLS عبر [Aspose.Total for Java](https://products.aspose.com/total/java/) هي عملية بسيطة من خطوتين. باستخدام واجهة برمجة تطبيقات معالجة المستندات والتحويل الغنية بالميزات [Aspose.Words for Java](https://products.aspose.com/words/java/) ، يمكنك تصدير RTF إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/java/) ، يمكنك تحويل HTML إلى XLS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C ++ API لتحويل RTF إلى XLS" %}}
1. افتح ملف RTF باستخدام فئة [Rtfument](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument)
2. تحويل RTF إلى HTML باستخدام [Save](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String.com.aspose.words.SaveOptions)) طريقة
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق XLS باستخدام [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String%D8%8C%D9%AA20com.aspose.cells.%20SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتشمل [Aspose.Words for Java](https://rtfs.aspose.com/words/java/installation/) و [Aspose.Cells for Java](https://rtfs.aspose.com/cells/java/ التثبيت /) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
قبل تحويل RTF إلى XLS ، يمكنك إزالة المعلومات غير المستخدمة من مستند RTF عبر [Aspose.Words for Java](https://products.aspose.com/words/java/). قد تحتاج أحيانًا إلى إزالة المعلومات غير المستخدمة أو المكررة لتقليل حجم المستند الناتج ووقت المعالجة. تتيح لك فئة [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) تحديد خيارات لتنظيف المستند. لإزالة الأنماط المكررة أو الأنماط أو القوائم غير المستخدمة من المستند ، يمكنك استخدام طريقة [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Rtfument#cleanup()). يمكنك استخدام [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) و [UnusedBuiltinStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) لاكتشاف وإزالة الأنماط التي تم تمييزها على أنها "غير مستخدمة".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-rtfument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بإزالة المعلومات غير المستخدمة من مستند RTF عبر Java" %}}
بعد تحويل RTF إلى XLS ، يمكّنك [Aspose.Cells for Java](https://products.aspose.com/cells/java/) من حفظ مستندك للدفق. إذا كنت بحاجة إلى حفظ الملفات في Stream ، فيجب عليك إنشاء كائن FileOutputStream ثم [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.٪20com.aspose.cells.SaveOptions)) الملف إلى كائن Stream هذا عن طريق استدعاء طريقة الحفظ [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) هدف. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xlsm/" name="RTF ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xlt/" name="RTF ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-ods/" name="RTF ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-tsv/" name="RTF ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xls/" name="RTF ل XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xlsb/" name="RTF ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-fods/" name="RTF ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-dif/" name="RTF ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xltx/" name="RTF ل XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xlam/" name="RTF ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xlsx/" name="RTF ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xltm/" name="RTF ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-sxc/" name="RTF ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-excel/" name="RTF ل EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}