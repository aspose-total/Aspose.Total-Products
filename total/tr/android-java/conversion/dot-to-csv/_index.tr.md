---
title: DOT'yi CSV'ye Dönüştürmek için Android API
description: Microsoft Word veya Microsoft Excel kullanmadan Java aracılığıyla Android'de DOT'yi CSV'ye dönüştürün

family: total
platformtag: cpp
feature: conversion
informat: DOT
outformat: CSV
otherformats: XLTX XLSX SXC TSV DIF EXCEL ODS XLSB FODS XLS XLTM XLAM XLSM XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android Uygulamalarında DOT'yi CSV'ye Dönüştür" h2="DOT'yi, Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan Java aracılığıyla Android'de CSV'ye aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
Java üzerinden [Aspose.Total for Android](https://products.aspose.com/total/android-java/) kullanarak, android uygulamalarınızda DOT'den CSV'ye dönüştürme özelliğini entegre edebilirsiniz. İlk olarak, zengin özelliklere sahip belge işleme ve dönüştürme API'sini [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) kullanarak DOT'u HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/) kullanarak HTML'yi CSV'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOT'yi CSV'ye Dönüştürmek için Android API" %}}
1. DOT dosyasını [Dotument](https://reference.aspose.com/words/java/com.aspose.words/Dotument) sınıfını kullanarak açın
2. [Kaydet](https://reference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak DOT'yi HTML'ye dönüştürün. ) yöntem
3. [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak HTML belgesini yükleyin
4. Belgeyi [Kaydet](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve Java aracılığıyla [Aspose.Cells for Android](https://dots.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-) yükleyin Java-from-maven-repository) ve [Java üzerinden Android için Aspose.Words](https://dots.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) uygulamalarınızda.

Alternatif olarak, [downloads](https://releases.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Java aracılığıyla Android'de bir DOT Belgesinden Kullanılmayan Bilgileri Kaldırma" %}}
DOT'yi CSV'ye dönüştürmeden önce, kullanılmayan bilgileri [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) aracılığıyla DOT Belgesinden kaldırabilirsiniz. Bazen çıktı belgesinin boyutunu ve işlem süresini azaltmak için kullanılmayan veya yinelenen bilgileri kaldırmanız gerekebilir. [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) sınıfı, belge temizleme seçeneklerini belirlemenize olanak tanır. Belgeden yinelenen stilleri veya yalnızca kullanılmayan stilleri veya listeleri kaldırmak için [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Dotument#cleanup()) yöntemini kullanabilirsiniz. [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) ve [UnusedBuiltinStyles](https://reference.aspose.com/words/java) kullanabilirsiniz /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) "kullanılmayan" olarak işaretlenen stilleri algılamak ve kaldırmak için özellikler.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java aracılığıyla Android'de Akış için CSV Dosyasını Kaydet" %}}
DOT'yi CSV'ye dönüştürdükten sonra, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), belgenizi akışa kaydetmenizi sağlar. Dosyaları bir Akışa kaydetmeniz gerekiyorsa, bir FileOutputStream nesnesi oluşturmalı ve ardından [kaydet](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) [Çalışma Kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) kaydetme yöntemini çağırarak bu Stream nesnesine dosya nesne.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-xltx/" name="DOT İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-xlsx/" name="DOT İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-sxc/" name="DOT İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-tsv/" name="DOT İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-dif/" name="DOT İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-excel/" name="DOT İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-ods/" name="DOT İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-xlsb/" name="DOT İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-fods/" name="DOT İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-xls/" name="DOT İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-xltm/" name="DOT İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-xlam/" name="DOT İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-xlsm/" name="DOT İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/dot-to-xlt/" name="DOT İle XLT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}