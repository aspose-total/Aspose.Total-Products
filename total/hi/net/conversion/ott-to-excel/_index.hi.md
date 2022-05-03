---
title: OTT को EXCEL में बदलने के लिए .NET API
description: सी # एपीआई माइक्रोसॉफ्ट एक्सेल या एडोब रीडर का उपयोग किए बिना डीओसी को सीएसवी में कनवर्ट करने के लिए
url: /hi/net/conversion/ott-to-excel/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: XLSX
otherformats: DIF XLTX XLAM XLSB XLT EXCEL ODS TSV XLTM FODS XLS XLSX XLSM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सी # एपीआई डीओसी को सीएसवी में कनवर्ट करने के लिए" h2="Microsoft<sup>&reg;</sup> Word या Microsoft<sup>&reg;</sup> Excel का उपयोग किए बिना OTT को C# के माध्यम से EXCEL में निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) का उपयोग करके आप किसी भी .NET, C#, ASP.NET और VB.NET एप्लिकेशन में OTT से EXCEL रूपांतरण सुविधा शामिल कर सकते हैं। दो सरल कदम। सबसे पहले, [Aspose.Words for .NET](https://products.aspose.com/words/net/) का उपयोग करके, आप HTML को OTT निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) स्प्रेडशीट प्रोग्रामिंग API का उपयोग करके, आप HTML को EXCEL में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="OTT को EXCEL में बदलने के लिए .NET API" %}}
1. [Document](https://apireference.aspose.com/words/net/aspose.words/document) वर्ग का उपयोग करके OTT फ़ाइल खोलें
2. [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) विधि का उपयोग करके OTT को HTML में बदलें
3. [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) विधि का उपयोग करके दस्तावेज़ को EXCEL प्रारूप में सहेजें और `EXCEL` को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ```Install-Package Aspose.Total``` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="सी # के माध्यम से स्ट्रीम से डीओसी दस्तावेज़ लोड करें" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) भी आपको स्ट्रीम के माध्यम से OTT दस्तावेज़ लोड करने की अनुमति देता है। किसी स्ट्रीम से दस्तावेज़ खोलने के लिए, बस एक स्ट्रीम ऑब्जेक्ट पास करें जिसमें दस्तावेज़ [Document](https://apireference.aspose.com/words/net/aspose.words/document) कंस्ट्रक्टर में हो। निम्न कोड उदाहरण दिखाता है कि किसी स्ट्रीम से दस्तावेज़ कैसे खोलें:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सी # के माध्यम से सीएसवी फ़ाइल में कस्टम गुण जोड़ें" %}}
OTT को EXCEL में कनवर्ट करते समय, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) आपको अपने EXCEL दस्तावेज़ों में कस्टम गुण जोड़ने में सक्षम बनाता है। कस्टम प्रॉपर्टी जोड़ने के लिए, आप [CustomDocumentPropertyCollection] के लिए [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) मेथड का इस्तेमाल कर सकते हैं। https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) वर्ग। जोड़ें विधि संपत्ति को एक्सेल फ़ाइल में जोड़ती है और नई दस्तावेज़ संपत्ति के लिए एक [Aspose.Cells.Properties.DocumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties)  के रूप में एक संदर्भ देता है दस्तावेज़प्रॉपर्टी वस्तु। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-dif/" name="OTT सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-xlsb/" name="OTT सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-tsv/" name="OTT सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-fods/" name="OTT सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-xlt/" name="OTT सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-excel/" name="OTT सेवा EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-xlsx/" name="OTT सेवा XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-ods/" name="OTT सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-sxc/" name="OTT सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-xlam/" name="OTT सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-xltm/" name="OTT सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-xlsm/" name="OTT सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-xls/" name="OTT सेवा XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ott-to-xltx/" name="OTT सेवा XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}