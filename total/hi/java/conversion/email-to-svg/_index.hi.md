---
title: जावा के माध्यम से ईमेल को बीएमपी में निर्यात करें
description: जावा एपीआई माइक्रोसॉफ्ट वर्ड या आउटलुक का उपयोग किए बिना ईमेल को बीएमपी में कनवर्ट करने के लिए
url_ignore: /hi/java/conversion/email-to-svg/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: SVG
otherformats: EMF PDF DOC PCL DOTX DOCM FLATOPC DOTM OTT PNG JPEG DOT PS RTF DOCX SVG TIFF GIF EPUB XPS MD WORDML TEXT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा एपीआई बीएमपी को ईमेल प्रस्तुत करने के लिए" h2="किसी तीसरे पक्ष की निर्भरता का उपयोग किए बिना ऑन-प्रिमाइसेस जावा एपीआई का उपयोग करके बीएमपी को ईमेल निर्यात करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
ईमेल रूपांतरण एक शक्तिशाली विशेषता है जिसे जावा डेवलपर्स [Aspose.Total for Java](https://products.aspose.com/total/java/) के माध्यम से किसी भी Java J2SE, J2EE, J2ME अनुप्रयोगों में एकीकृत कर सकते हैं। पैकेज के भीतर दो एपीआई का उपयोग करके आप ईमेल ईमेल को बीएमपी में बिना किसी तीसरे पक्ष की निर्भरता के परिवर्तित कर सकते हैं। सबसे पहले, आप EMAIL फ़ाइल स्वरूप को HTML में बदलने के लिए ईमेल मैनिपुलेशन API [Aspose.Email for Java](https://products.aspose.com/email/java/) का उपयोग कर सकते हैं। दूसरे, आप दस्तावेज़ प्रसंस्करण API [Aspose.Words for Java](https://products.aspose.com/words/java/) का उपयोग करके HTML को SVG में रेंडर कर सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAIL को SVG में कैसे बदलें" %}}
1. [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage) वर्ग का उपयोग करके EMAIL फ़ाइल खोलें
2. [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) का उपयोग करके EMAIL को HTML में बदलें तरीका
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके HTML लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके दस्तावेज़ को SVG प्रारूप में सहेजें)) विधि और बीएमपी को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आपको [Maven](https://releases.aspose.com/total/java/) आधारित प्रोजेक्ट से सीधे जावा के लिए Aspose.Total का उपयोग करना होगा। और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.SVG
document.save("output.svg", SaveFormat.SVG);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}