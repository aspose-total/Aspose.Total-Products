---
title: Java ile PPSM'u ODT'ye dönüştürün
description: Microsoft Word veya PowerPoint kullanmadan PPSM'u ODT'a Aktarmak için Java API
url_ignore: /tr/java/conversion/ppsm-to-odt/
family: total
platformtag: net
feature: conversion
informat: PPSM
outformat: ODT
otherformats: RTF ODTM FLATOPC ODTX DOTM DOT TEXT WORD WORDML DOTX OTT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile PPSM'u ODT'ye dönüştürün" h2="Herhangi bir Java J2SE, J2EE, J2ME uygulamasında PowerPoint PPSM'tan ODT'ye dönüştürme için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) Dosya Biçimi Otomasyonu kitaplıkları, Java geliştiricilerinin PowerPoint PPSM'tan Word ODT'a toplu dönüştürme sürecini otomatikleştirmesini sağlar. Belgeyi dönüştürmek iki adımlı bir işlemdir ve iki API kullanmayı içerir. PPSM'u HTML'ye dönüştürmek için sunum manipülasyonu ve yönetimi için bir PowerPoint API'si olan [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanacağız. Bundan sonra, zengin özelliklere sahip Kelime İşlem API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak HTML'yi ODT'ye dönüştüreceğiz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile PPSM'u ODT'ye Dönüştürme" %}}
1. [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPSM dosyasını açın
2. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak PPSM'u HTML'ye dönüştürün. ISaveOptions-) yöntemi ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) yöntemini kullanarak ODT biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
PPSM'tan ODT'ye dosya dönüştürme için, Aspose.Total for Java'yı doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose) üzerinden kolayca kullanabilirsiniz. /aspose-total) tabanlı bir projedir ve pom.xml dosyanıza kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
API'yi kullanarak, filigranlı PPSM dosyasını ODT'ye dönüştürme işlemini de gerçekleştirebilirsiniz. ODT belgenize filigran eklemek için öncelikle PPSM dosyasını HTML'ye çevirebilir ve ona bir filigran ekleyebilirsiniz. Filigran eklemek için, yeni oluşturulan HTML dosyasını [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin, bir TextWatermarkOptions örneği oluşturun ve ayarlayın özellikleri, Watermark.setText yöntemini çağırın ve filigran metnini ve TextWatermarkOptions nesnesini iletin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-word/" name="PPSM İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-dotx/" name="PPSM İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-odt/" name="PPSM İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-ott/" name="PPSM İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-rtf/" name="PPSM İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-flatopc/" name="PPSM İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-wordml/" name="PPSM İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-odtm/" name="PPSM İle ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-text/" name="PPSM İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-odtx/" name="PPSM İle ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-dotm/" name="PPSM İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsm-to-dot/" name="PPSM İle DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}