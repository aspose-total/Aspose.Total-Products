---
title: MOBI'yi XLT'ye Dönüştürmek için Android API
description: Microsoft Word veya Microsoft Excel kullanmadan Java aracılığıyla Android'de MOBI'yi XLT'ye dönüştürün

family: total
platformtag: cpp
feature: conversion
informat: MOBI
outformat: XLT
otherformats: TSV XLSB CSV XLSM XLS ODS DIF XLTX SXC XLAM XLSX FODS EXCEL XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android Uygulamalarında MOBI'yi XLT'ye Dönüştür" h2="MOBI'yi, Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan Java aracılığıyla Android'de XLT'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
Java üzerinden [Aspose.Total for Android](https://products.aspose.com/total/android-java/) kullanarak, android uygulamalarınızda MOBI'den XLT'ye dönüştürme özelliğini entegre edebilirsiniz. İlk olarak, zengin özelliklere sahip belge işleme ve dönüştürme API'sini [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) kullanarak MOBI'u HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/) kullanarak HTML'yi XLT'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MOBI'yi XLT'ye Dönüştürmek için Android API" %}}
1. MOBI dosyasını [Mobiument](https://reference.aspose.com/words/java/com.aspose.words/Mobiument) sınıfını kullanarak açın
2. [Kaydet](https://reference.aspose.com/words/java/com.aspose.words/Mobiument#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak MOBI'yi HTML'ye dönüştürün. ) yöntem
3. [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak HTML belgesini yükleyin
4. Belgeyi [Kaydet](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://releases.aspose.com/total/java/) üzerinden kolayca kullanabilirsiniz ve Java aracılığıyla [Aspose.Cells for Android](https://mobis.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-) yükleyin Java-from-maven-repository) ve [Java üzerinden Android için Aspose.Words](https://mobis.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) uygulamalarınızda.

Alternatif olarak, [downloads](https://releases.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java aracılığıyla Android'de bir MOBI Belgesinden Kullanılmayan Bilgileri Kaldırma" %}}
MOBI'yi XLT'ye dönüştürmeden önce, kullanılmayan bilgileri [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) aracılığıyla MOBI Belgesinden kaldırabilirsiniz. Bazen çıktı belgesinin boyutunu ve işlem süresini azaltmak için kullanılmayan veya yinelenen bilgileri kaldırmanız gerekebilir. [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) sınıfı, belge temizleme seçeneklerini belirlemenize olanak tanır. Belgeden yinelenen stilleri veya yalnızca kullanılmayan stilleri veya listeleri kaldırmak için [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Mobiument#cleanup()) yöntemini kullanabilirsiniz. [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) ve [UnusedBuiltinStyles](https://reference.aspose.com/words/java) kullanabilirsiniz /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) "kullanılmayan" olarak işaretlenen stilleri algılamak ve kaldırmak için özellikler.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-mobiument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java aracılığıyla Android'de Akış için XLT Dosyasını Kaydet" %}}
MOBI'yi XLT'ye dönüştürdükten sonra, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), belgenizi akışa kaydetmenizi sağlar. Dosyaları bir Akışa kaydetmeniz gerekiyorsa, bir FileOutputStream nesnesi oluşturmalı ve ardından [kaydet](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) kaydetme yöntemini çağırarak bu Stream nesnesine dosya nesne.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-tsv/" name="MOBI İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-xlsb/" name="MOBI İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-xlt/" name="MOBI İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-xlsm/" name="MOBI İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-xls/" name="MOBI İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-ods/" name="MOBI İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-dif/" name="MOBI İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-xltx/" name="MOBI İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-sxc/" name="MOBI İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-xlam/" name="MOBI İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-xlsx/" name="MOBI İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-fods/" name="MOBI İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-excel/" name="MOBI İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/mobi-to-xltm/" name="MOBI İle XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}