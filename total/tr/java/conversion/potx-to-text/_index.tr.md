---
title: Java ile POTX'u TEXT'ye dönüştürün
description: Microsoft Word veya PowerPoint kullanmadan POTX'u TEXT'a Aktarmak için Java API
url_ignore: /tr/java/conversion/potx-to-text/
family: total
platformtag: net
feature: conversion
informat: POTXX
outformat: TEXT
otherformats: WORDML DOTM TEXT RTF TEXTX ODT TEXTM FLATOPC DOT WORD OTT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile POTX'u TEXT'ye dönüştürün" h2="Herhangi bir Java J2SE, J2EE, J2ME uygulamasında PowerPoint POTX'tan TEXT'ye dönüştürme için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) Dosya Biçimi Otomasyonu kitaplıkları, Java geliştiricilerinin PowerPoint POTX'tan Word TEXT'a toplu dönüştürme sürecini otomatikleştirmesini sağlar. Belgeyi dönüştürmek iki adımlı bir işlemdir ve iki API kullanmayı içerir. POTX'u HTML'ye dönüştürmek için sunum manipülasyonu ve yönetimi için bir PowerPoint API'si olan [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanacağız. Bundan sonra, zengin özelliklere sahip Kelime İşlem API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak HTML'yi TEXT'ye dönüştüreceğiz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile POTX'u TEXT'ye Dönüştürme" %}}
1. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak POTX dosyasını açın
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak POTX'u HTML'ye dönüştürün. ISaveOptions-) yöntemi ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Textument](https://reference.aspose.com/words/java/com.aspose.words/Textument) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Textument#save(java.lang.String,int)) yöntemini kullanarak TEXT biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
POTX'tan TEXT'ye dosya dönüştürme için, Aspose.Total for Java'yı doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose) üzerinden kolayca kullanabilirsiniz. /aspose-total) tabanlı bir projedir ve pom.xml dosyanıza kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
API'yi kullanarak, filigranlı POTX dosyasını TEXT'ye dönüştürme işlemini de gerçekleştirebilirsiniz. TEXT belgenize filigran eklemek için öncelikle POTX dosyasını HTML'ye çevirebilir ve ona bir filigran ekleyebilirsiniz. Filigran eklemek için, yeni oluşturulan HTML dosyasını [Textument](https://reference.aspose.com/words/java/com.aspose.words/Textument) sınıfını kullanarak yükleyin, bir TextWatermarkOptions örneği oluşturun ve ayarlayın özellikleri, Watermark.setText yöntemini çağırın ve filigran metnini ve TextWatermarkOptions nesnesini iletin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-word/" name="POTX İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-dotx/" name="POTX İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-odt/" name="POTX İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-ott/" name="POTX İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-rtf/" name="POTX İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-flatopc/" name="POTX İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-wordml/" name="POTX İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-textm/" name="POTX İle TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-text/" name="POTX İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-textx/" name="POTX İle TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-dotm/" name="POTX İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/potx-to-dot/" name="POTX İle DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}