---
title: RTF'yi ODS'ye Dönüştürmek için Java API
description: Microsoft Word veya Microsoft Excel kullanmadan Java aracılığıyla RTF'yi ODS'ye dönüştürün
url_ignore: /tr/java/conversion/rtf-to-ods/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: ODS
otherformats: XLTM DIF TSV XLSB XLTX XLAM FODS XLSM XLS EXCEL XLSX SXC ODS XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile RTF'yi ODS'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan RTF'yi ODS'ye dönüştürmek için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) aracılığıyla RTF'yi ODS'ye dönüştürmek, iki adımlı basit bir işlemdir. Zengin özelliklere sahip, belge işleme ve dönüştürme API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak RTF'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak HTML'yi ODS'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="RTF'yi ODS'ye Dönüştürmek için C++ API" %}}
1. RTF dosyasını [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak açın
2. [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak RTF'yi HTML'ye dönüştürün ) yöntem
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak HTML belgesini yükleyin
4. [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.Words for Java](https://rtfs.aspose.com/words/java/installation/) ve [Aspose.Cells for Java](https://rtfs.aspose.com/cells/java/installation/) pom.xml dosyanızda.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
RTF'yi ODS'ye dönüştürmeden önce, kullanılmayan bilgileri [Aspose.Words for Java](https://products.aspose.com/words/java/) aracılığıyla RTF Belgesinden kaldırabilirsiniz. Bazen çıktı belgesinin boyutunu ve işlem süresini azaltmak için kullanılmayan veya yinelenen bilgileri kaldırmanız gerekebilir. [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) sınıfı, belge temizleme seçeneklerini belirlemenize olanak tanır. Belgeden yinelenen stilleri veya yalnızca kullanılmayan stilleri veya listeleri kaldırmak için [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()) yöntemini kullanabilirsiniz. [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) ve [UnusedBuiltinStyles](https://reference.aspose.com/words/java) kullanabilirsiniz /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) özellikleri, "kullanılmayan" olarak işaretlenen stilleri algılamak ve kaldırmak için.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-Document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java aracılığıyla bir RTF Belgesinden Kullanılmayan Bilgileri Kaldırma" %}}
RTF'yi ODS'ye dönüştürdükten sonra, [Aspose.Cells for Java](https://products.aspose.com/cells/java/), belgenizi akışa kaydetmenizi sağlar. Dosyaları bir Akışa kaydetmeniz gerekiyorsa, bir FileOutputStream nesnesi oluşturmalı ve ardından [kaydet](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) kaydetme yöntemini çağırarak bu Stream nesnesine dosya nesne. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xlsm/" name="RTF İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xlt/" name="RTF İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-ods/" name="RTF İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-tsv/" name="RTF İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xls/" name="RTF İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xlsb/" name="RTF İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-fods/" name="RTF İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-dif/" name="RTF İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xltx/" name="RTF İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xlam/" name="RTF İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xlsx/" name="RTF İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-xltm/" name="RTF İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-sxc/" name="RTF İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/rtf-to-excel/" name="RTF İle EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}