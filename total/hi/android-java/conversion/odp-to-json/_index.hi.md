---
title: जावा के माध्यम से एंड्रॉइड में डीओसी को जेएसओएन प्रारूप में कनवर्ट करें
description: माइक्रोसॉफ्ट वर्ड या एक्सेल का उपयोग किए बिना जावा के माध्यम से एंड्रॉइड में जेएसओएन प्रारूप में पार्स डीओसी
url: /hi/android-java/conversion/odp-to-json/
family: total
platformtag: cpp
feature: conversion
informat: ODP
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंड्रॉइड में डीओसी को जेएसओएन प्रारूप में कनवर्ट करें" h2="Microsoft<sup>&reg;</sup> Word या Excel का उपयोग किए बिना JSON को ODP निर्यात करने के लिए Android एप्लिकेशन डिज़ाइन करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) के ज़रिए अपने Android ऐप्लिकेशन में ODP को JSON फ़ॉर्मैट में बदल सकते हैं। दस्तावेज़ हेरफेर और रूपांतरण API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) का उपयोग करके, आप HTML को ODP निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) का उपयोग करके, आप HTML को JSON में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android में ODP को JSON फॉर्मेट में बदलें" %}}
1. [Document](https://reference.aspose.com/words/java/com.aspose.words/Odpument) वर्ग का उपयोग करके ODP फ़ाइल खोलें
2. [Save](https://reference.aspose.com/words/java/com.aspose.words/Odpument#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके ODP को HTML में बदलें ) तरीका
3. [वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) का उपयोग करके दस्तावेज़ को JSON फॉर्मेट में सेव करें। SaveOptions)) विधि
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और अपने ऐप में लाइब्रेरी इंस्टॉल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से Android में संरक्षित ODP को JSON प्रारूप में बदलें" %}}
एपीआई का उपयोग करके, आप पासवर्ड से सुरक्षित दस्तावेज़ भी खोल सकते हैं। यदि आपका इनपुट ODP दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप पासवर्ड का उपयोग किए बिना इसे JSON प्रारूप में परिवर्तित नहीं कर सकते। एपीआई आपको लोडऑप्शन ऑब्जेक्ट में सही पासवर्ड पास करके एन्क्रिप्टेड दस्तावेज़ को खोलने की अनुमति देता है। निम्न कोड उदाहरण दिखाता है कि किसी एन्क्रिप्टेड दस्तावेज़ को पासवर्ड के साथ कैसे खोलें।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एंड्रॉइड में रेंज में डीओसी को जेएसओएन में कनवर्ट करें" %}}
जब आप ODP को JSON में कनवर्ट कर रहे हैं, तो आप अपने आउटपुट JSON फॉर्मेट में रेंज भी सेट कर सकते हैं। सीमा निर्धारित करने के लिए, आप कार्यपुस्तिका वर्ग का उपयोग करके परिवर्तित HTML को खोल सकते हैं, Cells.createRange विधि का उपयोग करके निर्यात किए जाने वाले डेटा की एक श्रेणी बना सकते हैं, रेंज और ExportRangeToJsonOptions के संदर्भों के साथ JsonUtility.exportRangeToJson विधि को कॉल कर सकते हैं और फ़ाइल के लिए स्ट्रिंग JSON डेटा लिख सकते हैं। BufferedWriter.write विधि।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-odp/" name="ODP प्रति ODP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-odpm/" name="ODP प्रति ODPM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-odpx/" name="ODP प्रति ODPX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-dot/" name="ODP प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-dotm/" name="ODP प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-dotx/" name="ODP प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-odt/" name="ODP प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-ott/" name="ODP प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-rtf/" name="ODP प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-text/" name="ODP प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-word/" name="ODP प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/odp-to-wordml/" name="ODP प्रति WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}