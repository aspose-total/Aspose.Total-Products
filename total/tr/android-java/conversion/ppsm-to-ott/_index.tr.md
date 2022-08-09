---
title: Java aracılığıyla Andorid'de PPSM'u OTT'a aktarın
description: Herhangi bir yazılım yüklemeden mobil uygulamalarda PPSM'u OTT'ye dönüştürün
url: /tr/android-java/conversion/ppsm-to-ott/
family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: OTT
otherformats: RTF DOC TEXT ODT DOTM WORD DOT FLATOPC DOTX DOCX DOCM WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Andorid'de PPSM'u OTT'a dönüştürün" h2="Microsoft PowerPoint veya Word'e bağlı kalmadan Android uygulamalarında PPSM'u OTT'ye dönüştürmek için dosya biçimi API'leri" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java aracılığıyla Android için Aspose.Total](https://products.aspose.com/total/android-java/), Android uygulamalarında dosya biçimlerinin değiştirilmesine olanak tanır. Pakette sağlanan API'leri kullanarak, uygulamalarınızda PowerPoint PPSM'tan Word OTT'ye dönüştürme işlemini otomatikleştirebilirsiniz.
Verilen belgenizi iki adımda dönüştürebilirsiniz. PPSM'u HTML'ye dönüştürmek için Android uygulamaları için bir PowerPoint API'si olan [Aspose.Slides for Andorid with Java](https://products.aspose.com/slides/android-java/) kullanabilirsiniz. Bundan sonra belge işleme API'sini [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) kullanarak HTML'yi OTT'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android'de PPSM'tan OTT'a İşleme" %}}
1. [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPSM dosyasını açın
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak PPSM'u HTML'ye dönüştürün.ISaveOptions-) yöntemi ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Ottument](https://reference.aspose.com/words/java/com.aspose.words/Ottument) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,int)) yöntemini kullanarak OTT biçiminde kaydedin ve Ott'u ayarlayın SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java aracılığıyla Aspose.Slides for Android](https://otts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ve [Java aracılığıyla Aspose.Words for Andorid]'i yükleyin (https://otts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) uygulamalar.

Alternatif olarak, [downloads](https://downloads.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("input.ppsm");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-rtf/" name="PPSM İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-ott/" name="PPSM İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-text/" name="PPSM İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-odt/" name="PPSM İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-dotm/" name="PPSM İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-word/" name="PPSM İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-dot/" name="PPSM İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-flatopc/" name="PPSM İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-dotx/" name="PPSM İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-ottx/" name="PPSM İle OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-ottm/" name="PPSM İle OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppsm-to-wordml/" name="PPSM İle WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}