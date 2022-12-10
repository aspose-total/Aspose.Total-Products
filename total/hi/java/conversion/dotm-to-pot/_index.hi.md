---
title: जावा के माध्यम से DOTM को POT में बदलें
description: जावा एपीआई माइक्रोसॉफ्ट वर्ड या पावरपॉइंट का उपयोग किए बिना डीओसी को ओडीपी में निर्यात करने के लिए
url_ignore: /hi/java/conversion/dotm-to-pot/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: POT
otherformats: PPS PPT PPTM PPSM PPTX POTM PPSX POWERPOINT POTX POT CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से DOTM को POT में बदलें" h2="Microsoft<sup>&reg;</sup> PowerPoint या Word का उपयोग किए बिना किसी भी Java J2SE, J2EE, J2ME अनुप्रयोगों में ऑन-प्रिमाइसेस Java API का उपयोग करके DOTM से POT रूपांतरण" >}}
{{% blocks/products/pf/feature-page-summary %}}
कई बार डेवलपर्स को DOTM फाइल को प्रोग्रामेटिक रूप से POT में कनवर्ट करना पड़ता है। फ़ाइल ऑटोमेशन जावा लाइब्रेरी [Aspose.Total for Java](https://products.aspose.com/total/java/) का उपयोग करके आप कुछ आसान चरणों में रेंडरिंग प्रक्रिया को स्वचालित कर सकते हैं। आप [Aspose.Words for Java](https://products.aspose.com/words/java/) का उपयोग करके अपनी DOTM फ़ाइल लोड कर सकते हैं और इसे HTML में बदल सकते हैं। उसके बाद शक्तिशाली पावरपॉइंट मैनिपुलेशन Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) का उपयोग करके आप एक नया प्रेजेंटेशन बना सकते हैं, उसमें HTML सामग्री लिख सकते हैं और इसे POT के रूप में सहेज सकते हैं। .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से DOTM को POT में कैसे बदलें" %}}
1. [Document](https://reference.aspose.com/words/java/com.aspose.words/Dotmument) वर्ग का उपयोग करके DOTM फ़ाइल खोलें
2. [save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके DOTM फ़ाइल को HTML में बदलें)) तरीका
3. एक नया [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) ऑब्जेक्ट प्रारंभ करें
5. BufferedReader का उपयोग करके HTML फ़ाइल से सामग्री निकालें और अपनी प्रस्तुति फ़ाइल में सामग्री लिखें
6. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) पद्धति का उपयोग करके दस्तावेज़ को POT में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
DOTM से POT फ़ाइल रूपांतरण के लिए, आप आसानी से सीधे [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose से जावा के लिए Aspose.Total का उपयोग कर सकते हैं। /aspose-total) आधारित परियोजना और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-dotm-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
एपीआई आपको पासवर्ड से सुरक्षित डीओसी दस्तावेजों को ओडीपी में बदलने की भी अनुमति देता है। यदि आपका इनपुट डीओसी दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप पासवर्ड का उपयोग किए बिना इसे ओडीपी प्रारूप में परिवर्तित नहीं कर सकते। एन्क्रिप्टेड दस्तावेज़ खोलने के लिए आप LoadOptions ऑब्जेक्ट में सही पासवर्ड सेट कर सकते हैं और इसे दस्तावेज़ निर्माता को पास कर सकते हैं।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-dotm-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-ppsm/" name="DOTM सेवा PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-pot/" name="DOTM सेवा POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-powerpoint/" name="DOTM सेवा POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-pptx/" name="DOTM सेवा PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-potx/" name="DOTM सेवा POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-pptm/" name="DOTM सेवा PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-potm/" name="DOTM सेवा POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-pps/" name="DOTM सेवा PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-ppsx/" name="DOTM सेवा PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-ppt/" name="DOTM सेवा PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-csv/" name="DOTM सेवा CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-dif/" name="DOTM सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-fods/" name="DOTM सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-ods/" name="DOTM सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-sxc/" name="DOTM सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-tsv/" name="DOTM सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xlam/" name="DOTM सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xltm/" name="DOTM सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-excel/" name="DOTM सेवा EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xls/" name="DOTM सेवा XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xlsb/" name="DOTM सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xlsm/" name="DOTM सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xlsx/" name="DOTM सेवा XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xlt/" name="DOTM सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xltm/" name="DOTM सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xltx/" name="DOTM सेवा XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}