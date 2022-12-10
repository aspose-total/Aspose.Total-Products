---
title: जावा के माध्यम से एंड्रॉइड में जेएसओएन प्रारूप को सीएचएम में कनवर्ट करें
description: माइक्रोसॉफ्ट वर्ड का उपयोग किए बिना जावा में जेएसओएन को सीएचएम में पार्स करें

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOTX
otherformats: ODT DOCM DOT RTF PCL FLATOPC CHM OTT WORDML WORD DOC EPUB MOBI PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android एप्लिकेशन में JSON फॉर्मेट को DOTX में बदलें" h2="Microsoft<sup>&reg;</sup> Word का उपयोग किए बिना Android एप्लिकेशन में JSON को DOTX में पार्स करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप अपने Android एप्लिकेशन में JSON को DOTX में दो-चरणीय प्रक्रिया में बदल सकते हैं। सबसे पहले, पावरफुल स्प्रैडशीट प्रोसेसिंग API [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) का उपयोग करके आप JSON को PDF में पार्स कर सकते हैं। दूसरे चरण में, आप वर्ड प्रोसेसिंग एपीआई [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) का उपयोग करके पीडीएफ को सीएचएम में बदल सकते हैं। दोनों API [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) उत्पाद परिवार के अंतर्गत आते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से एंड्रॉइड में जेएसओएन प्रारूप को सीएचएम में कनवर्ट करें" %}}
1. एक नया [वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ऑब्जेक्ट बनाएं और फ़ाइल से मान्य JSON डेटा पढ़ें
2. [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) वर्ग और [Save](https://reference.aspose.com/) का उपयोग करके कार्यपत्रक में JSON फ़ाइल आयात करें cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) इसे PDF के रूप में
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके पीडीएफ दस्तावेज़ लोड करें
4. दस्तावेज़ को [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) का उपयोग करके सीएचएम प्रारूप में सहेजें )) तरीका
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://releases.aspose.com/total/java/) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और अपने ऐप में पुस्तकालय स्थापित करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एंड्रॉइड में लेआउट सेट करें और JSON फॉर्मेट को DOTX में बदलें" %}}
इसके अलावा, एपीआई आपको [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) का उपयोग करके JSON को DOTX में पार्स करते समय अपने JSON प्रारूप के लिए लेआउट विकल्प सेट करने की अनुमति देता है। यह आपको सरणी को तालिका के रूप में संसाधित करने, नल को अनदेखा करने, सरणी शीर्षक को अनदेखा करने, ऑब्जेक्ट शीर्षक को अनदेखा करने, स्ट्रिंग को संख्या या दिनांक में कनवर्ट करने, दिनांक और संख्या प्रारूप सेट करने और शीर्षक शैली सेट करने की अनुमति देता है। ये सभी विकल्प आपको अपनी आवश्यकताओं के अनुसार अपना डेटा प्रस्तुत करने की अनुमति देते हैं। निम्न कोड स्निपेट आपको दिखाता है कि लेआउट विकल्प कैसे सेट करें।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एंड्रॉइड में वॉटरमार्क के साथ जेएसओएन प्रारूप को सीएचएम में कनवर्ट करें" %}}
एपीआई का उपयोग करके, आप JSON को वॉटरमार्क के साथ DOTX में भी बदल सकते हैं। अपने DOTX दस्तावेज़ में वॉटरमार्क जोड़ने के लिए, आप पहले JSON फ़ाइल को PDF में पार्स कर सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके नई बनाई गई PDF फ़ाइल लोड करें, TextWatermarkOptions का एक उदाहरण बनाएं और सेट करें इसके गुण, Watermark.setText विधि को कॉल करें और वॉटरमार्क टेक्स्ट और TextWatermarkOptions का ऑब्जेक्ट पास करें। वॉटरमार्क जोड़ने के बाद, आप दस्तावेज़ को सीएचएम में सहेज सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-odt/" name="JSON प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-docm/" name="JSON प्रति DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-dot/" name="JSON प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-rtf/" name="JSON प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-pcl/" name="JSON प्रति PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-flatopc/" name="JSON प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-dotx/" name="JSON प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-ott/" name="JSON प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-wordml/" name="JSON प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-word/" name="JSON प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-doc/" name="JSON प्रति DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-epub/" name="JSON प्रति EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-mobi/" name="JSON प्रति MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/json-to-ps/" name="JSON प्रति PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}