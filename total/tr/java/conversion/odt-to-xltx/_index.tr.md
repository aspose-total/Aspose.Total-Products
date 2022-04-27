---
title: ODT'yi XLTX'ye Dönüştürmek için Java API
description: Microsoft Word veya Microsoft Excel kullanmadan Java aracılığıyla ODT'yi XLTX'ye dönüştürün
url: /tr/java/conversion/odt-to-xltx/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: XLTX
otherformats: XLTX TSV XLT XLS EXCEL XLSB FODS SXC XLSM DIF XLSX ODS XLAM XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile ODT'yi XLTX'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan ODT'yi XLTX'ye dönüştürmek için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) aracılığıyla ODT'yi XLTX'ye dönüştürmek, iki adımlı basit bir işlemdir. Zengin özelliklere sahip, belge işleme ve dönüştürme API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak ODT'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak HTML'yi XLTX'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ODT'yi XLTX'ye Dönüştürmek için C++ API" %}}
1. ODT dosyasını [Odtument](https://apireference.aspose.com/words/java/com.aspose.words/Odtument) sınıfını kullanarak açın
2. [Save](https://apireference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak ODT'yi HTML'ye dönüştürün ) yöntem
3. [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak HTML belgesini yükleyin
4. [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.Words for Java](https://odts.aspose.com/words/java/installation/) ve [Aspose.Cells for Java](https://odts.aspose.com/cells/java/) içerir kurulum/) pom.xml dosyanızda.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
ODT'yi XLTX'ye dönüştürmeden önce, kullanılmayan bilgileri [Aspose.Words for Java](https://products.aspose.com/words/java/) aracılığıyla ODT Belgesinden kaldırabilirsiniz. Bazen çıktı belgesinin boyutunu ve işlem süresini azaltmak için kullanılmayan veya yinelenen bilgileri kaldırmanız gerekebilir. [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) sınıfı, belge temizleme seçeneklerini belirlemenize olanak tanır. Belgeden yinelenen stilleri veya yalnızca kullanılmayan stilleri veya listeleri kaldırmak için [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Odtument#cleanup()) yöntemini kullanabilirsiniz. [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) ve [UnusedBuiltinStyles](https://apireference.aspose.com/words/java) kullanabilirsiniz /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) özellikleri, "kullanılmayan" olarak işaretlenen stilleri algılamak ve kaldırmak için.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-odtument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java aracılığıyla bir ODT Belgesinden Kullanılmayan Bilgileri Kaldırma" %}}
ODT'yi XLTX'ye dönüştürdükten sonra, [Aspose.Cells for Java](https://products.aspose.com/cells/java/), belgenizi akışa kaydetmenizi sağlar. Dosyaları bir Akışa kaydetmeniz gerekiyorsa, bir FileOutputStream nesnesi oluşturmalı ve ardından [kaydet](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) kaydetme yöntemini çağırarak bu Stream nesnesine dosya nesne. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xlsm/" name="ODT İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xlt/" name="ODT İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-ods/" name="ODT İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-tsv/" name="ODT İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xls/" name="ODT İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xlsb/" name="ODT İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-fods/" name="ODT İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-dif/" name="ODT İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xltx/" name="ODT İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xlam/" name="ODT İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xlsx/" name="ODT İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xltm/" name="ODT İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-sxc/" name="ODT İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-excel/" name="ODT İle EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}