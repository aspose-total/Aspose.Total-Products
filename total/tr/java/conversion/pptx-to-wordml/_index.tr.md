---
title: Java ile PPTX'u WORDML'ye dönüştürün
description: Microsoft Word veya PowerPoint kullanmadan PPTX'u WORDML'a Aktarmak için Java API
url_ignore: /tr/java/conversion/pptx-to-wordml/
family: total
platformtag: net
feature: conversion
informat: PPTX
outformat: WORDML
otherformats: WORD TEXT WORDMLX WORDML WORDMLM DOTX DOT RTF ODT OTT DOTM FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile PPTX'u WORDML'ye dönüştürün" h2="Herhangi bir Java J2SE, J2EE, J2ME uygulamasında PowerPoint PPTX'tan WORDML'ye dönüştürme için Şirket İçi Java API'si" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) Dosya Biçimi Otomasyonu kitaplıkları, Java geliştiricilerinin PowerPoint PPTX'tan Word WORDML'a toplu dönüştürme sürecini otomatikleştirmesini sağlar. Belgeyi dönüştürmek iki adımlı bir işlemdir ve iki API kullanmayı içerir. PPTX'u HTML'ye dönüştürmek için sunum manipülasyonu ve yönetimi için bir PowerPoint API'si olan [Aspose.Slides for Java](https://products.aspose.com/slides/java/) kullanacağız. Bundan sonra, zengin özelliklere sahip Kelime İşlem API'sini [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak HTML'yi WORDML'ye dönüştüreceğiz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java ile PPTX'u WORDML'ye Dönüştürme" %}}
1. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPTX dosyasını açın
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak PPTX'u HTML'ye dönüştürün. ISaveOptions-) yöntemi ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) yöntemini kullanarak WORDML biçiminde kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
PPTX'tan WORDML'ye dosya dönüştürme için, Aspose.Total for Java'yı doğrudan bir [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose) üzerinden kolayca kullanabilirsiniz. /aspose-total) tabanlı bir projedir ve pom.xml dosyanıza kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
API'yi kullanarak, filigranlı PPTX dosyasını WORDML'ye dönüştürme işlemini de gerçekleştirebilirsiniz. WORDML belgenize filigran eklemek için öncelikle PPTX dosyasını HTML'ye çevirebilir ve ona bir filigran ekleyebilirsiniz. Filigran eklemek için, yeni oluşturulan HTML dosyasını [Wordmlument](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument) sınıfını kullanarak yükleyin, bir TextWatermarkOptions örneği oluşturun ve ayarlayın özellikleri, Watermark.setText yöntemini çağırın ve filigran metnini ve TextWatermarkOptions nesnesini iletin.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-protected-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-word/" name="PPTX İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-dotx/" name="PPTX İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-odt/" name="PPTX İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-ott/" name="PPTX İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-rtf/" name="PPTX İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-flatopc/" name="PPTX İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-wordml/" name="PPTX İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-wordmlm/" name="PPTX İle WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-text/" name="PPTX İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-wordmlx/" name="PPTX İle WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-dotm/" name="PPTX İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pptx-to-dot/" name="PPTX İle DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}