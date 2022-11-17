---
title: Java API لتحويل RTF إلى TSV
description: قم بتحويل RTF إلى TSV عبر Java دون استخدام Microsoft Word أو Microsoft Excel
url_ignore: /ar/java/conversion/rtf-to-tsv/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: TSV
otherformats: SXC FODS XLSB XLSM ODS XLT XLS XLSX XLTX XLTM XLAM EXCEL TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل RTF إلى TSV عبر Java" h2="في Premise Java API لتحويل RTF إلى TSV بدون استخدام Microsoft<sup>&reg;</sup> Word أو Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
تحويل RTF إلى TSV عبر [Aspose.Total for Java](https://products.aspose.com/total/java/) هي عملية بسيطة من خطوتين. باستخدام واجهة برمجة تطبيقات معالجة المستندات والتحويل الغنية بالميزات [Aspose.Words for Java](https://products.aspose.com/words/java/) ، يمكنك تصدير RTF إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/java/) ، يمكنك تحويل HTML إلى TSV.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل RTF إلى TSV" %}}
1. افتح ملف RTF باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. تحويل RTF إلى HTML باستخدام [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String.com.aspose.words.SaveOptions)) طريقة
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق TSV باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String%D8%8C%D9%AA20com.aspose.cells.%20SaveOptions)) الطريقة
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
قبل تحويل RTF إلى TSV ، يمكنك إزالة المعلومات غير المستخدمة من مستند RTF عبر [Aspose.Words for Java](https://products.aspose.com/words/java/). قد تحتاج أحيانًا إلى إزالة المعلومات غير المستخدمة أو المكررة لتقليل حجم المستند الناتج ووقت المعالجة. تتيح لك فئة [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) تحديد خيارات لتنظيف المستند. لإزالة الأنماط المكررة أو الأنماط أو القوائم غير المستخدمة من المستند ، يمكنك استخدام طريقة [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()). يمكنك استخدام [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) و [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) لاكتشاف وإزالة الأنماط التي تم تمييزها على أنها "غير مستخدمة".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-Document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بإزالة المعلومات غير المستخدمة من مستند RTF عبر Java" %}}
بعد تحويل RTF إلى TSV ، يمكّنك [Aspose.Cells for Java](https://products.aspose.com/cells/java/) من حفظ مستندك للدفق. إذا كنت بحاجة إلى حفظ الملفات في Stream ، فيجب عليك إنشاء كائن FileOutputStream ثم [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.٪20com.aspose.cells.SaveOptions)) الملف إلى كائن Stream هذا عن طريق استدعاء طريقة الحفظ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) هدف. 
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