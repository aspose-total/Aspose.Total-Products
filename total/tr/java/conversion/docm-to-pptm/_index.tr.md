---
title: Java ile DOCM'yi PPTM'ye dönüştürün
description: Microsoft Word veya PowerPoint kullanmadan DOCM'yi PPTM'ye Dışa Aktarmak için Java API
url: /tr/java/conversion/docm-to-pptm/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: PPTM
otherformats: PPSM PPT PPTX PPSX POTX POTM POWERPOINT POT PPS PPTM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile DOCM'yi PPTM'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> PowerPoint veya Word kullanmadan herhangi bir Java J2SE, J2EE, J2ME uygulamasında şirket içi Java API kullanarak DOCM'den PPTM'ye dönüştürme" >}}
{{% blocks/products/pf/feature-page-summary %}}
Çoğu zaman geliştiricilerin DOCM dosyasını programlı olarak PPTM'ye dönüştürmesi gerekir. Dosya Otomasyonu Java kitaplıklarını [Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak, oluşturma işlemini birkaç basit adımda otomatikleştirebilirsiniz. DOCM dosyanızı [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak yükleyebilir ve HTML'ye dönüştürebilirsiniz. Bundan sonra, güçlü PowerPoint manipülasyonu Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanarak yeni bir Sunum oluşturabilir, içine HTML içeriği yazabilir ve PPTM olarak kaydedebilirsiniz. .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile DOCM'yi PPTM'ye Dönüştürme" %}}
1. DOCM dosyasını [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak açın
2. [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak DOCM dosyasını HTML'ye dönüştürün )) yöntem
3. Yeni bir [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) nesnesini başlatın
5. BufferedReader kullanarak HTML dosyasından içerik çıkarın ve içeriği sunum dosyanıza yazın
6. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) yöntemini kullanarak belgeyi PPTM'ye kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
DOCM'den PPTM'ye dosya dönüştürme için Aspose.Total for Java'yı doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose) üzerinden kolayca kullanabilirsiniz. /aspose-total) tabanlı bir projedir ve pom.xml dosyanıza kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docm-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}Document
API ayrıca parola korumalı DOCM belgelerini PPTM'ye dönüştürmenize olanak tanır. Girdiğiniz DOCM belgeniz parola korumalıysa, parolayı kullanmadan PPTM biçimine dönüştüremezsiniz. Şifrelenmiş bir belgeyi açmak için LoadOptions nesnesinde doğru parolayı ayarlayabilir ve bunu Docmument yapıcısına iletebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docm-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-ppsm/" name="DOCM İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-pot/" name="DOCM İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-powerpoint/" name="DOCM İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-pptx/" name="DOCM İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-potx/" name="DOCM İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-pptm/" name="DOCM İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-potm/" name="DOCM İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-pps/" name="DOCM İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-ppsx/" name="DOCM İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-ppt/" name="DOCM İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-csv/" name="DOCM İle CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-dif/" name="DOCM İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-fods/" name="DOCM İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-ods/" name="DOCM İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-sxc/" name="DOCM İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-tsv/" name="DOCM İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-xlam/" name="DOCM İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-xltm/" name="DOCM İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-excel/" name="DOCM İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-xls/" name="DOCM İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-xlsb/" name="DOCM İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-xlsm/" name="DOCM İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-xlsx/" name="DOCM İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-xlt/" name="DOCM İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-xltm/" name="DOCM İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docm-to-xltx/" name="DOCM İle XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}