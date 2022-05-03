---
title: जावा के माध्यम से DOCM को PPSM में बदलें
description: जावा एपीआई माइक्रोसॉफ्ट वर्ड या पावरपॉइंट का उपयोग किए बिना डीओसी को ओडीपी में निर्यात करने के लिए
url: /hi/java/conversion/docm-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: PPSM
otherformats: POT PPSM POWERPOINT PPTX PPTM PPS POTM PPSX POTX PPT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से DOCM को PPSM में बदलें" h2="Microsoft<sup>&reg;</sup> PowerPoint या Word का उपयोग किए बिना किसी भी Java J2SE, J2EE, J2ME अनुप्रयोगों में ऑन-प्रिमाइसेस Java API का उपयोग करके DOCM से PPSM रूपांतरण" >}}
{{% blocks/products/pf/feature-page-summary %}}
कई बार डेवलपर्स को DOCM फाइल को प्रोग्रामेटिक रूप से PPSM में कनवर्ट करना पड़ता है। फ़ाइल ऑटोमेशन जावा लाइब्रेरी [Aspose.Total for Java](https://products.aspose.com/total/java/) का उपयोग करके आप कुछ आसान चरणों में रेंडरिंग प्रक्रिया को स्वचालित कर सकते हैं। आप [Aspose.Words for Java](https://products.aspose.com/words/java/) का उपयोग करके अपनी DOCM फ़ाइल लोड कर सकते हैं और इसे HTML में बदल सकते हैं। उसके बाद शक्तिशाली पावरपॉइंट मैनिपुलेशन Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) का उपयोग करके आप एक नया प्रेजेंटेशन बना सकते हैं, उसमें HTML सामग्री लिख सकते हैं और इसे PPSM के रूप में सहेज सकते हैं। .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से DOCM को PPSM में कैसे बदलें" %}}
1. [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके DOCM फ़ाइल खोलें
2. [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके DOCM फ़ाइल को HTML में बदलें)) तरीका
3. एक नया [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) ऑब्जेक्ट प्रारंभ करें
5. BufferedReader का उपयोग करके HTML फ़ाइल से सामग्री निकालें और अपनी प्रस्तुति फ़ाइल में सामग्री लिखें
6. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) पद्धति का उपयोग करके दस्तावेज़ को PPSM में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
DOCM से PPSM फ़ाइल रूपांतरण के लिए, आप आसानी से सीधे [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose से जावा के लिए Aspose.Total का उपयोग कर सकते हैं। /aspose-total) आधारित परियोजना और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docm-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
एपीआई आपको पासवर्ड से सुरक्षित डीओसी दस्तावेजों को ओडीपी में बदलने की भी अनुमति देता है। यदि आपका इनपुट डीओसी दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप पासवर्ड का उपयोग किए बिना इसे ओडीपी प्रारूप में परिवर्तित नहीं कर सकते। एन्क्रिप्टेड दस्तावेज़ खोलने के लिए आप LoadOptions ऑब्जेक्ट में सही पासवर्ड सेट कर सकते हैं और इसे दस्तावेज़ निर्माता को पास कर सकते हैं।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docm-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-ppsm/" name="DOCM सेवा PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-pot/" name="DOCM सेवा POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-powerpoint/" name="DOCM सेवा POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-pptx/" name="DOCM सेवा PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-potx/" name="DOCM सेवा POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-pptm/" name="DOCM सेवा PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-potm/" name="DOCM सेवा POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-pps/" name="DOCM सेवा PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-ppsx/" name="DOCM सेवा PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-ppt/" name="DOCM सेवा PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-csv/" name="DOCM सेवा CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-dif/" name="DOCM सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-fods/" name="DOCM सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-ods/" name="DOCM सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-sxc/" name="DOCM सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-tsv/" name="DOCM सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-xlam/" name="DOCM सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-xltm/" name="DOCM सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-excel/" name="DOCM सेवा EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-xls/" name="DOCM सेवा XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-xlsb/" name="DOCM सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-xlsm/" name="DOCM सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-xlsx/" name="DOCM सेवा XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-xlt/" name="DOCM सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-xltm/" name="DOCM सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docm-to-xltx/" name="DOCM सेवा XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}