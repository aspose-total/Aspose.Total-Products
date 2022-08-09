---
title: Java aracılığıyla Andorid'de PPT'u FLATOPC'a aktarın
description: Herhangi bir yazılım yüklemeden mobil uygulamalarda PPT'u FLATOPC'ye dönüştürün
url: /tr/android-java/conversion/ppt-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: FLATOPC
otherformats: ODT DOCM TEXT DOTX DOCX WORD WORDML RTF DOT DOTM DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Andorid'de PPT'u FLATOPC'a dönüştürün" h2="Microsoft PowerPoint veya Word'e bağlı kalmadan Android uygulamalarında PPT'u FLATOPC'ye dönüştürmek için dosya biçimi API'leri" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java aracılığıyla Android için Aspose.Total](https://products.aspose.com/total/android-java/), Android uygulamalarında dosya biçimlerinin değiştirilmesine olanak tanır. Pakette sağlanan API'leri kullanarak, uygulamalarınızda PowerPoint PPT'tan Word FLATOPC'ye dönüştürme işlemini otomatikleştirebilirsiniz.
Verilen belgenizi iki adımda dönüştürebilirsiniz. PPT'u HTML'ye dönüştürmek için Android uygulamaları için bir PowerPoint API'si olan [Aspose.Slides for Andorid with Java](https://products.aspose.com/slides/android-java/) kullanabilirsiniz. Bundan sonra belge işleme API'sini [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) kullanarak HTML'yi FLATOPC'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android'de PPT'tan FLATOPC'a İşleme" %}}
1. [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPT dosyasını açın
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak PPT'u HTML'ye dönüştürün.ISaveOptions-) yöntemi ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Flatopcument](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument#save(java.lang.String,int)) yöntemini kullanarak FLATOPC biçiminde kaydedin ve Flatopc'u ayarlayın SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java aracılığıyla Aspose.Slides for Android](https://flatopcs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ve [Java aracılığıyla Aspose.Words for Andorid]'i yükleyin (https://flatopcs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) uygulamalar.

Alternatif olarak, [downloads](https://downloads.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPT file
Presentation presentation = new Presentation("input.ppt");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Flatopcument
Flatopcument flatopcument = new Flatopcument("htmlOutput.html");
// save flatopcument in FLATOPC format
flatopcument.save("output.flatopc",SaveFormat.FlatOpc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-odt/" name="PPT İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-flatopcm/" name="PPT İle FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-text/" name="PPT İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-dotx/" name="PPT İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-flatopcx/" name="PPT İle FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-word/" name="PPT İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-wordml/" name="PPT İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-rtf/" name="PPT İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-dot/" name="PPT İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-dotm/" name="PPT İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-flatopc/" name="PPT İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/ppt-to-ott/" name="PPT İle OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}