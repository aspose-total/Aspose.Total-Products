---
title: Java ile PPTM'u DOTM'ye dönüştürün
description: Microsoft Word veya PowerPoint kullanmadan PPTM'u DOTM'a Aktarmak için Java API
url: /tr/java/conversion/pptm-to-dotm/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: DOTM
otherformats: DOTMX DOTMM FLATOPC DOTM TEXT WORDML OTT DOT WORD ODT RTF DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile PPTM'u DOTM'ye dönüştürün" h2="Herhangi bir Java J2SE, J2EE, J2ME uygulamasında PowerPoint PPTM'tan DOTM'ye dönüştürme için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) Dosya Biçimi Otomasyonu kitaplıkları, Java geliştiricilerinin PowerPoint PPTM'tan Word DOTM'a toplu dönüştürme sürecini otomatikleştirmesini sağlar. Belgeyi dönüştürmek iki adımlı bir işlemdir ve iki API kullanmayı içerir. PPTM'u HTML'ye dönüştürmek için sunum manipülasyonu ve yönetimi için bir PowerPoint API'si olan [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanacağız. Bundan sonra, zengin özelliklere sahip Kelime İşlem API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak HTML'yi DOTM'ye dönüştüreceğiz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile PPTM'u DOTM'ye Dönüştürme" %}}
1. [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPTM dosyasını açın
2. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak PPTM'u HTML'ye dönüştürün. ISaveOptions-) yöntemi ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Dotmument](https://apireference.aspose.com/words/java/com.aspose.words/Dotmument) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://apireference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,int)) yöntemini kullanarak DOTM biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
PPTM'tan DOTM'ye dosya dönüştürme için, Aspose.Total for Java'yı doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose) üzerinden kolayca kullanabilirsiniz. /aspose-total) tabanlı bir projedir ve pom.xml dosyanıza kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
API'yi kullanarak, filigranlı PPTM dosyasını DOTM'ye dönüştürme işlemini de gerçekleştirebilirsiniz. DOTM belgenize filigran eklemek için öncelikle PPTM dosyasını HTML'ye çevirebilir ve ona bir filigran ekleyebilirsiniz. Filigran eklemek için, yeni oluşturulan HTML dosyasını [Dotmument](https://apireference.aspose.com/words/java/com.aspose.words/Dotmument) sınıfını kullanarak yükleyin, bir TextWatermarkOptions örneği oluşturun ve ayarlayın özellikleri, Watermark.setText yöntemini çağırın ve filigran metnini ve TextWatermarkOptions nesnesini iletin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-word/" name="PPTM İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-dotx/" name="PPTM İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-odt/" name="PPTM İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-ott/" name="PPTM İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-rtf/" name="PPTM İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-flatopc/" name="PPTM İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-wordml/" name="PPTM İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-dotmm/" name="PPTM İle DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-text/" name="PPTM İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-dotmx/" name="PPTM İle DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-dotm/" name="PPTM İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptm-to-dot/" name="PPTM İle DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}