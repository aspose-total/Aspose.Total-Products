---
title: जावा के माध्यम से पीओटी को डीओसी में कनवर्ट करें
description: Microsoft Word या PowerPoint का उपयोग किए बिना DOCM को PPTM निर्यात करने के लिए Java API
url: /hi/java/conversion/pptm-to-docm/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: DOCMM
otherformats: DOTM DOCM RTF OTT DOT WORD FLATOPC TEXT ODT DOTX DOCMX WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से पीओटी को डीओसी में कनवर्ट करें" h2="किसी भी जावा J2SE, J2EE, J2ME अनुप्रयोगों के भीतर PowerPoint PPTM से DOCM रूपांतरण के लिए परिसर जावा एपीआई पर" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) फाइल फॉर्मेट ऑटोमेशन लाइब्रेरी जावा डेवलपर्स को पावरपॉइंट पॉट की बैच रूपांतरण प्रक्रिया को वर्ड डीओसी में स्वचालित करने के लिए सशक्त बनाती है। दस्तावेज़ को परिवर्तित करना दो चरणों वाली प्रक्रिया है और इसमें दो API का उपयोग करना शामिल है। हम [Aspose.Slides for Java](https://products.aspose.com/slides/java/) का उपयोग करेंगे जो कि PPTM को HTML में बदलने के लिए प्रस्तुतियों में हेरफेर और प्रबंधन के लिए एक PowerPoint API है। उसके बाद सुविधा संपन्न वर्ड प्रोसेसिंग एपीआई [Aspose.Words for Java](https://products.aspose.com/words/java/) का उपयोग करके हम HTML को DOCM में बदल देंगे।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से पीओटी को डीओसी में कैसे बदलें" %}}
1. [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके PPTM फ़ाइल खोलें
2. Presentation.save का उपयोग करके PPTM को HTML में बदलें। विधि और HTML को SaveFormat के रूप में सेट करें
3. परिवर्तित HTML फ़ाइल को [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके लोड करें
4. [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) विधि का उपयोग करके दस्तावेज़ को DOCM प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
PPTM से DOCM फ़ाइल रूपांतरण के लिए, आप आसानी से सीधे [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose से जावा के लिए Aspose.Total का उपयोग कर सकते हैं। /aspose-total) आधारित परियोजना और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
एपीआई का उपयोग करके, आप वॉटरमार्क के साथ पीओटी फ़ाइल को डीओसी रूपांतरण में भी कर सकते हैं। अपने DOCM दस्तावेज़ में वॉटरमार्क जोड़ने के लिए, आप पहले PPTM फ़ाइल को HTML में बदल सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके नई बनाई गई HTML फ़ाइल लोड करें, TextWatermarkOptions का एक उदाहरण बनाएं और सेट करें इसके गुण, Watermark.setText विधि को कॉल करें और वॉटरमार्क टेक्स्ट और TextWatermarkOptions का ऑब्जेक्ट पास करें।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-word/" name="PPTM सेवा WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-dotx/" name="PPTM सेवा DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-odt/" name="PPTM सेवा ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-ott/" name="PPTM सेवा OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-rtf/" name="PPTM सेवा RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-flatopc/" name="PPTM सेवा FLAसेवाPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-wordml/" name="PPTM सेवा WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-docmm/" name="PPTM सेवा DOCMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-text/" name="PPTM सेवा TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-docmx/" name="PPTM सेवा DOCMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-dotm/" name="PPTM सेवा DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pptm-to-dot/" name="PPTM सेवा DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}