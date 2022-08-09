---
title: जावा के माध्यम से एंड्रॉइड में पीओटी को सीएसवी में कनवर्ट करें
description: माइक्रोसॉफ्ट एक्सेल या पावरपॉइंट का उपयोग किए बिना जावा के माध्यम से एंड्रॉइड में पीओटी को सीएसवी में कनवर्ट करें
url: /hi/android-java/conversion/pot-to-xls/
family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: XLS
otherformats: XLTM TSV DIF XLSX XLT MARKDOWN MHTML ODS XLAM EXCEL FODS CSV XLTX SXC XLSB XLSM DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंड्रॉइड में पीओटी को सीएसवी में कनवर्ट करें" h2="Microsoft<sup>&reg;</sup> Excel या PowerPoint का उपयोग किए बिना Android अनुप्रयोगों में POT फ़ाइल को XLS में निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप अपने Android ऐप्लिकेशन में [Aspose.Total for Android by Java](https://products.aspose.com/total/android-java/) के ज़रिए आसानी से अपने Android ऐप्लिकेशन में POT फ़ाइल को XLS में बदल सकते हैं। पहले चरण में आप [Aspose.Slides for Android by Java](https://products.aspose.com/slides/android-java/) का उपयोग करके HTML को POT फ़ाइल निर्यात कर सकते हैं। दूसरे, [Aspose.Cells for Android by Java](https://products.aspose.com/cells/android-java/) का उपयोग करके, आप HTML को XLS में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="एंड्रॉइड में पीओटी को सीएसवी में कैसे बदलें" %}}
1. [प्रस्तुति](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके POT फ़ाइल खोलें
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)  का उपयोग करके POT को HTML में बदलें।ISaveOptions-) विधि
3. [वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. दस्तावेज़ को [save](https://reference.aspose.com/cells/java/com.aspose.cells/) का उपयोग करके XLS प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
POT को XLS में बदलने के लिए, आप आसानी से [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) और अपने ऐप में लाइब्रेरी इंस्टॉल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एंड्रॉइड में संरक्षित पॉट को सीएसवी में कनवर्ट करें" %}}
एपीआई का उपयोग करके, आप पासवर्ड से सुरक्षित दस्तावेज़ भी खोल सकते हैं। यदि आपका इनपुट पीओटी दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप पासवर्ड का उपयोग किए बिना इसे सीएसवी में परिवर्तित नहीं कर सकते। एपीआई आपको लोडऑप्शन ऑब्जेक्ट में सही पासवर्ड पास करके एन्क्रिप्टेड दस्तावेज़ को खोलने की अनुमति देता है। निम्न कोड उदाहरण दिखाता है कि किसी एन्क्रिप्टेड दस्तावेज़ को पासवर्ड से खोलने का प्रयास कैसे करें:
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="एंड्रॉइड में वॉटरमार्क के साथ पीओटी फ़ाइल को सीएसवी में कनवर्ट करें" %}}
POT फ़ाइल को XLS में कनवर्ट करते समय, आप अपने आउटपुट XLS फ़ाइल स्वरूप में वॉटरमार्क भी जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, परिवर्तित HTML फ़ाइल को खोलने के लिए एक नई कार्यपुस्तिका बनाएं। इसकी अनुक्रमणिका के माध्यम से वर्कशीट का चयन करें, एक आकृति बनाएं और इसके addTextEffect फ़ंक्शन का उपयोग करें, रंग, पारदर्शिता और बहुत कुछ सेट करें। उसके बाद आप वॉटरमार्क के साथ अपने HTML दस्तावेज़ को XLS के रूप में सहेज सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-xltm/" name="POT प्रति XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-tsv/" name="POT प्रति TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-dif/" name="POT प्रति DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-xlsx/" name="POT प्रति XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-xlt/" name="POT प्रति XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-markdown/" name="POT प्रति MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-mhtml/" name="POT प्रति MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-ods/" name="POT प्रति ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-xlam/" name="POT प्रति XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-excel/" name="POT प्रति EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-fods/" name="POT प्रति FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-xls/" name="POT प्रति XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-xltx/" name="POT प्रति XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-sxc/" name="POT प्रति SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-xlsb/" name="POT प्रति XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-xlsm/" name="POT प्रति XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-doc/" name="POT प्रति DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-docx/" name="POT प्रति DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-docm/" name="POT प्रति DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-dot/" name="POT प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-dotm/" name="POT प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-dotx/" name="POT प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-odt/" name="POT प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-ott/" name="POT प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-rtf/" name="POT प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-word/" name="POT प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-wordml/" name="POT प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-text/" name="POT प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-flatopx/" name="POT प्रति FLATOPX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}