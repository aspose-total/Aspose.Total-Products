---
title: Andorid Uygulamasında EMAIL to PS'ye dönüştürün
description: Andorid uygulamalarınızda Microsoft Word veya Outlook kullanmadan EMAIL'i PS'ye aktarın

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: PS
otherformats: OTT EPUB DOT DOCM EMF PNG WORDML XPS PCL GIF ODT RTF JPEG DOTX DOCX MD SVG DOTM FLATOPC BMP PDF TEXT DOC TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Andorid Uygulamalarında EMAIL'i PS'ye Dönüştürün" h2="Java API aracılığıyla Andorid kullanarak EMAIL'i PS'ye aktarmak için Andorid uygulamaları tasarlama" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps, son kullanıcılar için günlük bazda kullanımı kolaydır. Gün geçtikçe Andorid telefon kullanıcılarının sayısı artıyor. Güçlü [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Dosya Biçimi Otomasyonu kitaplıklarını kullanarak E-posta işleme ve dönüştürme uygulamaları geliştirebilirsiniz. [Aspose.Email for Android Java](https://products.aspose.com/email/android-java/) ve [Aspose.Words for Andorid Java](https://) kombinasyonunu kullanarak EMAIL'i PS'ye dönüştürebilirsiniz. Products.aspose.com/words/android-java/). İlk API'yi kullanarak EMAIL dosya biçimini HTML'ye dönüştürebilir ve ikinci API'yi kullanarak HTML'yi PS olarak oluşturabilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAIL'i Andorid'de PS'ye Dönüştür" %}}
1. [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) sınıfını kullanarak EMAIL dosyasını açın
2. [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) kullanarak EMAIL'i HTML'ye dönüştürün )) yöntem
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak HTML yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) kullanarak PS biçiminde kaydedin )) yöntemi ve PS'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://releases.aspose.com/total/java/) üzerinden kolayca kullanabilirsiniz ve [Aspose.Email for Android via Java](https://docs.aspose.com/email/androidjava/installation/) ve [Java üzerinden Aspose.Words for Andorid](https://docs.aspose.com/words) yükleyin /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) uygulamalarınızda.

Alternatif olarak, [downloads](https://releases.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PS
document.save("output.ps", SaveFormat.PS); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}