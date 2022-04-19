---
title: .NET . के माध्यम से PPSM को JSON फॉर्मेट में बदलें
description: Microsoft Excel या Powerpoint का उपयोग किए बिना PPSM को JSON में C# में बदलें
url: /hi/net/conversion/ppsm-to-json/
family: total
platformtag: net
feature: conversion
informat: PPSM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सी # के माध्यम से ओडीपी को जेएसओएन प्रारूप में कनवर्ट करें" h2="Microsoft<sup>&reg;</sup> Excel या PowerPoint का उपयोग किए बिना PPSM को C# के माध्यम से JSON में निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) का उपयोग करके आप किसी भी .NET, C#, ASP.NET और VB.NET एप्लिकेशन में PPSM को JSON फॉर्मेट में कन्वर्ट कर सकते हैं। सरल कदम। सबसे पहले, [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) का उपयोग करके, आप PPSM को HTML में निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) स्प्रेडशीट प्रोग्रामिंग API का उपयोग करके, आप HTML को JSON में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी # के माध्यम से ओडीपी को जेएसओएन प्रारूप में कनवर्ट करें" %}}
1. [प्रस्तुति](https://apireference.aspose.com/slides/net/aspose.slides/presentation) वर्ग का उपयोग करके PPSM फ़ाइल खोलें
2. [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) विधि का उपयोग करके PPSM को HTML में बदलें
3. [वर्कबुक](https://apireference.aspose.com/cells/net/aspose.cells/workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) विधि का उपयोग करके दस्तावेज़ को JSON प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ````Install-Package Aspose.Total`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड] (https://downloads.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="संरक्षित ओडीपी को सी # के माध्यम से जेएसओएन प्रारूप में कनवर्ट करें" %}}
एपीआई का उपयोग करके, आप पासवर्ड से सुरक्षित दस्तावेज़ भी खोल सकते हैं। यदि आपका इनपुट PPSM दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप पासवर्ड का उपयोग किए बिना इसे JSON प्रारूप में परिवर्तित नहीं कर सकते। एपीआई आपको लोडऑप्शन ऑब्जेक्ट में सही पासवर्ड पास करके एन्क्रिप्टेड दस्तावेज़ को खोलने की अनुमति देता है। निम्न कोड उदाहरण दिखाता है कि पासवर्ड के साथ एन्क्रिप्टेड दस्तावेज़ कैसे खोलें।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सी # के माध्यम से ओडीपी को जेएसओएन में रेंज में कनवर्ट करें" %}}
जब आप PPSM को JSON में कनवर्ट कर रहे हैं, तो आप अपने आउटपुट JSON फॉर्मेट में रेंज भी सेट कर सकते हैं। सीमा निर्धारित करने के लिए, आप कार्यपुस्तिका वर्ग का उपयोग करके परिवर्तित HTML को खोल सकते हैं, डेटा युक्त कार्यपत्रक का CellCollection प्राप्त कर सकते हैं, पंक्ति और स्तंभ सूचकांक निर्दिष्ट करके CellCollection से एक श्रेणी बना सकते हैं, और Range और ExportRangeToJsonOptions ऑब्जेक्ट्स के संदर्भ में ExportRangeToJson विधि को कॉल कर सकते हैं। अंत में, आप फ़ाइल के लिए JSON डेटा को File.WriteAllText विधि के माध्यम से सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-doc/" name="PPSM सेवा DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-docm/" name="PPSM सेवा DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-docx/" name="PPSM सेवा DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-dot/" name="PPSM सेवा DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-dotm/" name="PPSM सेवा DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-dotx/" name="PPSM सेवा DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-odt/" name="PPSM सेवा ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-ott/" name="PPSM सेवा OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-rtf/" name="PPSM सेवा RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-text/" name="PPSM सेवा TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-word/" name="PPSM सेवा WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppsm-to-wordml/" name="PPSM सेवा WORDML" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}