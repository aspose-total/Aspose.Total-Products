---
title: जावा के माध्यम से पीओटी को सीएसवी प्रारूप में कनवर्ट करें
description: माइक्रोसॉफ्ट एक्सेल या पावरपॉइंट का उपयोग किए बिना जावा के माध्यम से पीओटी को सीएसवी प्रारूप में कनवर्ट करें
url: /hi/java/conversion/pps-to-xls/
family: total
platformtag: net
feature: conversion
informat: PPS
outformat: XLS
otherformats: FODS XLAM XLTM XLSM SXC MARKDOWN XLSX XLS TSV ODS EXCEL MHTML DIF XLTX XLT XLSB DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से पीओटी को सीएसवी में कनवर्ट करें" h2="Microsoft<sup>&reg;</sup> Excel या PowerPoint का उपयोग किए बिना XLS को PPS निर्यात करने के लिए परिसर जावा API पर" >}}
{{% blocks/products/pf/feature-page-summary %}}
आप दो चरणों में [Aspose.Total for Java](https://products.aspose.com/total/java/) के ज़रिए PPS फ़ाइल को XLS में बदल सकते हैं। पहले चरण में आप [Aspose.Slides for Java](https://products.aspose.com/slides/java/) का उपयोग करके HTML को PPS निर्यात कर सकते हैं। दूसरे, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) का उपयोग करके, आप HTML को XLS में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से पीओटी को सीएसवी में कैसे बदलें" %}}
1. [प्रस्तुति](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके PPS फ़ाइल खोलें
2. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides का उपयोग करके PPS को HTML में बदलें। ISaveOptions-) विधि
3. [वर्कबुक](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) का उपयोग करके दस्तावेज़ को XLS प्रारूप में सहेजें। SaveOptions)) विधि
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
PPS को XLS में बदलने के लिए, आप सीधे [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/ से सीधे जावा के लिए Aspose.Total का उपयोग कर सकते हैं। aspose/aspose-total) आधारित परियोजना और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
एपीआई का उपयोग करके, आप पासवर्ड से सुरक्षित दस्तावेज़ भी खोल सकते हैं। यदि आपका इनपुट पीओटी दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप पासवर्ड का उपयोग किए बिना इसे सीएसवी में परिवर्तित नहीं कर सकते। एपीआई आपको लोडऑप्शन ऑब्जेक्ट में सही पासवर्ड पास करके एन्क्रिप्टेड दस्तावेज़ को खोलने की अनुमति देता है।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से संरक्षित पॉट को सीएसवी में कनवर्ट करें" %}}
PPS फ़ाइल को XLS में कनवर्ट करते समय, आप अपने आउटपुट XLS फ़ाइल स्वरूप में वॉटरमार्क भी जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, परिवर्तित HTML फ़ाइल को खोलने के लिए एक नई कार्यपुस्तिका बनाएं। इसकी अनुक्रमणिका के माध्यम से वर्कशीट का चयन करें, एक आकृति बनाएं और इसके addTextEffect फ़ंक्शन का उपयोग करें, रंग, पारदर्शिता और बहुत कुछ सेट करें। उसके बाद आप वॉटरमार्क के साथ अपने HTML दस्तावेज़ को XLS के रूप में सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-fods/" name="PPS सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-xltm/" name="PPS सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-xlt/" name="PPS सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-xlam/" name="PPS सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-markdown/" name="PPS सेवा MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-excel/" name="PPS सेवा EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-mhtml/" name="PPS सेवा MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-xlsb/" name="PPS सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-ods/" name="PPS सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-sxc/" name="PPS सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-xls/" name="PPS सेवा XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-xltx/" name="PPS सेवा XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-xlsx/" name="PPS सेवा XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-tsv/" name="PPS सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-dif/" name="PPS सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-xlsm/" name="PPS सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-doc/" name="PPS सेवा DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-docx/" name="PPS सेवा DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-docm/" name="PPS सेवा DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-dot/" name="PPS सेवा DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-dotm/" name="PPS सेवा DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-dotx/" name="PPS सेवा DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-odt/" name="PPS सेवा ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-ott/" name="PPS सेवा OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-rtf/" name="PPS सेवा RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-word/" name="PPS सेवा WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-wordml/" name="PPS सेवा WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-text/" name="PPS सेवा TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/pps-to-flatopx/" name="PPS सेवा FLAसेवाPX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}