---
title: सी # के माध्यम से पीओटी को सीएसवी में कनवर्ट करें
description: Microsoft Excel या Powerpoint का उपयोग किए बिना PPT को XLS में C# में बदलें
url_ignore: /hi/net/conversion/ppt-to-xls/
family: total
platformtag: net
feature: conversion
informat: PPT
outformat: XLS
otherformats: EXCEL XLTM XLSM XLAM XLSB FODS XLS XLTX XLSX MARKDOWN DIF SXC ODS MHTML XLT TSV DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सी # के माध्यम से पीओटी को सीएसवी में कनवर्ट करें" h2="Microsoft<sup>&reg;</sup> Excel या PowerPoint का उपयोग किए बिना PPT से XLS रूपांतरण के लिए .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) का उपयोग करके आप किसी भी .NET, C#, ASP.NET और VB.NET एप्लिकेशन में PPT फ़ाइल को XLS में कनवर्ट कर सकते हैं। सरल कदम। सबसे पहले, [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) का उपयोग करके, आप HTML को PPT निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) स्प्रेडशीट प्रोग्रामिंग API का उपयोग करके, आप HTML को XLS में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी # के माध्यम से पीओटी को सीएसवी में कैसे परिवर्तित करें" %}}
1. [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) वर्ग का उपयोग करके PPT फ़ाइल खोलें
2. [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) पद्धति का उपयोग करके PPT को HTML के रूप में निर्यात करें
3. [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) विधि का उपयोग करके दस्तावेज़ को XLS में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ```Install-Package Aspose.Total``` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="सी # के माध्यम से संरक्षित पीओटी को सीएसवी में कनवर्ट करें" %}}
पीओटी फ़ाइल को सीएसवी में कनवर्ट करते समय, यदि आपका इनपुट पीओटी दस्तावेज़ पासवर्ड से सुरक्षित है तो आप दस्तावेज़ को डिक्रिप्ट किए बिना इसे सीएसवी में परिवर्तित नहीं कर सकते हैं। जब आपका दस्तावेज़ पासवर्ड से सुरक्षित होता है, तो इसका मतलब है कि यह प्रस्तुति पर कुछ प्रतिबंध लागू करता है। प्रतिबंधों को हटाने के लिए, पासवर्ड दर्ज करना होगा। एक पासवर्ड-रक्षित प्रस्तुतिकरण को एक अवरोधित प्रस्तुति माना जाता है। एपीआई आपको लोडऑप्शन ऑब्जेक्ट में सही पासवर्ड पास करके एन्क्रिप्टेड दस्तावेज़ को खोलने की अनुमति देता है।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सी # के माध्यम से वॉटरमार्क के साथ पीओटी को सीएसवी में कनवर्ट करें" %}}
PPT फ़ाइल को XLS में कनवर्ट करते समय, आप अपने आउटपुट XLS फ़ाइल स्वरूप में वॉटरमार्क भी जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, आप एक नई वर्कबुक ऑब्जेक्ट बना सकते हैं और परिवर्तित HTML दस्तावेज़ खोल सकते हैं, इसके इंडेक्स के माध्यम से वर्कशीट का चयन कर सकते हैं, एक आकृति बना सकते हैं और इसके AddTextEffect फ़ंक्शन का उपयोग कर सकते हैं। उसके बाद आप वॉटरमार्क के साथ अपने HTML दस्तावेज़ को XLS के रूप में सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-fods/" name="PPT सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-xltm/" name="PPT सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-xlt/" name="PPT सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-xlam/" name="PPT सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-markdown/" name="PPT सेवा MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-excel/" name="PPT सेवा EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-mhtml/" name="PPT सेवा MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-xlsb/" name="PPT सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-ods/" name="PPT सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-sxc/" name="PPT सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-xls/" name="PPT सेवा XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-xltx/" name="PPT सेवा XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-xlsx/" name="PPT सेवा XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-tsv/" name="PPT सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-dif/" name="PPT सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-xlsm/" name="PPT सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-doc/" name="PPT सेवा DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-docx/" name="PPT सेवा DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-docm/" name="PPT सेवा DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-dot/" name="PPT सेवा DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-dotm/" name="PPT सेवा DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-dotx/" name="PPT सेवा DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-odt/" name="PPT सेवा ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-ott/" name="PPT सेवा OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-rtf/" name="PPT सेवा RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-word/" name="PPT सेवा WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-wordml/" name="PPT सेवा WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-text/" name="PPT सेवा TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ppt-to-flatopx/" name="PPT सेवा FLAसेवाPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}