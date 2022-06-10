---
title: Java ile ODT'yi POTM'ye dönüştürün
description: Microsoft Word veya PowerPoint kullanmadan ODT'yi POTM'ye Dışa Aktarmak için Java API
url_ignore: /tr/java/conversion/odt-to-potm/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: POTM
otherformats: PPTX POTM POWERPOINT PPT PPTM POTX PPS PPSX POT PPSM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile ODT'yi POTM'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> PowerPoint veya Word kullanmadan herhangi bir Java J2SE, J2EE, J2ME uygulamasında şirket içi Java API kullanarak ODT'den POTM'ye dönüştürme" >}}
{{% blocks/products/pf/feature-page-summary %}}
Çoğu zaman geliştiricilerin ODT dosyasını programlı olarak POTM'ye dönüştürmesi gerekir. Dosya Otomasyonu Java kitaplıklarını [Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak, oluşturma işlemini birkaç basit adımda otomatikleştirebilirsiniz. ODT dosyanızı [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak yükleyebilir ve HTML'ye dönüştürebilirsiniz. Bundan sonra, güçlü PowerPoint manipülasyonu Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanarak yeni bir Sunum oluşturabilir, içine HTML içeriği yazabilir ve POTM olarak kaydedebilirsiniz. .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile ODT'yi POTM'ye Dönüştürme" %}}
1. ODT dosyasını [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak açın
2. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak ODT dosyasını HTML'ye dönüştürün)) yöntem
3. Yeni bir [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) nesnesini başlatın
5. BufferedReader kullanarak HTML dosyasından içerik çıkarın ve içeriği sunum dosyanıza yazın
6. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) yöntemini kullanarak belgeyi POTM'ye kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
ODT'den POTM'ye dosya dönüştürme için Aspose.Total for Java'yı doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose) üzerinden kolayca kullanabilirsiniz. /aspose-total) tabanlı bir projedir ve pom.xml dosyanıza kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
API ayrıca parola korumalı ODT belgelerini POTM'ye dönüştürmenize olanak tanır. Girdiğiniz ODT belgeniz parola korumalıysa, parolayı kullanmadan POTM biçimine dönüştüremezsiniz. Şifrelenmiş bir belgeyi açmak için LoadOptions nesnesinde doğru parolayı ayarlayabilir ve bunu Document yapıcısına iletebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-ppsm/" name="ODT İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-pot/" name="ODT İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-powerpoint/" name="ODT İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-pptx/" name="ODT İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-potx/" name="ODT İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-pptm/" name="ODT İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-potm/" name="ODT İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-pps/" name="ODT İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-ppsx/" name="ODT İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-ppt/" name="ODT İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-csv/" name="ODT İle CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-dif/" name="ODT İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-fods/" name="ODT İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-ods/" name="ODT İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-sxc/" name="ODT İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-tsv/" name="ODT İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xlam/" name="ODT İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xltm/" name="ODT İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-excel/" name="ODT İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xls/" name="ODT İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xlsb/" name="ODT İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xlsm/" name="ODT İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xlsx/" name="ODT İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xlt/" name="ODT İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xltm/" name="ODT İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/odt-to-xltx/" name="ODT İle XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}