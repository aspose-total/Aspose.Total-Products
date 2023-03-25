---
title: जावा के माध्यम से JSON प्रारूप को POTM में बदलें
description: Microsoft PowerPoint का उपयोग किए बिना जावा में JSON को POTM में पार्स करें
url_ignore: /hi/java/conversion/json-to-potm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POTM
otherformats: POTM PPT PPSM POWERPOINT OTP POTX POT PPSX PPS PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से JSON प्रारूप को POTM में बदलें" h2="Microsoft<sup>&reg;</sup> PowerPoint का उपयोग किए बिना JSON प्रारूप को POTM में पार्स करने के लिए Java API" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) का उपयोग करके, आप दो आसान चरणों में किसी भी जावा एप्लिकेशन के भीतर JSON प्रारूप को POTM में बदल सकते हैं। सबसे पहले, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) का उपयोग करके, आप JSON को PPTX में पार्स कर सकते हैं। उसके बाद, [Aspose.Slides for Java](https://products.aspose.com/slides/java/) का उपयोग करके, आप PPTX को POTM में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से JSON प्रारूप को POTM में बदलें" %}}
1. एक नया [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ऑब्जेक्ट बनाएं और JSON फाइल खोलें
2. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) का उपयोग करके JSON को PPTX के रूप में सेव करें। ) तरीका
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके PPTX दस्तावेज़ लोड करें
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) पद्धति का उपयोग करके दस्तावेज़ को POTM प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://releases.aspose.com/total/java/) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
इसके अलावा, एपीआई आपको निर्दिष्ट लेआउट विकल्पों के साथ JSON को POTM में पार्स करने की अनुमति देता है। लेआउट विकल्पों को निर्दिष्ट करने के लिए, आप [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) वर्ग का उपयोग कर सकते हैं। यह आपको एक सरणी को तालिका के रूप में संसाधित करने, नल को अनदेखा करने, सरणी शीर्षक को अनदेखा करने, ऑब्जेक्ट शीर्षक को अनदेखा करने, स्ट्रिंग को संख्या या दिनांक में बदलने, दिनांक और संख्या प्रारूप सेट करने और शीर्षक शैली सेट करने की अनुमति देता है। ये सभी विकल्प आपको अपनी आवश्यकताओं के अनुसार अपना डेटा प्रस्तुत करने की अनुमति देते हैं। निम्न कोड स्निपेट आपको दिखाता है कि लेआउट विकल्प कैसे सेट करें।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से लेआउट सेट करें और JSON प्रारूप को POTM में बदलें" %}}
एपीआई का उपयोग करके, आप JSON को वॉटरमार्क के साथ POTM में भी बदल सकते हैं। अपने POTM दस्तावेज़ में वॉटरमार्क जोड़ने के लिए, आप पहले JSON को PPTX में पार्स कर सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके नई बनाई गई PPTX फ़ाइल लोड करें, सभी स्लाइडों के माध्यम से लूप करें, टेक्स्ट जोड़ें AddTextFrame का उपयोग करके, सभी प्रासंगिक विकल्प जैसे रंग, भरण टाइप और बहुत कुछ सेट करें और दस्तावेज़ को POTM में सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}