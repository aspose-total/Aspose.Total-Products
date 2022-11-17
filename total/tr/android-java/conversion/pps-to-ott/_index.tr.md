---
title: Java aracılığıyla Andorid'de PPS'u OTT'a aktarın
description: Herhangi bir yazılım yüklemeden mobil uygulamalarda PPS'u OTT'ye dönüştürün

family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: OTT
otherformats: DOTM TEXT WORD FLATOPC WORDML RTF DOCX DOTX DOCM ODT DOT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Andorid'de PPS'u OTT'a dönüştürün" h2="Microsoft PowerPoint veya Word'e bağlı kalmadan Android uygulamalarında PPS'u OTT'ye dönüştürmek için dosya biçimi API'leri" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), Android uygulamalarında dosya biçimlerinin değiştirilmesine olanak tanır. Pakette sağlanan API'leri kullanarak, uygulamalarınızda PowerPoint PPS'tan Word OTT'ye dönüştürme işlemini otomatikleştirebilirsiniz.
Verilen belgenizi iki adımda dönüştürebilirsiniz. PPS'u HTML'ye dönüştürmek için Android uygulamaları için bir PowerPoint API'si olan [Aspose.Slides for Andorid with Java](https://products.aspose.com/slides/android-java/) kullanabilirsiniz. Bundan sonra belge işleme API'sini [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) kullanarak HTML'yi OTT'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android'de PPS'tan OTT'a İşleme" %}}
1. [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPS dosyasını açın
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak PPS'u HTML'ye dönüştürün.ISaveOptions-) yöntemi ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Ottument](https://reference.aspose.com/words/java/com.aspose.words/Ottument) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,int)) yöntemini kullanarak OTT biçiminde kaydedin ve Ott'u ayarlayın SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java aracılığıyla Aspose.Slides for Android](https://otts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ve [Java aracılığıyla Aspose.Words for Andorid]'i yükleyin (https://otts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) uygulamalar.

Alternatif olarak, [downloads](https://downloads.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Ottument
Ottument ottument = new Ottument("htmlOutput.html");
// save ottument in OTT format
ottument.save("output.ott",SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-dotm/" name="PPS İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-text/" name="PPS İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-word/" name="PPS İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-flatopc/" name="PPS İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-wordml/" name="PPS İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-rtf/" name="PPS İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-ottx/" name="PPS İle OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-dotx/" name="PPS İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-ottm/" name="PPS İle OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-odt/" name="PPS İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-dot/" name="PPS İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pps-to-ott/" name="PPS İle OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}