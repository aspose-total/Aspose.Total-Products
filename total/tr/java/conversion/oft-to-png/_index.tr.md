---
title: OFT'i Java aracılığıyla PNG'ye aktarın
description: Microsoft Word veya Outlook kullanmadan OFT'i PNG'ye Dönüştürmek için Java API
url_ignore: /tr/java/conversion/oft-to-png/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: PNG
otherformats: OTT MD DOCM DOT DOTX RTF JPEG XPS GIF PCL SVG EPUB DOCX FLATOPC TEXT DOTM PS PNG EMF DOC PDF TIFF WORDML ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="E-POSTA'yı PNG'ye Dönüştürmek için Java API" h2="Herhangi bir üçüncü taraf bağımlılığı kullanmadan şirket içi Java API'sini kullanarak OFT'i PNG'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
E-posta dönüştürme, Java geliştiricilerinin [Aspose.Total for Java](https://products.aspose.com/total/java/) aracılığıyla herhangi bir Java J2SE, J2EE, J2ME uygulamasına entegre edebileceği güçlü bir özelliktir. Paket içinde iki API kullanarak, herhangi bir üçüncü taraf bağımlılığı olmadan E-posta E-postasını PNG'ye dönüştürebilirsiniz. İlk olarak, OFT dosya biçimini HTML'ye dönüştürmek için Oft Manipulation API'sini [Aspose.Oft for Java](https://products.aspose.com/email/java/) kullanabilirsiniz. İkinci olarak, Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak HTML'yi PNG'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="OFT'i PNG'ye Dönüştürme" %}}
1. [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) sınıfını kullanarak OFT dosyasını açın
2. [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions) kullanarak OFT'i HTML'ye dönüştürün)) yöntem
3. HTML'yi [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak belgeyi PNG biçiminde kaydedin)) yöntemi ve PNG'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kullanmanız gerekir. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PNG
document.save("output.png", SaveFormat.PNG);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-png/" name="MSG İle PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-doc/" name="MSG İle DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-ott/" name="MSG İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-odt/" name="MSG İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-wordml/" name="MSG İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-dotx/" name="MSG İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-svg/" name="MSG İle SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-docx/" name="MSG İle DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-epub/" name="MSG İle EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-text/" name="MSG İle TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-xps/" name="MSG İle XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-ps/" name="MSG İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-flatopc/" name="MSG İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-docm/" name="MSG İle DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-jpeg/" name="MSG İle JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-tiff/" name="MSG İle TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-dot/" name="MSG İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-emf/" name="MSG İle EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-rtf/" name="MSG İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-gif/" name="MSG İle GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-pcl/" name="MSG İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-dotm/" name="MSG İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-md/" name="MSG İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-pdf/" name="MSG İle PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}