---
title: EML'i Java aracılığıyla BMP'ye aktarın
description: Microsoft Word veya Outlook kullanmadan EML'i BMP'ye Dönüştürmek için Java API
url_ignore: /tr/java/conversion/eml-to-bmp/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: BMP
otherformats: MD SVG EMF WORDML TEXT PS TIFF DOT PCL DOC FLATOPC DOCX DOCM DOTM ODT PDF GIF OTT EPUB DOTX XPS JPEG PNG RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="E-POSTA'yı BMP'ye Dönüştürmek için Java API" h2="Herhangi bir üçüncü taraf bağımlılığı kullanmadan şirket içi Java API'sini kullanarak EML'i BMP'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
E-posta dönüştürme, Java geliştiricilerinin [Aspose.Total for Java](https://products.aspose.com/total/java/) aracılığıyla herhangi bir Java J2SE, J2EE, J2ME uygulamasına entegre edebileceği güçlü bir özelliktir. Paket içinde iki API kullanarak, herhangi bir üçüncü taraf bağımlılığı olmadan E-posta E-postasını BMP'ye dönüştürebilirsiniz. İlk olarak, EML dosya biçimini HTML'ye dönüştürmek için Eml Manipulation API'sini [Aspose.Email for Java](https://products.aspose.com/email/java/) kullanabilirsiniz. İkinci olarak, Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak HTML'yi BMP'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EML'i BMP'ye Dönüştürme" %}}
1. [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) sınıfını kullanarak EML dosyasını açın
2. [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) kullanarak EML'i HTML'ye dönüştürün)) yöntem
3. HTML'yi [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak belgeyi BMP biçiminde kaydedin)) yöntemi ve BMP'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kullanmanız gerekir. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-formats-to-images.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}