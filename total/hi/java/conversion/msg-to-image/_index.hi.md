---
title: जावा के माध्यम से ईमेल को बीएमपी में निर्यात करें
description: जावा एपीआई माइक्रोसॉफ्ट वर्ड या आउटलुक का उपयोग किए बिना ईमेल को बीएमपी में कनवर्ट करने के लिए
url_ignore: /hi/java/conversion/msg-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: DOCM PDF TIFF PCL GIF DOT SVG MD IMAGE DOTM PS JPEG DOTX TEXT EPUB DOCX EMF WORDML OTT FLATOPC DOC ODT RTF PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा एपीआई बीएमपी को ईमेल प्रस्तुत करने के लिए" h2="किसी तीसरे पक्ष की निर्भरता का उपयोग किए बिना ऑन-प्रिमाइसेस जावा एपीआई का उपयोग करके बीएमपी को ईमेल निर्यात करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
ईमेल रूपांतरण एक शक्तिशाली विशेषता है जिसे जावा डेवलपर्स [Aspose.Total for Java](https://products.aspose.com/total/java/) के माध्यम से किसी भी Java J2SE, J2EE, J2ME अनुप्रयोगों में एकीकृत कर सकते हैं। पैकेज के भीतर दो एपीआई का उपयोग करके आप ईमेल ईमेल को बीएमपी में बिना किसी तीसरे पक्ष की निर्भरता के परिवर्तित कर सकते हैं। सबसे पहले, आप MSG फ़ाइल स्वरूप को HTML में बदलने के लिए ईमेल मैनिपुलेशन API [Aspose.Email for Java](https://products.aspose.com/email/java/) का उपयोग कर सकते हैं। दूसरे, आप दस्तावेज़ प्रसंस्करण API [Aspose.Words for Java](https://products.aspose.com/words/java/) का उपयोग करके HTML को IMAGE में रेंडर कर सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MSG को IMAGE में कैसे बदलें" %}}
1. [MailMessage](https://reference.aspose.com/msg/java/com.aspose.msg/mailmessage) वर्ग का उपयोग करके MSG फ़ाइल खोलें
2. [save](https://reference.aspose.com/msg/java/com.aspose.msg/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions) का उपयोग करके MSG को HTML में बदलें)) तरीका
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके HTML लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके दस्तावेज़ को IMAGE प्रारूप में सहेजें)) विधि और बीएमपी को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आपको [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) आधारित प्रोजेक्ट से सीधे जावा के लिए Aspose.Total का उपयोग करना होगा। और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PNG
document.save("output.png", SaveFormat.PNG);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-png/" name="MSG सेवा PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-doc/" name="MSG सेवा DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-ott/" name="MSG सेवा OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-odt/" name="MSG सेवा ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-wordml/" name="MSG सेवा WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-dotx/" name="MSG सेवा DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-svg/" name="MSG सेवा SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-docx/" name="MSG सेवा DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-epub/" name="MSG सेवा EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-text/" name="MSG सेवा TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-xps/" name="MSG सेवा XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-ps/" name="MSG सेवा PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-flatopc/" name="MSG सेवा FLAसेवाPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-docm/" name="MSG सेवा DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-jpeg/" name="MSG सेवा JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-tiff/" name="MSG सेवा TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-dot/" name="MSG सेवा DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-emf/" name="MSG सेवा EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-rtf/" name="MSG सेवा RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-gif/" name="MSG सेवा GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-pcl/" name="MSG सेवा PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-dotm/" name="MSG सेवा DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-md/" name="MSG सेवा MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-pdf/" name="MSG सेवा PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}