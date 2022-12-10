---
title: Andorid Uygulamasında EML to GIF'ye dönüştürün
description: Andorid uygulamalarınızda Microsoft Word veya Outlook kullanmadan EML'i GIF'ye aktarın

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: GIF
otherformats: EPUB TEXT PNG ODT PDF FLATOPC DOCX EMF DOT OTT WORDML XPS JPEG PCL DOCM DOTX RTF BMP MD PS SVG DOTM TIFF DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Andorid Uygulamalarında EML'i GIF'ye Dönüştürün" h2="Java API aracılığıyla Andorid kullanarak EML'i GIF'ye aktarmak için Andorid uygulamaları tasarlama" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps, son kullanıcılar için günlük bazda kullanımı kolaydır. Gün geçtikçe Andorid telefon kullanıcılarının sayısı artıyor. Güçlü [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Dosya Biçimi Otomasyonu kitaplıklarını kullanarak E-posta işleme ve dönüştürme uygulamaları geliştirebilirsiniz. [Aspose.Eml for Android Java](https://products.aspose.com/eml/android-java/) ve [Aspose.Words for Andorid Java](https://) kombinasyonunu kullanarak EML'i GIF'ye dönüştürebilirsiniz. Products.aspose.com/words/android-java/). İlk API'yi kullanarak EML dosya biçimini HTML'ye dönüştürebilir ve ikinci API'yi kullanarak HTML'yi GIF olarak oluşturabilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EML'i Andorid'de GIF'ye Dönüştür" %}}
1. [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) sınıfını kullanarak EML dosyasını açın
2. [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) kullanarak EML'i HTML'ye dönüştürün )) yöntem
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak HTML yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) kullanarak GIF biçiminde kaydedin )) yöntemi ve GIF'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) üzerinden kolayca kullanabilirsiniz ve [Java üzerinden Aspose.Eml for Android](https://docs.aspose.com/eml/androidjava/installation/) ve [Java üzerinden Aspose.Words for Andorid](https://docs.aspose.com/words) yükleyin /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) uygulamalarınızda.

Alternatif olarak, [downloads](https://releases.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.GIF
document.save("output.gif", SaveFormat.GIF); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-epub/" name="EML İle EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-text/" name="EML İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-png/" name="EML İle PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-odt/" name="EML İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-pdf/" name="EML İle PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-flatopc/" name="EML İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-docx/" name="EML İle DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-emf/" name="EML İle EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-dot/" name="EML İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-ott/" name="EML İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-wordml/" name="EML İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-xps/" name="EML İle XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-jpeg/" name="EML İle JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-pcl/" name="EML İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-docm/" name="EML İle DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-dotx/" name="EML İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-rtf/" name="EML İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-gif/" name="EML İle GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-md/" name="EML İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-ps/" name="EML İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-svg/" name="EML İle SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-dotm/" name="EML İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-tiff/" name="EML İle TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/android-java/conversion/eml-to-doc/" name="EML İle DOC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}