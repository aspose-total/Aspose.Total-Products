---
title: Java ile DOC'u JSON Formatına Dönüştür
description: Microsoft Word veya Microsoft Excel kullanmadan Java aracılığıyla DOC'yi JSON formatına dönüştürün
url: /tr/java/conversion/doc-to-json/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile DOC'u JSON Formatına Dönüştür" h2="Microsoft<sup>&reg;</sup> Word veya Microsoft<sup>&reg;</sup> Excel kullanmadan DOC'yi JSON'a dönüştürmek için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) aracılığıyla DOC'yi JSON formatına dönüştürmek, iki adımlı basit bir işlemdir. Zengin özelliklere sahip, belge işleme ve dönüştürme API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak DOC'yi HTML'ye aktarabilirsiniz. Bundan sonra, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) kullanarak HTML'yi JSON'a dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile DOC'u JSON Formatına Dönüştür" %}}
1. DOC dosyasını [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak açın
2. [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak DOC'yi HTML'ye dönüştürün ) yöntem
3. [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıfını kullanarak HTML belgesini yükleyin
4. Belgeyi [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) yöntemi
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kolayca kullanabilirsiniz. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
API'yi kullanarak parola korumalı belgeyi de açabilirsiniz. Girdiğiniz DOC belgeniz parola korumalıysa, parolayı kullanmadan JSON biçimine dönüştüremezsiniz. API, bir LoadOptions nesnesinde doğru parolayı ileterek şifrelenmiş belgeyi açmanıza olanak tanır. Aşağıdaki kod örneği, şifreli bir belgeyi parola ile açmanın nasıl deneneceğini gösterir:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Korumalı DOC'u JSON Formatına Dönüştür" %}}
DOC'yi JSON'a dönüştürürken, aralığı JSON çıktı biçiminize de ayarlayabilirsiniz. Aralığı ayarlamak için dönüştürülen HTML'yi Workbook sınıfını kullanarak açabilir, Cells.createRange yöntemini kullanarak dışa aktarılacak bir veri aralığı oluşturabilir, Range & ExportRangeToJsonOptions referanslarıyla JsonUtility.exportRangeToJson yöntemini çağırabilir ve dosyaya dize JSON verilerini yazabilirsiniz. BufferedWriter.write yöntemi. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-xlam/" name="DOC İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-xlt/" name="DOC İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-csv/" name="DOC İle CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-xlsx/" name="DOC İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-fods/" name="DOC İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-xltm/" name="DOC İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-xlsm/" name="DOC İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-xltx/" name="DOC İle XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-ods/" name="DOC İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-xlsb/" name="DOC İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-excel/" name="DOC İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-sxc/" name="DOC İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-tsv/" name="DOC İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/doc-to-dif/" name="DOC İle DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}