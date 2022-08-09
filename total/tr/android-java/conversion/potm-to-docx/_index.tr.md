---
title: Java aracılığıyla Andorid'de POTM'u DOCX'a aktarın
description: Herhangi bir yazılım yüklemeden mobil uygulamalarda POTM'u DOCX'ye dönüştürün
url: /tr/android-java/conversion/potm-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: DOCX
otherformats: TEXT DOTM ODT WORD DOC WORDML DOTX DOCM OTT DOT RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java aracılığıyla Andorid'de POTM'u DOCX'a dönüştürün" h2="Microsoft PowerPoint veya Word'e bağlı kalmadan Android uygulamalarında POTM'u DOCX'ye dönüştürmek için dosya biçimi API'leri" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java aracılığıyla Android için Aspose.Total](https://products.aspose.com/total/android-java/), Android uygulamalarında dosya biçimlerinin değiştirilmesine olanak tanır. Pakette sağlanan API'leri kullanarak, uygulamalarınızda PowerPoint POTM'tan Word DOCX'ye dönüştürme işlemini otomatikleştirebilirsiniz.
Verilen belgenizi iki adımda dönüştürebilirsiniz. POTM'u HTML'ye dönüştürmek için Android uygulamaları için bir PowerPoint API'si olan [Aspose.Slides for Andorid with Java](https://products.aspose.com/slides/android-java/) kullanabilirsiniz. Bundan sonra belge işleme API'sini [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) kullanarak HTML'yi DOCX'ye dönüştürebilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android'de POTM'tan DOCX'a İşleme" %}}
1. [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak POTM dosyasını açın
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides) kullanarak POTM'u HTML'ye dönüştürün.ISaveOptions-) yöntemi ve Html'yi SaveFormat olarak ayarlayın
3. Dönüştürülen HTML dosyasını [Docxument](https://reference.aspose.com/words/java/com.aspose.words/Docxument) sınıfını kullanarak yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,int)) yöntemini kullanarak DOCX biçiminde kaydedin ve Docx'u ayarlayın SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java aracılığıyla Aspose.Slides for Android](https://docxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ve [Java aracılığıyla Aspose.Words for Andorid]'i yükleyin (https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) uygulamalar.

Alternatif olarak, [downloads](https://downloads.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Docxument
Docxument docxument = new Docxument("htmlOutput.html");
// save docxument in DOCX format
docxument.save("output.docx",SaveFormat.Docxx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-text/" name="POTM İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-dotm/" name="POTM İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-odt/" name="POTM İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-word/" name="POTM İle WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-docx/" name="POTM İle DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-wordml/" name="POTM İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-dotx/" name="POTM İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-docxm/" name="POTM İle DOCXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-ott/" name="POTM İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-dot/" name="POTM İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-rtf/" name="POTM İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/potm-to-flatopc/" name="POTM İle FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}