---
title: Andorid Uygulamasında EMLX to PS'ye dönüştürün
description: Andorid uygulamalarınızda Microsoft Word veya Outlook kullanmadan EMLX'i PS'ye aktarın
url: /tr/android-java/conversion/emlx-to-ps/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: PS
otherformats: DOTX BMP TIFF MD DOCX GIF SVG PCL ODT DOT FLATOPC EMF TEXT JPEG EPUB DOC PNG RTF XPS PDF DOTM WORDML OTT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Andorid Uygulamalarında EMLX'i PS'ye Dönüştürün" h2="Java API aracılığıyla Andorid kullanarak EMLX'i PS'ye aktarmak için Andorid uygulamaları tasarlama" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps, son kullanıcılar için günlük bazda kullanımı kolaydır. Gün geçtikçe Andorid telefon kullanıcılarının sayısı artıyor. Güçlü [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Dosya Biçimi Otomasyonu kitaplıklarını kullanarak E-posta işleme ve dönüştürme uygulamaları geliştirebilirsiniz. [Aspose.Emlx for Android Java](https://products.aspose.com/emlx/android-java/) ve [Aspose.Words for Andorid Java](https://) kombinasyonunu kullanarak EMLX'i PS'ye dönüştürebilirsiniz. Products.aspose.com/words/android-java/). İlk API'yi kullanarak EMLX dosya biçimini HTML'ye dönüştürebilir ve ikinci API'yi kullanarak HTML'yi PS olarak oluşturabilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLX'i Andorid'de PS'ye Dönüştür" %}}
1. [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage) sınıfını kullanarak EMLX dosyasını açın
2. [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions) kullanarak EMLX'i HTML'ye dönüştürün )) yöntem
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak HTML yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) kullanarak PS biçiminde kaydedin )) yöntemi ve PS'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java üzerinden Aspose.Emlx for Android](https://docs.aspose.com/emlx/androidjava/installation/) ve [Java üzerinden Aspose.Words for Andorid](https://docs.aspose.com/words) yükleyin /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) uygulamalarınızda.

Alternatif olarak, [downloads](https://downloads.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PS
document.save("output.ps", SaveFormat.PS); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-dotx/" name="EMLX İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-ps/" name="EMLX İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-tiff/" name="EMLX İle TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-md/" name="EMLX İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-docx/" name="EMLX İle DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-gif/" name="EMLX İle GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-svg/" name="EMLX İle SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-pcl/" name="EMLX İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-odt/" name="EMLX İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-dot/" name="EMLX İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-flatopc/" name="EMLX İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-emf/" name="EMLX İle EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-text/" name="EMLX İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-jpeg/" name="EMLX İle JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-epub/" name="EMLX İle EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-doc/" name="EMLX İle DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-png/" name="EMLX İle PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-rtf/" name="EMLX İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-xps/" name="EMLX İle XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-pdf/" name="EMLX İle PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-dotm/" name="EMLX İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-wordml/" name="EMLX İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-ott/" name="EMLX İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/emlx-to-docm/" name="EMLX İle DOCM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}