---
title: DOTX को XLAM में बदलने के लिए .NET API
description: सी # एपीआई माइक्रोसॉफ्ट एक्सेल या एडोब रीडर का उपयोग किए बिना डीओसी को सीएसवी में कनवर्ट करने के लिए
url: /hi/net/conversion/dotx-to-xlam/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: XLAM
otherformats: XLSB XLTM SXC TSV DIF XLTX XLAM EXCEL XLSM FODS XLSX XLT XLS ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सी # एपीआई डीओसी को सीएसवी में कनवर्ट करने के लिए" h2="Microsoft<sup>&reg;</sup> Word या Microsoft<sup>&reg;</sup> Excel का उपयोग किए बिना DOTX को C# के माध्यम से XLAM में निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) का उपयोग करके आप किसी भी .NET, C#, ASP.NET और VB.NET एप्लिकेशन में DOTX से XLAM रूपांतरण सुविधा शामिल कर सकते हैं। दो सरल कदम। सबसे पहले, [Aspose.Words for .NET](https://products.aspose.com/words/net/) का उपयोग करके, आप HTML को DOTX निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) स्प्रेडशीट प्रोग्रामिंग API का उपयोग करके, आप HTML को XLAM में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOTX को XLAM में बदलने के लिए .NET API" %}}
1. [दस्तावेज़](https://apireference.aspose.com/words/net/aspose.words/dotxument) वर्ग का उपयोग करके DOTX फ़ाइल खोलें
2. [Save](https://apireference.aspose.com/words/net/aspose.words.dotxument/save/methods/4) विधि का उपयोग करके DOTX को HTML में बदलें
3. [वर्कबुक](https://apireference.aspose.com/cells/net/aspose.cells/workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) विधि का उपयोग करके दस्तावेज़ को XLAM प्रारूप में सहेजें और `XLAM` को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ````Install-Package Aspose.Total`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="सी # के माध्यम से स्ट्रीम से डीओसी दस्तावेज़ लोड करें" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) भी आपको स्ट्रीम के माध्यम से DOTX दस्तावेज़ लोड करने की अनुमति देता है। किसी स्ट्रीम से दस्तावेज़ खोलने के लिए, बस एक स्ट्रीम ऑब्जेक्ट पास करें जिसमें दस्तावेज़ [दस्तावेज़](https://apireference.aspose.com/words/net/aspose.words/dotxument) कंस्ट्रक्टर में हो। निम्न कोड उदाहरण दिखाता है कि किसी स्ट्रीम से दस्तावेज़ कैसे खोलें:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सी # के माध्यम से सीएसवी फ़ाइल में कस्टम गुण जोड़ें" %}}
DOTX को XLAM में कनवर्ट करते समय, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) आपको अपने XLAM दस्तावेज़ों में कस्टम गुण जोड़ने में सक्षम बनाता है। कस्टम प्रॉपर्टी जोड़ने के लिए, आप [CustomDotxumentPropertyCollection] के लिए [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdotxumentpropertycollection/methods/add/index) मेथड का इस्तेमाल कर सकते हैं। https://apireference.aspose.com/cells/net/aspose.cells.properties/customdotxumentpropertycollection) वर्ग। जोड़ें विधि संपत्ति को एक्सेल फ़ाइल में जोड़ती है और नई दस्तावेज़ संपत्ति के लिए एक [Aspose.Cells.Properties.DotxumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties के रूप में एक संदर्भ देता है। /दस्तावेज़प्रॉपर्टी) वस्तु। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-dif/" name="DOTX सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-xlsb/" name="DOTX सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-tsv/" name="DOTX सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-fods/" name="DOTX सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-xlt/" name="DOTX सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-excel/" name="DOTX सेवा EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-xlsx/" name="DOTX सेवा XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-ods/" name="DOTX सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-sxc/" name="DOTX सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-xlam/" name="DOTX सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-xltm/" name="DOTX सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-xlsm/" name="DOTX सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-xls/" name="DOTX सेवा XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotx-to-xltx/" name="DOTX सेवा XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}