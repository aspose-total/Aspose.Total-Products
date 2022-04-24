---
title: जावा के माध्यम से DOT को JSON फॉर्मेट में बदलें
description: माइक्रोसॉफ्ट वर्ड या माइक्रोसॉफ्ट एक्सेल का उपयोग किए बिना जावा के माध्यम से डीओसी को जेएसओएन प्रारूप में कनवर्ट करें
url: /hi/java/conversion/dot-to-json/
family: total
platformtag: net
feature: conversion
informat: DOT
outformat: JSON
otherformats: XLAM XLSB XLTM ODS XLT TSV SXC EXCEL FODS DIF XLTX CSV XLS XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से DOT को JSON फॉर्मेट में बदलें" h2="Microsoft<sup>&reg;</sup> Word या Microsoft<sup>&reg;</sup> Excel का उपयोग किए बिना DOT को JSON में कनवर्ट करने के लिए Premise Java API पर" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) के ज़रिए DOT को JSON फ़ॉर्मैट में बदलना एक आसान दो चरणों वाली प्रक्रिया है। सुविधा संपन्न, दस्तावेज़ हेरफेर और रूपांतरण API [Aspose.Words for Java](https://products.aspose.com/words/java/) का उपयोग करके, आप HTML को DOT निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) का उपयोग करके, आप HTML को JSON में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से DOT को JSON फॉर्मेट में बदलें" %}}
1. [दस्तावेज़](https://apireference.aspose.com/words/java/com.aspose.words/Dotument) वर्ग का उपयोग करके DOT फ़ाइल खोलें
2. [Save](https://apireference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके DOT को HTML में बदलें ) तरीका
3. [वर्कबुक](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) का उपयोग करके दस्तावेज़ को JSON फॉर्मेट में सेव करें। SaveOptions)) विधि
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड] (https://downloads.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
एपीआई का उपयोग करके, आप पासवर्ड से सुरक्षित दस्तावेज़ भी खोल सकते हैं। यदि आपका इनपुट DOT दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप पासवर्ड का उपयोग किए बिना इसे JSON प्रारूप में परिवर्तित नहीं कर सकते। एपीआई आपको लोडऑप्शन ऑब्जेक्ट में सही पासवर्ड पास करके एन्क्रिप्टेड दस्तावेज़ को खोलने की अनुमति देता है। निम्न कोड उदाहरण दिखाता है कि किसी एन्क्रिप्टेड दस्तावेज़ को पासवर्ड से खोलने का प्रयास कैसे करें:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से संरक्षित डीओसी को जेएसओएन प्रारूप में कनवर्ट करें" %}}
जब आप DOT को JSON में कनवर्ट कर रहे हैं, तो आप अपने आउटपुट JSON फॉर्मेट में रेंज भी सेट कर सकते हैं। सीमा निर्धारित करने के लिए, आप कार्यपुस्तिका वर्ग का उपयोग करके परिवर्तित HTML को खोल सकते हैं, Cells.createRange विधि का उपयोग करके निर्यात किए जाने वाले डेटा की एक श्रेणी बना सकते हैं, रेंज और ExportRangeToJsonOptions के संदर्भों के साथ JsonUtility.exportRangeToJson विधि को कॉल कर सकते हैं और फ़ाइल के लिए स्ट्रिंग JSON डेटा लिख सकते हैं। BufferedWriter.write विधि। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-xlam/" name="DOT सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-xlt/" name="DOT सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-csv/" name="DOT सेवा CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-xlsx/" name="DOT सेवा XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-fods/" name="DOT सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-xltm/" name="DOT सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-xlsm/" name="DOT सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-xltx/" name="DOT सेवा XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-ods/" name="DOT सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-xlsb/" name="DOT सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-excel/" name="DOT सेवा EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-sxc/" name="DOT सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-tsv/" name="DOT सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dot-to-dif/" name="DOT सेवा DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}