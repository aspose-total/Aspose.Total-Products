---
title: MSG'i Java aracılığıyla JPEG'ye aktarın
description: Microsoft Word veya Outlook kullanmadan MSG'i JPEG'ye Dönüştürmek için Java API
url_ignore: /tr/java/conversion/msg-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: JPEG
otherformats: JPEG SVG OTT WORDML DOC XPS FLATOPC RTF DOTM TIFF ODT EMF EPUB DOTX DOT TEXT DOCM PCL PS GIF PNG DOCX MD PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="E-POSTA'yı JPEG'ye Dönüştürmek için Java API" h2="Herhangi bir üçüncü taraf bağımlılığı kullanmadan şirket içi Java API'sini kullanarak MSG'i JPEG'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
E-posta dönüştürme, Java geliştiricilerinin [Aspose.Total for Java](https://products.aspose.com/total/java/) aracılığıyla herhangi bir Java J2SE, J2EE, J2ME uygulamasına entegre edebileceği güçlü bir özelliktir. Paket içinde iki API kullanarak, herhangi bir üçüncü taraf bağımlılığı olmadan E-posta E-postasını JPEG'ye dönüştürebilirsiniz. İlk olarak, MSG dosya biçimini HTML'ye dönüştürmek için Msg Manipulation API'sini [Aspose.Email for Java](https://products.aspose.com/email/java/) kullanabilirsiniz. İkinci olarak, Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak HTML'yi JPEG'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MSG'i JPEG'ye Dönüştürme" %}}
1. [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) sınıfını kullanarak MSG dosyasını açın
2. [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions) kullanarak MSG'i HTML'ye dönüştürün)) yöntem
3. HTML'yi [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak belgeyi JPEG biçiminde kaydedin)) yöntemi ve JPEG'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kullanmanız gerekir. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.JPEG
document.save("output.jpeg", SaveFormat.JPEG);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}