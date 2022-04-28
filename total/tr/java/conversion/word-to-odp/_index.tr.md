---
title: Java ile WORD'yi ODP'ye dönüştürün
description: Microsoft Word veya PowerPoint kullanmadan WORD'yi ODP'ye Dışa Aktarmak için Java API
url: /tr/java/conversion/word-to-odp/
family: total
platformtag: net
feature: conversion
informat: WORDX
outformat: ODP
otherformats: POTX PPTM POT POWERPOINT PPTX PPT PPSX PPS POTM PPSM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile WORD'yi ODP'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> PowerPoint veya Word kullanmadan herhangi bir Java J2SE, J2EE, J2ME uygulamasında şirket içi Java API kullanarak WORD'den ODP'ye dönüştürme" >}}
{{% blocks/products/pf/feature-page-summary %}}
Çoğu zaman geliştiricilerin WORD dosyasını programlı olarak ODP'ye dönüştürmesi gerekir. Dosya Otomasyonu Java kitaplıklarını [Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak, oluşturma işlemini birkaç basit adımda otomatikleştirebilirsiniz. WORD dosyanızı [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak yükleyebilir ve HTML'ye dönüştürebilirsiniz. Bundan sonra, güçlü PowerPoint manipülasyonu Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanarak yeni bir Sunum oluşturabilir, içine HTML içeriği yazabilir ve ODP olarak kaydedebilirsiniz. .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile WORD'yi ODP'ye Dönüştürme" %}}
1. WORD dosyasını [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak açın
2. [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak WORD dosyasını HTML'ye dönüştürün )) yöntem
3. Yeni bir [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) nesnesini başlatın
5. BufferedReader kullanarak HTML dosyasından içerik çıkarın ve içeriği sunum dosyanıza yazın
6. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) yöntemini kullanarak belgeyi ODP'ye kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
WORD'den ODP'ye dosya dönüştürme için Aspose.Total for Java'yı doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose) üzerinden kolayca kullanabilirsiniz. /aspose-total) tabanlı bir projedir ve pom.xml dosyanıza kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-word-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}Document
API ayrıca parola korumalı WORD belgelerini ODP'ye dönüştürmenize olanak tanır. Girdiğiniz WORD belgeniz parola korumalıysa, parolayı kullanmadan ODP biçimine dönüştüremezsiniz. Şifrelenmiş bir belgeyi açmak için LoadOptions nesnesinde doğru parolayı ayarlayabilir ve bunu Wordument yapıcısına iletebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-word-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-ppsm/" name="WORD İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-pot/" name="WORD İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-powerpoint/" name="WORD İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-pptx/" name="WORD İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-potx/" name="WORD İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-pptm/" name="WORD İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-potm/" name="WORD İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-pps/" name="WORD İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-ppsx/" name="WORD İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-ppt/" name="WORD İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-csv/" name="WORD İle CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-dif/" name="WORD İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-fods/" name="WORD İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-ods/" name="WORD İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-sxc/" name="WORD İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-tsv/" name="WORD İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-xlam/" name="WORD İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-xltm/" name="WORD İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-excel/" name="WORD İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-xls/" name="WORD İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-xlsb/" name="WORD İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-xlsm/" name="WORD İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-xlsx/" name="WORD İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-xlt/" name="WORD İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-xltm/" name="WORD İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/word-to-xltx/" name="WORD İle XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}