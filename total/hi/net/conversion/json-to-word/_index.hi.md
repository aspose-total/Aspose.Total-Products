---
title: .NET के माध्यम से JSON फॉर्मेट को WORD में बदलें
description: माइक्रोसॉफ्ट वर्ड का उपयोग किए बिना जेएसओएन को सी # में सीएचएम में पार्स करें
url: /hi/net/conversion/json-to-word/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOC
otherformats: DOC MOBI DOT ODT WORDML DOTX FLATOPC EPUB DOCM OTT PS RTF WORD PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जेएसओएन प्रारूप को सी # के माध्यम से सीएचएम में कनवर्ट करें" h2="सी#एपीआई माइक्रोसॉफ्ट<sup>&reg;</sup> Word का उपयोग किए बिना JSON को WORD में पार्स करने के लिए" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) का उपयोग करके आप किसी भी .NET, C#, ASP.NET और VB.NET एप्लिकेशन में JSON को WORD में पार्स कर सकते हैं। कदम। सबसे पहले, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) का उपयोग करके, आप JSON को PDF में निर्यात कर सकते हैं। उसके बाद, [Aspose.Words for .NET](https://products.aspose.com/words/net/) का उपयोग करके, आप PDF को WORD में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जेएसओएन प्रारूप को सी # के माध्यम से सीएचएम में कनवर्ट करें" %}}
1. एक नया [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) ऑब्जेक्ट बनाएं और फ़ाइल से मान्य JSON डेटा पढ़ें
2. [JsonUtility](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility) वर्ग और [Save](https://apireference.aspose.com/) का उपयोग करके कार्यपत्रक में JSON फ़ाइल आयात करें cells/net/aspose.cells.workbook/save/methods/4) इसे PDF के रूप में
3. [Document](https://apireference.aspose.com/words/net/aspose.words/document) वर्ग का उपयोग करके पीडीएफ दस्तावेज़ लोड करें
4. [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3) विधि का उपयोग करके दस्तावेज़ को WORD प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ```Install-Package Aspose.Total``` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="लेआउट सेट करें और JSON प्रारूप को C# के माध्यम से WORD में बदलें" %}}
JSON को WORD में पार्स करते समय, आप [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) का उपयोग करके अपने JSON के लिए लेआउट विकल्प भी सेट कर सकते हैं। यह आपको सरणी को तालिका के रूप में संसाधित करने, नल को अनदेखा करने, सरणी शीर्षक को अनदेखा करने, ऑब्जेक्ट शीर्षक को अनदेखा करने, स्ट्रिंग को संख्या या दिनांक में कनवर्ट करने, दिनांक और संख्या प्रारूप सेट करने और शीर्षक शैली सेट करने की अनुमति देता है। ये सभी विकल्प आपको अपनी आवश्यकताओं के अनुसार अपना डेटा प्रस्तुत करने की अनुमति देते हैं। निम्न कोड स्निपेट आपको दिखाता है कि लेआउट विकल्प कैसे सेट करें।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="पार्स JSON प्रारूप वॉटरमार्क के साथ सीएचएम करने के लिए" %}}
एपीआई का उपयोग करके, आप JSON को वॉटरमार्क के साथ WORD में भी बदल सकते हैं। अपने WORD दस्तावेज़ में वॉटरमार्क जोड़ने के लिए, आप पहले JSON फ़ाइल को PDF में पार्स कर सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, [Document](https://apireference.aspose.com/words/net/aspose.words/document) वर्ग का उपयोग करके नई बनाई गई पीडीएफ फाइल को लोड करें, TextWatermarkOptions का एक उदाहरण बनाएं और इसके गुण सेट करें , वॉटरमार्क पर कॉल करें। सेटटेक्स्ट विधि और वॉटरमार्क टेक्स्ट और टेक्स्टवाटरमार्कऑप्शन का ऑब्जेक्ट पास करें। वॉटरमार्क जोड़ने के बाद, आप दस्तावेज़ को सीएचएम में सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-ott/" name="JSON सेवा OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-flatopc/" name="JSON सेवा FLAसेवाPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-ps/" name="JSON सेवा PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-dotx/" name="JSON सेवा DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-rtf/" name="JSON सेवा RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-wordml/" name="JSON सेवा WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-odt/" name="JSON सेवा ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-word/" name="JSON सेवा WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-epub/" name="JSON सेवा EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-doc/" name="JSON सेवा DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-dot/" name="JSON सेवा DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-pcl/" name="JSON सेवा PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-mobi/" name="JSON सेवा MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-docm/" name="JSON सेवा DOCM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}