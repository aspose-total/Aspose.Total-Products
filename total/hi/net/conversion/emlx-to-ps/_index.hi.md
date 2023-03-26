---
title: सी # एपीआई बीएमपी को ईमेल निर्यात करने के लिए
description: .NET पर Microsoft Word या Outlook का उपयोग किए बिना EMLX को PS में बदलें
url_ignore: /hi/net/conversion/emlx-to-ps/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PS
otherformats: XPS PNG DOTX EMF PS WORDML DOTM ODT FLATOPC RTF DOC JPEG OTT EPUB PCL PDF DOCX TEXT DOCM MD DOT GIF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET . के माध्यम से बीएमपी को ईमेल निर्यात करें" h2="वर्ड या आउटलुक का उपयोग किए बिना विंडोज़, मैकओएस और लिनक्स पर बीएमपी को ईमेल प्रस्तुत करने के लिए .NET एपीआई" >}}

{{% blocks/products/pf/feature-page-summary %}}
यदि आप एक .NET डेवलपर हैं, जो अपने एप्लिकेशन के अंदर EMLX को PS रूपांतरण सुविधाओं में जोड़ना चाहते हैं, तो [Aspose.Total for .NET](https://products.aspose.com/total/net/) फ़ाइल प्रारूप में हेरफेर API एक तरीका है। आगे। [Aspose.Email for .NET](https://products.aspose.com/email/net/) का उपयोग करके, आप EMLX फ़ाइल स्वरूप को HTML में बदल सकते हैं। उसके बाद, [Aspose.Words for .NET](https://products.aspose.com/words/net/) का उपयोग करके, आप HTML को PS में रेंडर कर सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी # एपीआई ईमेल को बीएमपी में कनवर्ट करने के लिए" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) वर्ग का उपयोग करके EMLX फ़ाइल खोलें
2. [MailMessage.Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) विधि का उपयोग करके EMLX को HTML में बदलें
3. [Document](https://reference.aspose.com/words/net/aspose.words/document) वर्ग का उपयोग करके HTML लोड करें
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) विधि का उपयोग करके दस्तावेज़ को PS प्रारूप में सहेजें और Ps को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ```Install-Package Aspose.Total``` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.ps", SaveFormat.Ps); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET के माध्यम से ईमेल फ़ाइल को पार्स करें" %}}
EMLX को PS में बदलने से पहले, यदि आप यह सुनिश्चित करना चाहते हैं कि आप सही ईमेल परिवर्तित कर रहे हैं, तो आप EMLX दस्तावेज़ लोड कर सकते हैं, उसे पार्स कर सकते हैं और अपनी वांछित संपत्ति पर एक नज़र डाल सकते हैं। [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) वर्ग [Aspose.Email for .NET](https://products.aspose.com/email) का उपयोग करके /net/) एपीआई, आप प्रेषक और प्राप्तकर्ताओं की जानकारी प्राप्त कर सकते हैं। उदाहरण के लिए, आप [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) प्रॉपर्टी का इस्तेमाल करके कन्वर्ज़न के लिए किसी खास ईमेल भेजने वाले की जांच कर सकते हैं।  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET के माध्यम से PS दस्तावेज़ संपादन प्रतिबंधित करें" %}}
दस्तावेज़ को EMLX से PS में सहेजते समय, आपको अपने आउटपुट दस्तावेज़ को सुरक्षित रखने की आवश्यकता हो सकती है। कभी-कभी आपको किसी दस्तावेज़ को संपादित करने की क्षमता को सीमित करना पड़ सकता है और इसके साथ केवल कुछ क्रियाओं की अनुमति देनी पड़ सकती है। यह अन्य लोगों को आपके दस्तावेज़ में संवेदनशील और गोपनीय जानकारी को संपादित करने से रोकने के लिए उपयोगी हो सकता है। [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, आपको [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype)  का उपयोग करके सामग्री को प्रतिबंधित करने के तरीके को नियंत्रित करने में सक्षम बनाता है  एन्यूमरेशन पैरामीटर। आप कोड की निम्नलिखित पंक्तियों का उपयोग करके अपने दस्तावेज़ को केवल-पढ़ने के लिए सेट कर सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ps", SaveFormat.Ps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}