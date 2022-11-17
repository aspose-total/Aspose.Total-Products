---
title: Android API لتحويل DOC إلى CSV
description: قم بتحويل DOC إلى CSV في Android عبر Java دون استخدام Microsoft Word أو Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: CSV
otherformats: FODS XLAM DIF XLS XLSM TSV XLT XLTX EXCEL XLTM ODS SXC XLSX XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل DOC إلى CSV في تطبيقات Android" h2="تصدير DOC إلى CSV في Android عبر Java بدون استخدام Microsoft <sup>&reg;</sup> Word أو Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Android عبر Java](https://products.aspose.com/total/android-java/) يمكنك دمج ميزة تحويل DOC إلى CSV داخل تطبيقات Android. أولاً ، يمكنك تحويل DOC إلى HTML باستخدام واجهة برمجة تطبيقات غنية بالميزات ومعالجة المستندات والتحويل [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). بعد ذلك ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/) ، يمكنك تحويل HTML إلى CSV. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API لتحويل DOC إلى CSV" %}}
1. افتح ملف DOC باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. تحويل DOC إلى HTML باستخدام [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) طريقة
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق CSV باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions))) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) و [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بإزالة المعلومات غير المستخدمة من مستند DOC في Android عبر Java" %}}
قبل تحويل DOC إلى CSV ، يمكنك إزالة المعلومات غير المستخدمة من مستند DOC عبر [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). قد تحتاج أحيانًا إلى إزالة المعلومات غير المستخدمة أو المكررة لتقليل حجم المستند الناتج ووقت المعالجة. تتيح لك فئة [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) تحديد خيارات لتنظيف المستند. لإزالة الأنماط المكررة أو الأنماط أو القوائم غير المستخدمة من المستند ، يمكنك استخدام طريقة [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup ()). يمكنك استخدام [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) و [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) لاكتشاف وإزالة الأنماط التي تم وضع علامة عليها على أنها "غير مستخدمة".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="احفظ ملف CSV للتدفق في Android عبر Java" %}}
بعد تحويل DOC إلى CSV ، يمكّنك [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) من حفظ مستندك للدفق. إذا كنت بحاجة إلى حفظ الملفات في Stream ، فيجب عليك إنشاء كائن FileOutputStream ثم [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream،٪20com.aspose.cells.SaveOptions)) الملف إلى كائن Stream هذا عن طريق استدعاء طريقة الحفظ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) هدف.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-fods/" name="DOC إلى FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-xlam/" name="DOC إلى XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-dif/" name="DOC إلى DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-xls/" name="DOC إلى XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-xlsm/" name="DOC إلى XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-tsv/" name="DOC إلى TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-xlt/" name="DOC إلى XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-xltx/" name="DOC إلى XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-excel/" name="DOC إلى EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-xltm/" name="DOC إلى XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-ods/" name="DOC إلى ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-sxc/" name="DOC إلى SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-xlsx/" name="DOC إلى XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/doc-to-xlsb/" name="DOC إلى XLSB" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}