---
title: Andorid Uygulamasında EMLX to PDF'ye dönüştürün
description: Andorid uygulamalarınızda Microsoft Word veya Outlook kullanmadan EMLX'i PDF'ye aktarın

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: PDF
otherformats: OTT DOCM TIFF GIF FLATOPC JPEG BMP PS DOCX ODT XPS DOC RTF WORDML TEXT SVG DOTM EPUB PCL EMF DOT PNG MD DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Andorid Uygulamalarında EMLX'i PDF'ye Dönüştürün" h2="Java API aracılığıyla Andorid kullanarak EMLX'i PDF'ye aktarmak için Andorid uygulamaları tasarlama" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps, son kullanıcılar için günlük bazda kullanımı kolaydır. Gün geçtikçe Andorid telefon kullanıcılarının sayısı artıyor. Güçlü [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Dosya Biçimi Otomasyonu kitaplıklarını kullanarak E-posta işleme ve dönüştürme uygulamaları geliştirebilirsiniz. [Aspose.Emlx for Android Java](https://products.aspose.com/emlx/android-java/) ve [Aspose.Words for Andorid Java](https://) kombinasyonunu kullanarak EMLX'i PDF'ye dönüştürebilirsiniz. Products.aspose.com/words/android-java/). İlk API'yi kullanarak EMLX dosya biçimini HTML'ye dönüştürebilir ve ikinci API'yi kullanarak HTML'yi PDF olarak oluşturabilirsiniz. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLX'i Andorid'de PDF'ye Dönüştür" %}}
1. [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage) sınıfını kullanarak EMLX dosyasını açın
2. [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions) kullanarak EMLX'i HTML'ye dönüştürün )) yöntem
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak HTML yükleyin
4. Belgeyi [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) kullanarak PDF biçiminde kaydedin )) yöntemi ve PDF'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Android'i Java aracılığıyla doğrudan [Maven](https://releases.aspose.com/total/java/) üzerinden kolayca kullanabilirsiniz ve [Java üzerinden Aspose.Emlx for Android](https://docs.aspose.com/emlx/androidjava/installation/) ve [Java üzerinden Aspose.Words for Andorid](https://docs.aspose.com/words) yükleyin /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) uygulamalarınızda.

Alternatif olarak, [downloads](https://releases.aspose.com/total/androidjava) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PDF
document.save("output.pdf", SaveFormat.PDF); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}