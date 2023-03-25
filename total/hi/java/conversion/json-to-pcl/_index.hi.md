---
title: जावा के माध्यम से JSON प्रारूप को PCL में बदलें
description: माइक्रोसॉफ्ट वर्ड का उपयोग किए बिना जावा में जेएसओएन को सीएचएम में पार्स करें
url_ignore: /hi/java/conversion/json-to-pcl/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PCL
otherformats: WORD EPUB ODT RTF DOT FLATOPC PCL DOCM DOC OTT PS DOTX MOBI WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से JSON प्रारूप को PCL में बदलें" h2="Microsoft<sup>&reg;</sup> Word का उपयोग किए बिना JSON को PCL में पार्स करने के लिए जावा एपीआई के आधार पर" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) का उपयोग करके आप दो चरणों वाली प्रक्रिया में अपने जावा एप्लिकेशन में JSON को PCL में बदल सकते हैं। सबसे पहले, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) का उपयोग करके आप JSON को PDF में पार्स कर सकते हैं। दूसरे चरण में, आप Word संसाधन API [Aspose.Words for Java](https://products.aspose.com/words/java/) का उपयोग करके PDF को PCL में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से JSON प्रारूप को PCL में बदलें" %}}
1. एक नई [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ऑब्जेक्ट बनाएं और फ़ाइल से मान्य JSON डेटा पढ़ें
2. [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) वर्ग और [Save](https://reference.aspose.com/) का उपयोग करके कार्यपत्रक में JSON फ़ाइल आयात करें cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) इसे PDF के रूप में
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके पीडीएफ दस्तावेज़ लोड करें
4. दस्तावेज़ को [MailMessage.Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके PCL प्रारूप में सहेजें)) तरीका
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://releases.aspose.com/total/java/) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
इसके अलावा, एपीआई आपको [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) का उपयोग करके JSON को PCL में पार्स करते समय अपने JSON के लिए लेआउट विकल्प सेट करने की अनुमति देता है। यह आपको सरणी को तालिका के रूप में संसाधित करने, नल को अनदेखा करने, सरणी शीर्षक को अनदेखा करने, ऑब्जेक्ट शीर्षक को अनदेखा करने, स्ट्रिंग को संख्या या दिनांक में कनवर्ट करने, दिनांक और संख्या प्रारूप सेट करने और शीर्षक शैली सेट करने की अनुमति देता है। ये सभी विकल्प आपको अपनी आवश्यकताओं के अनुसार अपना डेटा प्रस्तुत करने की अनुमति देते हैं। निम्न कोड स्निपेट आपको दिखाता है कि लेआउट विकल्प कैसे सेट करें।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से लेआउट सेट करें और JSON प्रारूप को PCL में बदलें" %}}
एपीआई का उपयोग करके, आप जेएसओएन को सीएचएम को वॉटरमार्क के साथ भी पार्स कर सकते हैं। अपने PCL दस्तावेज़ में वॉटरमार्क जोड़ने के लिए, आप पहले JSON फ़ाइल को PDF में बदल सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके नई बनाई गई PDF फ़ाइल लोड करें, TextWatermarkOptions का एक उदाहरण बनाएं और सेट करें इसके गुण, Watermark.setText विधि को कॉल करें और वॉटरमार्क टेक्स्ट और TextWatermarkOptions का ऑब्जेक्ट पास करें। वॉटरमार्क जोड़ने के बाद, आप दस्तावेज़ को सीएचएम में सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}