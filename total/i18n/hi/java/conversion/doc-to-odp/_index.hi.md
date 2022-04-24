---
title: जावा के माध्यम से DOC को ODP में बदलें
description: जावा एपीआई माइक्रोसॉफ्ट वर्ड या पावरपॉइंट का उपयोग किए बिना डीओसी को ओडीपी में निर्यात करने के लिए
url: /hi/java/conversion/doc-to-odp/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: ODP
otherformats: PPSM POT POWERPOINT PPTX POTX PPTM POTM PPS PPSX PPT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से DOC को ODP में बदलें" h2="Microsoft<sup>&reg;</sup> PowerPoint या Word का उपयोग किए बिना किसी भी Java J2SE, J2EE, J2ME अनुप्रयोगों में ऑन-प्रिमाइसेस Java API का उपयोग करके DOC से ODP रूपांतरण" >}}
{{% blocks/products/pf/feature-page-summary %}}
कई बार डेवलपर्स को DOC फाइल को प्रोग्रामेटिक रूप से ODP में कनवर्ट करना पड़ता है। फ़ाइल ऑटोमेशन जावा लाइब्रेरी [Aspose.Total for Java](https://products.aspose.com/total/java/) का उपयोग करके आप कुछ आसान चरणों में रेंडरिंग प्रक्रिया को स्वचालित कर सकते हैं। आप [Aspose.Words for Java](https://products.aspose.com/words/java/) का उपयोग करके अपनी DOC फ़ाइल लोड कर सकते हैं और इसे HTML में बदल सकते हैं। उसके बाद शक्तिशाली पावरपॉइंट मैनिपुलेशन Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) का उपयोग करके आप एक नया प्रेजेंटेशन बना सकते हैं, उसमें HTML सामग्री लिख सकते हैं और इसे ODP के रूप में सहेज सकते हैं। .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से DOC को ODP में कैसे बदलें" %}}
1. [दस्तावेज़](https://apireference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके DOC फ़ाइल खोलें
2. [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके DOC फ़ाइल को HTML में बदलें )) तरीका
3. एक नया [प्रस्तुति](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) ऑब्जेक्ट प्रारंभ करें
5. BufferedReader का उपयोग करके HTML फ़ाइल से सामग्री निकालें और अपनी प्रस्तुति फ़ाइल में सामग्री लिखें
6. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) पद्धति का उपयोग करके दस्तावेज़ को ODP में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
DOC से ODP फ़ाइल रूपांतरण के लिए, आप आसानी से सीधे [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose से जावा के लिए Aspose.Total का उपयोग कर सकते हैं। /aspose-total) आधारित परियोजना और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-doc-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
एपीआई आपको पासवर्ड से सुरक्षित डीओसी दस्तावेजों को ओडीपी में बदलने की भी अनुमति देता है। यदि आपका इनपुट डीओसी दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप पासवर्ड का उपयोग किए बिना इसे ओडीपी प्रारूप में परिवर्तित नहीं कर सकते। एन्क्रिप्टेड दस्तावेज़ खोलने के लिए आप LoadOptions ऑब्जेक्ट में सही पासवर्ड सेट कर सकते हैं और इसे दस्तावेज़ निर्माता को पास कर सकते हैं।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-doc-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-ppsm/" name="DOC सेवा PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-pot/" name="DOC सेवा POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-powerpoint/" name="DOC सेवा POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-pptx/" name="DOC सेवा PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-potx/" name="DOC सेवा POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-pptm/" name="DOC सेवा PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-potm/" name="DOC सेवा POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-pps/" name="DOC सेवा PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-ppsx/" name="DOC सेवा PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-ppt/" name="DOC सेवा PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-csv/" name="DOC सेवा CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-dif/" name="DOC सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-fods/" name="DOC सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-ods/" name="DOC सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-sxc/" name="DOC सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-tsv/" name="DOC सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-xlam/" name="DOC सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-xltm/" name="DOC सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-excel/" name="DOC सेवा EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-xls/" name="DOC सेवा XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-xlsb/" name="DOC सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-xlsm/" name="DOC सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-xlsx/" name="DOC सेवा XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-xlt/" name="DOC सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-xltm/" name="DOC सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/doc-to-xltx/" name="DOC सेवा XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}