---
title: Java API لتحويل DOC إلى XLS
description: قم بتحويل DOC إلى XLS عبر Java دون استخدام Microsoft Word أو Microsoft Excel
url_ignore: /ar/java/conversion/doc-to-xls/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: XLS
otherformats: XLS SXC DIF XLTX XLSX TSV XLAM XLTM FODS ODS XLT XLSM EXCEL XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل DOC إلى XLS عبر Java" h2="في Premise Java API لتحويل DOC إلى XLS بدون استخدام Microsoft<sup>&reg;</sup> Word أو Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
تحويل DOC إلى XLS عبر [Aspose.Total for Java](https://products.aspose.com/total/java/) هي عملية بسيطة من خطوتين. باستخدام واجهة برمجة تطبيقات معالجة المستندات والتحويل الغنية بالميزات [Aspose.Words for Java](https://products.aspose.com/words/java/) ، يمكنك تصدير DOC إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/java/) ، يمكنك تحويل HTML إلى XLS.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل DOC إلى XLS" %}}
1. افتح ملف DOC باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. تحويل DOC إلى HTML باستخدام [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String.com.aspose.words.SaveOptions)) طريقة
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق XLS باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String%D8%8C%D9%AA20com.aspose.cells.%20SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتشمل [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) و [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
قبل تحويل DOC إلى XLS ، يمكنك إزالة المعلومات غير المستخدمة من مستند DOC عبر [Aspose.Words for Java](https://products.aspose.com/words/java/). قد تحتاج أحيانًا إلى إزالة المعلومات غير المستخدمة أو المكررة لتقليل حجم المستند الناتج ووقت المعالجة. تتيح لك فئة [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) تحديد خيارات لتنظيف المستند. لإزالة الأنماط المكررة أو الأنماط أو القوائم غير المستخدمة من المستند ، يمكنك استخدام طريقة [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()). يمكنك استخدام [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) و [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) لاكتشاف وإزالة الأنماط التي تم تمييزها على أنها "غير مستخدمة".  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بإزالة المعلومات غير المستخدمة من مستند DOC عبر Java" %}}
بعد تحويل DOC إلى XLS ، يمكّنك [Aspose.Cells for Java](https://products.aspose.com/cells/java/) من حفظ مستندك للدفق. إذا كنت بحاجة إلى حفظ الملفات في Stream ، فيجب عليك إنشاء كائن FileOutputStream ثم [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.٪20com.aspose.cells.SaveOptions)) الملف إلى كائن Stream هذا عن طريق استدعاء طريقة الحفظ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) هدف. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-xlsm/" name="DOC ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-xlt/" name="DOC ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-ods/" name="DOC ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-tsv/" name="DOC ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-xls/" name="DOC ل XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-xlsb/" name="DOC ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-fods/" name="DOC ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-dif/" name="DOC ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-xltx/" name="DOC ل XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-xlam/" name="DOC ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-xlsx/" name="DOC ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-xltm/" name="DOC ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-sxc/" name="DOC ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/doc-to-excel/" name="DOC ل EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}