---
title: Java ile DOCX'yi PPTX'ye dönüştürün
description: Microsoft Word veya PowerPoint kullanmadan DOCX'yi PPTX'ye Dışa Aktarmak için Java API
url: /tr/java/conversion/docx-to-pptx/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: PPTX
otherformats: POTX PPTM POT POTM PPSM POWERPOINT PPSX PPT PPS PPTX CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile DOCX'yi PPTX'ye dönüştürün" h2="Microsoft<sup>&reg;</sup> PowerPoint veya Word kullanmadan herhangi bir Java J2SE, J2EE, J2ME uygulamasında şirket içi Java API kullanarak DOCX'den PPTX'ye dönüştürme" >}}
{{% blocks/products/pf/feature-page-summary %}}
Çoğu zaman geliştiricilerin DOCX dosyasını programlı olarak PPTX'ye dönüştürmesi gerekir. Dosya Otomasyonu Java kitaplıklarını [Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak, oluşturma işlemini birkaç basit adımda otomatikleştirebilirsiniz. DOCX dosyanızı [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak yükleyebilir ve HTML'ye dönüştürebilirsiniz. Bundan sonra, güçlü PowerPoint manipülasyonu Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanarak yeni bir Sunum oluşturabilir, içine HTML içeriği yazabilir ve PPTX olarak kaydedebilirsiniz. .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile DOCX'yi PPTX'ye Dönüştürme" %}}
1. DOCX dosyasını [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak açın
2. [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak DOCX dosyasını HTML'ye dönüştürün)) yöntem
3. Yeni bir [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) nesnesini başlatın
5. BufferedReader kullanarak HTML dosyasından içerik çıkarın ve içeriği sunum dosyanıza yazın
6. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) yöntemini kullanarak belgeyi PPTX'ye kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
DOCX'den PPTX'ye dosya dönüştürme için Aspose.Total for Java'yı doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose) üzerinden kolayca kullanabilirsiniz. /aspose-total) tabanlı bir projedir ve pom.xml dosyanıza kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docx-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
API ayrıca parola korumalı DOCX belgelerini PPTX'ye dönüştürmenize olanak tanır. Girdiğiniz DOCX belgeniz parola korumalıysa, parolayı kullanmadan PPTX biçimine dönüştüremezsiniz. Şifrelenmiş bir belgeyi açmak için LoadOptions nesnesinde doğru parolayı ayarlayabilir ve bunu Document yapıcısına iletebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-docx-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-ppsm/" name="DOCX İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-pot/" name="DOCX İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-powerpoint/" name="DOCX İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-pptx/" name="DOCX İle PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-potx/" name="DOCX İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-pptm/" name="DOCX İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-potm/" name="DOCX İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-pps/" name="DOCX İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-ppsx/" name="DOCX İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-ppt/" name="DOCX İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-csv/" name="DOCX İle CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-dif/" name="DOCX İle DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-fods/" name="DOCX İle FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-ods/" name="DOCX İle ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-sxc/" name="DOCX İle SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-tsv/" name="DOCX İle TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xlam/" name="DOCX İle XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xltm/" name="DOCX İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-excel/" name="DOCX İle EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xls/" name="DOCX İle XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xlsb/" name="DOCX İle XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xlsm/" name="DOCX İle XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xlsx/" name="DOCX İle XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xlt/" name="DOCX İle XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xltm/" name="DOCX İle XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/docx-to-xltx/" name="DOCX İle XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}