---
title: जावा के माध्यम से एंड्रॉइड में जेएसओएन प्रारूप को ओडीपी में कनवर्ट करें
description: Microsoft PowerPoint का उपयोग किए बिना Android अनुप्रयोगों में JSON को POWERPOINT में पार्स करें

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POWERPOINT
otherformats: POT PPSM OTP ODP PPTM PPT PPS PPSX POTM POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android में JSON फॉर्मेट को POWERPOINT में बदलें" h2="Microsoft<sup>&reg;</sup> PowerPoint का उपयोग किए बिना Android अनुप्रयोगों में JSON प्रारूप को POWERPOINT में पार्स करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप दो चरणों वाली प्रक्रिया में अपने Android एप्लिकेशन में JSON प्रारूप को POWERPOINT में बदल सकते हैं। सबसे पहले, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) का उपयोग करके, आप JSON को PPTX में पार्स कर सकते हैं। उसके बाद, [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) का उपयोग करके, आप PPTX को POWERPOINT में बदल सकते हैं। दोनों एपीआई [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) पैकेज के तहत आते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android में JSON फॉर्मेट को POWERPOINT में बदलें" %}}
1. एक नया [वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ऑब्जेक्ट बनाएं और JSON फाइल खोलें
2. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) का उपयोग करके JSON को PPTX के रूप में सेव करें। ) तरीका
3. [प्रस्तुति](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके PPTX दस्तावेज़ लोड करें
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) पद्धति का उपयोग करके दस्तावेज़ को POWERPOINT प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://releases.aspose.com/total/java/) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और अपने ऐप में पुस्तकालय स्थापित करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="एंड्रॉइड एप्लिकेशन में लेआउट सेट करें और JSON फॉर्मेट को POWERPOINT में बदलें" %}}
इसके अलावा, एपीआई आपको निर्दिष्ट लेआउट विकल्पों के साथ JSON को POWERPOINT में पार्स करने की अनुमति देता है। लेआउट विकल्प निर्दिष्ट करने के लिए, आप [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) वर्ग का उपयोग कर सकते हैं। यह आपको एक सरणी को तालिका के रूप में संसाधित करने, नल को अनदेखा करने, सरणी शीर्षक को अनदेखा करने, ऑब्जेक्ट शीर्षक को अनदेखा करने, स्ट्रिंग को संख्या या दिनांक में बदलने, दिनांक और संख्या प्रारूप सेट करने और शीर्षक शैली सेट करने की अनुमति देता है। ये सभी विकल्प आपको अपनी आवश्यकताओं के अनुसार अपना डेटा प्रस्तुत करने की अनुमति देते हैं। निम्न कोड स्निपेट आपको दिखाता है कि लेआउट विकल्प कैसे सेट करें।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एंड्रॉइड में वॉटरमार्क के साथ जेएसओएन प्रारूप को ओडीपी में कनवर्ट करें" %}}
एपीआई का उपयोग करके, आप JSON को वॉटरमार्क के साथ POWERPOINT में भी बदल सकते हैं। अपने POWERPOINT दस्तावेज़ में वॉटरमार्क जोड़ने के लिए, आप पहले JSON को PPTX में पार्स कर सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, [प्रस्तुति](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके नई बनाई गई PPTX फ़ाइल लोड करें, सभी स्लाइडों के माध्यम से लूप करें, टेक्स्ट जोड़ें AddTextFrame का उपयोग करके, सभी प्रासंगिक विकल्प जैसे रंग, भरण टाइप और बहुत कुछ सेट करें और दस्तावेज़ को POWERPOINT में सहेज सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}