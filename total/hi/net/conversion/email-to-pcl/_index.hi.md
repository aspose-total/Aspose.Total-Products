---
title: सी # एपीआई बीएमपी को ईमेल निर्यात करने के लिए
description: .NET पर Microsoft Word या Outlook का उपयोग किए बिना EMAIL को PCL में बदलें
url: /hi/net/conversion/email-to-pcl/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PCL
otherformats: DOTX EPUB ODT RTF GIF DOCX FLATOPC DOC TIFF JPEG EMF SVG PS PCL MD DOT PDF OTT PNG TEXT DOCM XPS WORDML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET . के माध्यम से बीएमपी को ईमेल निर्यात करें" h2="वर्ड या आउटलुक का उपयोग किए बिना विंडोज़, मैकओएस और लिनक्स पर बीएमपी को ईमेल प्रस्तुत करने के लिए .NET एपीआई" >}}

{{% blocks/products/pf/feature-page-summary %}}
यदि आप एक .NET डेवलपर हैं, जो अपने एप्लिकेशन के अंदर EMAIL को PCL रूपांतरण सुविधाओं में जोड़ना चाहते हैं, तो [Aspose.Total for .NET](https://products.aspose.com/total/net/) फ़ाइल प्रारूप में हेरफेर API एक तरीका है। आगे। [Aspose.Email for .NET](https://products.aspose.com/email/net/) का उपयोग करके, आप EMAIL फ़ाइल स्वरूप को HTML में बदल सकते हैं। उसके बाद, [Aspose.Words for .NET](https://products.aspose.com/words/net/) का उपयोग करके, आप HTML को PCL में रेंडर कर सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी # एपीआई ईमेल को बीएमपी में कनवर्ट करने के लिए" %}}
1. [MailMessage](https://apireference.aspose.com/email/net/aspose.email/mailmessage) वर्ग का उपयोग करके EMAIL फ़ाइल खोलें
2. [MailMessage.Save](https://apireference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) विधि का उपयोग करके EMAIL को HTML में बदलें
3. [Document](https://apireference.aspose.com/words/net/aspose.words/document) वर्ग का उपयोग करके HTML लोड करें
4. [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) विधि का उपयोग करके दस्तावेज़ को PCL प्रारूप में सहेजें और Pcl को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ```Install-Package Aspose.Total``` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.pcl", SaveFormat.Pcl); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET के माध्यम से ईमेल फ़ाइल को पार्स करें" %}}
EMAIL को PCL में बदलने से पहले, यदि आप यह सुनिश्चित करना चाहते हैं कि आप सही ईमेल परिवर्तित कर रहे हैं, तो आप EMAIL दस्तावेज़ लोड कर सकते हैं, उसे पार्स कर सकते हैं और अपनी वांछित संपत्ति पर एक नज़र डाल सकते हैं। [MapiMessage](https://apireference.aspose.com/email/net/aspose.email.mapi/mapimessage) वर्ग [Aspose.Email for .NET](https://products.aspose.com/email) का उपयोग करके /net/) एपीआई, आप प्रेषक और प्राप्तकर्ताओं की जानकारी प्राप्त कर सकते हैं। उदाहरण के लिए, आप [SenderName](https://apireference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) प्रॉपर्टी का इस्तेमाल करके कन्वर्ज़न के लिए किसी खास ईमेल भेजने वाले की जांच कर सकते हैं।  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET के माध्यम से PCL दस्तावेज़ संपादन प्रतिबंधित करें" %}}
दस्तावेज़ को EMAIL से PCL में सहेजते समय, आपको अपने आउटपुट दस्तावेज़ को सुरक्षित रखने की आवश्यकता हो सकती है। कभी-कभी आपको किसी दस्तावेज़ को संपादित करने की क्षमता को सीमित करना पड़ सकता है और इसके साथ केवल कुछ क्रियाओं की अनुमति देनी पड़ सकती है। यह अन्य लोगों को आपके दस्तावेज़ में संवेदनशील और गोपनीय जानकारी को संपादित करने से रोकने के लिए उपयोगी हो सकता है। [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, आपको [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype)  का उपयोग करके सामग्री को प्रतिबंधित करने के तरीके को नियंत्रित करने में सक्षम बनाता है  एन्यूमरेशन पैरामीटर। आप कोड की निम्नलिखित पंक्तियों का उपयोग करके अपने दस्तावेज़ को केवल-पढ़ने के लिए सेट कर सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-pcl/" name="एमएसजी टू पीसीएल" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-pdf/" name="पीडीएफ के लिए एमएसजी" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-dot/" name="एमएसजी टू डॉट" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-flatopc/" name="MSG से FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-jpeg/" name="जेपीईजी के लिए एमएसजी" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-png/" name="पीएनजी के लिए एमएसजी" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-rtf/" name="एमएसजी से आरटीएफ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-tiff/" name="एमएसजी टू टीआईएफएफ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-docm/" name="DOCM करने के लिए MSG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-ps/" name="एमएसजी टू पीएस" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-gif/" name="जीआईएफ के लिए एमएसजी" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-xps/" name="एमएसजी टू एक्सपीएस" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-odt/" name="एमएसजी टू ओडीटी" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-docx/" name="एमएसजी टू डॉक्स" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-doc/" name="डॉक्टर को एमएसजी" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-wordml/" name="एमएसजी टू वर्डएमएल" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-svg/" name="एमएसजी से एसवीजी" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-epub/" name="EPUB करने के लिए एमएसजी" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-md/" name="एमएसजी से एमडी" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-emf/" name="ईएमएफ के लिए एमएसजी" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-dotm/" name="एमएसजी टू डॉट" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-ott/" name="एमएसजी टू ओटीटी" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-dotx/" name="एमएसजी टू डॉटएक्स" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/msg-to-text/" name="पाठ के लिए एमएसजी" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}