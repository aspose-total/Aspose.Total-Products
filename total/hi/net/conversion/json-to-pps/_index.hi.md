---
title: .NET . के माध्यम से JSON फॉर्मेट को PPS में बदलें
description: माइक्रोसॉफ्ट पावरपॉइंट का उपयोग किए बिना जेएसओएन को ओडीपी में सी # में पार्स करें
url_ignore: /hi/net/conversion/json-to-pps/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPS
otherformats: PPS PPSX POWERPOINT POTM OTP PPTM PPSM PPT POT POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जेएसओएन प्रारूप को सी # के माध्यम से ओडीपी में कनवर्ट करें" h2="सी # एपीआई माइक्रोसॉफ्ट का उपयोग किए बिना जेएसओएन को ओडीपी में पार्स करने के लिए<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप किसी भी .NET, C#, ASP.NET और VB.NET एप्लिकेशन में JSON को PPS में दो सरल चरणों में बदल सकते हैं। सबसे पहले, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) का उपयोग करके, आप JSON को PPTX में पार्स कर सकते हैं। उसके बाद, [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) का उपयोग करके, आप PPTX को PPS में बदल सकते हैं। दोनों API [Aspose.Total for .NET](https://products.aspose.com/total/net/) पैकेज के अंतर्गत आते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जेएसओएन प्रारूप को सी # के माध्यम से ओडीपी में कनवर्ट करें" %}}
1. एक नया [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) ऑब्जेक्ट बनाएं और फ़ाइल से मान्य JSON डेटा पढ़ें
2. [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) वर्ग और [Save](https://reference.aspose.com/) का उपयोग करके कार्यपत्रक में JSON फ़ाइल आयात करें cells/net/aspose.cells.workbook/save/methods/4) इसे PPTX के रूप में
3. [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) वर्ग का उपयोग करके PPTX दस्तावेज़ लोड करें
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) विधि का उपयोग करके दस्तावेज़ को PPS प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ```Install-Package Aspose.Total``` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="लेआउट सेट करें और जेएसओएन प्रारूप को सी # के माध्यम से ओडीपी में कनवर्ट करें" %}}
JSON को PPS में पार्स करते समय, आप [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) का उपयोग करके अपने JSON प्रारूप के लिए लेआउट विकल्प भी सेट कर सकते हैं। यह आपको सरणी को तालिका के रूप में संसाधित करने, नल को अनदेखा करने, सरणी शीर्षक को अनदेखा करने, ऑब्जेक्ट शीर्षक को अनदेखा करने, स्ट्रिंग को संख्या या दिनांक में कनवर्ट करने, दिनांक और संख्या प्रारूप सेट करने और शीर्षक शैली सेट करने की अनुमति देता है। ये सभी विकल्प आपको अपनी आवश्यकताओं के अनुसार अपना डेटा प्रस्तुत करने की अनुमति देते हैं। निम्न कोड स्निपेट आपको दिखाता है कि लेआउट विकल्प कैसे सेट करें।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="वॉटरमार्क के साथ JSON फॉर्मेट को PPS में बदलें" %}}
एपीआई का उपयोग करके, आप JSON को वॉटरमार्क के साथ PPS में भी बदल सकते हैं। अपने PPS दस्तावेज़ में वॉटरमार्क जोड़ने के लिए, आप पहले JSON को PPTX में पार्स कर सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) वर्ग का उपयोग करके नई बनाई गई PPTX फ़ाइल लोड करें, मास्टर प्रस्तुति का चयन करें, आकार प्रकार का उपयोग करके जोड़ें AddAutoShape, और AddTextFrame का उपयोग करके वॉटरमार्क टेक्स्ट जोड़ें। वॉटरमार्क जोड़ने के बाद, आप दस्तावेज़ को ओडीपी में सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}