---
title: Java ile PPSX'u WORDML'ye dönüştürün
description: Microsoft Word veya PowerPoint kullanmadan PPSX'u WORDML'a Aktarmak için Java API
url_ignore: /tr/java/conversion/ppsx-to-wordml/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: WORDML
otherformats: ODT WORD FLATOPC OTT WORDML WORDMLM RTF DOTX DOTM DOT WORDMLX TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile PPSX'u WORDML'ye dönüştürün" h2="Herhangi bir Java J2SE, J2EE, J2ME uygulamasında PowerPoint PPSX'tan WORDML'ye dönüştürme için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) Dosya Biçimi Otomasyonu kitaplıkları, Java geliştiricilerinin PowerPoint PPSX'tan Word WORDML'a toplu dönüştürme sürecini otomatikleştirmesini sağlar. Belgeyi dönüştürmek iki adımlı bir işlemdir ve iki API kullanmayı içerir. PPSX'u HTML'ye dönüştürmek için sunum manipülasyonu ve yönetimi için bir PowerPoint API'si olan [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanacağız. Bundan sonra, zengin özelliklere sahip Kelime İşlem API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak HTML'yi WORDML'ye dönüştüreceğiz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile PPSX'u WORDML'ye Dönüştürme" %}}
1. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPSX dosyasını açın
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak PPSX'u HTML'ye dönüştürün. ISaveOptions-) yöntemi ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) yöntemini kullanarak WORDML biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
PPSX'tan WORDML'ye dosya dönüştürme için, Aspose.Total for Java'yı doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose) üzerinden kolayca kullanabilirsiniz. /aspose-total) tabanlı bir projedir ve pom.xml dosyanıza kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
API'yi kullanarak, filigranlı PPSX dosyasını WORDML'ye dönüştürme işlemini de gerçekleştirebilirsiniz. WORDML belgenize filigran eklemek için öncelikle PPSX dosyasını HTML'ye çevirebilir ve ona bir filigran ekleyebilirsiniz. Filigran eklemek için, yeni oluşturulan HTML dosyasını [Wordmlument](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument) sınıfını kullanarak yükleyin, bir TextWatermarkOptions örneği oluşturun ve ayarlayın özellikleri, Watermark.setText yöntemini çağırın ve filigran metnini ve TextWatermarkOptions nesnesini iletin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-word/" name="PPSX İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-dotx/" name="PPSX İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-odt/" name="PPSX İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-ott/" name="PPSX İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-rtf/" name="PPSX İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-flatopc/" name="PPSX İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-wordml/" name="PPSX İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-wordmlm/" name="PPSX İle WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-text/" name="PPSX İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-wordmlx/" name="PPSX İle WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-dotm/" name="PPSX İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-dot/" name="PPSX İle DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}