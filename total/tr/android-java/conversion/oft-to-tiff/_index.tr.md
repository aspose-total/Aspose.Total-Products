---
title: Andorid Uygulamasında OFT to TIFF'ye dönüştürün
description: Andorid uygulamalarınızda Microsoft Word veya Outlook kullanmadan OFT'i TIFF'ye aktarın

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: TIFF
otherformats: FLATOPC DOCM DOTM XPS RTF EPUB EMF PCL PDF JPEG DOT TEXT BMP MD DOTX PS PNG SVG DOCX WORDML DOC OTT ODT GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Andorid Uygulamalarında OFT'i TIFF'ye Dönüştürün" h2="Java API aracılığıyla Andorid kullanarak OFT'i TIFF'ye aktarmak için Andorid uygulamaları tasarlama" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps, son kullanıcılar için günlük bazda kullanımı kolaydır. Gün geçtikçe Andorid telefon kullanıcılarının sayısı artıyor. Güçlü [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Dosya Biçimi Otomasyonu kitaplıklarını kullanarak E-posta işleme ve dönüştürme uygulamaları geliştirebilirsiniz. [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/) ve [Aspose.Words for Andorid Java](https://) kombinasyonunu kullanarak OFT'i TIFF'ye dönüştürebilirsiniz. Products.aspose.com/words/android-java/). İlk API'yi kullanarak OFT dosya biçimini HTML'ye dönüştürebilir ve ikinci API'yi kullanarak HTML'yi TIFF olarak oluşturabilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="OFT'i Andorid'de TIFF'ye Dönüştür" %}}
1. [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage) sınıfını kullanarak OFT dosyasını açın
2. [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions) kullanarak OFT'i HTML'ye dönüştürün )) yöntem
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak HTML yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) kullanarak TIFF biçiminde kaydedin )) yöntemi ve TIFF'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://releases.aspose.com/total/java/) üzerinden kolayca kullanabilirsiniz ve [Java üzerinden Aspose.Oft for Android](https://docs.aspose.com/oft/androidjava/installation/) ve [Java üzerinden Aspose.Words for Andorid](https://docs.aspose.com/words) yükleyin /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) uygulamalarınızda.

Alternatif olarak, [downloads](https://releases.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.TIFF
document.save("output.tiff", SaveFormat.TIFF); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}