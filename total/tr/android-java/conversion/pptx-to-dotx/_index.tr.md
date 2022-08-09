---
title: Java aracılığıyla Andorid'de PPTX'u DOTX'a aktarın
description: Herhangi bir yazılım yüklemeden mobil uygulamalarda PPTX'u DOTX'ye dönüştürün
url: /tr/android-java/conversion/pptx-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: DOTX
otherformats: DOC OTT DOTM FLATOPC TEXT RTF DOCX WORD ODT WORDML DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Andorid'de PPTX'u DOTX'a dönüştürün" h2="Microsoft PowerPoint veya Word'e bağlı kalmadan Android uygulamalarında PPTX'u DOTX'ye dönüştürmek için dosya biçimi API'leri" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java aracılığıyla Android için Aspose.Total](https://products.aspose.com/total/android-java/), Android uygulamalarında dosya biçimlerinin değiştirilmesine olanak tanır. Pakette sağlanan API'leri kullanarak, uygulamalarınızda PowerPoint PPTX'tan Word DOTX'ye dönüştürme işlemini otomatikleştirebilirsiniz.
Verilen belgenizi iki adımda dönüştürebilirsiniz. PPTX'u HTML'ye dönüştürmek için Android uygulamaları için bir PowerPoint API'si olan [Aspose.Slides for Andorid with Java](https://products.aspose.com/slides/android-java/) kullanabilirsiniz. Bundan sonra belge işleme API'sini [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) kullanarak HTML'yi DOTX'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android'de PPTX'tan DOTX'a İşleme" %}}
1. [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPTX dosyasını açın
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak PPTX'u HTML'ye dönüştürün.ISaveOptions-) yöntemi ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,int)) yöntemini kullanarak DOTX biçiminde kaydedin ve Dotx'u ayarlayın SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java aracılığıyla Aspose.Slides for Android](https://dotxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ve [Java aracılığıyla Aspose.Words for Andorid]'i yükleyin (https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) uygulamalar.

Alternatif olarak, [downloads](https://downloads.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotxument
Dotxument dotxument = new Dotxument("htmlOutput.html");
// save dotxument in DOTX format
dotxument.save("output.dotx",SaveFormat.Dotx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-dotx/" name="PPTX İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-ott/" name="PPTX İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-dotm/" name="PPTX İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-flatopc/" name="PPTX İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-text/" name="PPTX İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-rtf/" name="PPTX İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-dotxx/" name="PPTX İle DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-word/" name="PPTX İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-odt/" name="PPTX İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-wordml/" name="PPTX İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-dot/" name="PPTX İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/pptx-to-dotxm/" name="PPTX İle DOTXM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}