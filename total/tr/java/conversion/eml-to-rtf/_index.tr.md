---
title: EML'i Java aracılığıyla RTF'ye aktarın
description: Microsoft Word veya Outlook kullanmadan EML'i RTF'ye Dönüştürmek için Java API
url_ignore: /tr/java/conversion/eml-to-rtf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: RTF
otherformats: RTF PNG DOC TEXT TIFF EMF XPS DOTX DOTM ODT DOT GIF SVG EPUB JPEG OTT FLATOPC PS DOCM PDF WORDML MD PCL DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="E-POSTA'yı RTF'ye Dönüştürmek için Java API" h2="Herhangi bir üçüncü taraf bağımlılığı kullanmadan şirket içi Java API'sini kullanarak EML'i RTF'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
E-posta dönüştürme, Java geliştiricilerinin [Aspose.Total for Java](https://products.aspose.com/total/java/) aracılığıyla herhangi bir Java J2SE, J2EE, J2ME uygulamasına entegre edebileceği güçlü bir özelliktir. Paket içinde iki API kullanarak, herhangi bir üçüncü taraf bağımlılığı olmadan E-posta E-postasını RTF'ye dönüştürebilirsiniz. İlk olarak, EML dosya biçimini HTML'ye dönüştürmek için Eml Manipulation API'sini [Aspose.Email for Java](https://products.aspose.com/email/java/) kullanabilirsiniz. İkinci olarak, Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/) kullanarak HTML'yi RTF'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EML'i RTF'ye Dönüştürme" %}}
1. [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) sınıfını kullanarak EML dosyasını açın
2. [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) kullanarak EML'i HTML'ye dönüştürün)) yöntem
3. HTML'yi [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) sınıfını kullanarak yükleyin
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) kullanarak belgeyi RTF biçiminde kaydedin)) yöntemi ve RTF'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kullanmanız gerekir. ve pom.xml'inize kitaplıkları dahil edin.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.RTF
document.save("output.rtf", SaveFormat.RTF);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}