---
title: जावा के माध्यम से एंड्रॉइड में डीओसी को जेएसओएन प्रारूप में कनवर्ट करें
description: माइक्रोसॉफ्ट वर्ड या एक्सेल का उपयोग किए बिना जावा के माध्यम से एंड्रॉइड में जेएसओएन प्रारूप में पार्स डीओसी
url: /hi/android-java/conversion/docx-to-json/
family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंड्रॉइड में डीओसी को जेएसओएन प्रारूप में कनवर्ट करें" h2="Microsoft<sup>&reg;</sup> Word या Excel का उपयोग किए बिना JSON को DOCX निर्यात करने के लिए Android एप्लिकेशन डिज़ाइन करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप [Aspose.Total for Android by Java](https://products.aspose.com/total/android-java/) के ज़रिए अपने Android ऐप्लिकेशन में DOCX को JSON फ़ॉर्मैट में बदल सकते हैं। दस्तावेज़ हेरफेर और रूपांतरण API [Aspose.Words for Android by Java](https://products.aspose.com/words/android-java/) का उपयोग करके, आप HTML को DOCX निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for Android by Java](https://products.aspose.com/cells/android-java/) का उपयोग करके, आप HTML को JSON में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android में DOCX को JSON फॉर्मेट में बदलें" %}}
1. [दस्तावेज़](https://reference.aspose.com/words/java/com.aspose.words/Docxument) वर्ग का उपयोग करके DOCX फ़ाइल खोलें
2. [Save](https://reference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके DOCX को HTML में बदलें ) तरीका
3. [वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) का उपयोग करके दस्तावेज़ को JSON फॉर्मेट में सेव करें। SaveOptions)) विधि
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे जावा के माध्यम से Android के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और अपने ऐप में लाइब्रेरी इंस्टॉल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से Android में संरक्षित DOCX को JSON प्रारूप में बदलें" %}}
एपीआई का उपयोग करके, आप पासवर्ड से सुरक्षित दस्तावेज़ भी खोल सकते हैं। यदि आपका इनपुट DOCX दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप पासवर्ड का उपयोग किए बिना इसे JSON प्रारूप में परिवर्तित नहीं कर सकते। एपीआई आपको लोडऑप्शन ऑब्जेक्ट में सही पासवर्ड पास करके एन्क्रिप्टेड दस्तावेज़ को खोलने की अनुमति देता है। निम्न कोड उदाहरण दिखाता है कि किसी एन्क्रिप्टेड दस्तावेज़ को पासवर्ड के साथ कैसे खोलें।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एंड्रॉइड में रेंज में डीओसी को जेएसओएन में कनवर्ट करें" %}}
जब आप DOCX को JSON में कनवर्ट कर रहे हैं, तो आप अपने आउटपुट JSON फॉर्मेट में रेंज भी सेट कर सकते हैं। सीमा निर्धारित करने के लिए, आप कार्यपुस्तिका वर्ग का उपयोग करके परिवर्तित HTML को खोल सकते हैं, Cells.createRange विधि का उपयोग करके निर्यात किए जाने वाले डेटा की एक श्रेणी बना सकते हैं, रेंज और ExportRangeToJsonOptions के संदर्भों के साथ JsonUtility.exportRangeToJson विधि को कॉल कर सकते हैं और फ़ाइल के लिए स्ट्रिंग JSON डेटा लिख सकते हैं। BufferedWriter.write विधि।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-xlam/" name="DOCX प्रति XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-xlsm/" name="DOCX प्रति XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-dif/" name="DOCX प्रति DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-xlt/" name="DOCX प्रति XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-csv/" name="DOCX प्रति CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-xltx/" name="DOCX प्रति XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-xlsx/" name="DOCX प्रति XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-tsv/" name="DOCX प्रति TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-ods/" name="DOCX प्रति ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-xltm/" name="DOCX प्रति XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-excel/" name="DOCX प्रति EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-fods/" name="DOCX प्रति FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-xls/" name="DOCX प्रति XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/docx-to-xlsb/" name="DOCX प्रति XLSB" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}