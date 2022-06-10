---
title: RTF को XLT में बदलने के लिए .NET API
description: सी # एपीआई माइक्रोसॉफ्ट एक्सेल या एडोब रीडर का उपयोग किए बिना डीओसी को सीएसवी में कनवर्ट करने के लिए
url_ignore: /hi/net/conversion/rtf-to-xlt/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: XLT
otherformats: XLTM SXC XLSX XLTX TSV EXCEL XLSB XLT XLS FODS XLSM XLAM DIF ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सी # एपीआई डीओसी को सीएसवी में कनवर्ट करने के लिए" h2="Microsoft<sup>&reg;</sup> Word या Microsoft<sup>&reg;</sup> Excel का उपयोग किए बिना RTF को C# के माध्यम से XLT में निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) का उपयोग करके आप किसी भी .NET, C#, ASP.NET और VB.NET एप्लिकेशन में RTF से XLT रूपांतरण सुविधा शामिल कर सकते हैं। दो सरल कदम। सबसे पहले, [Aspose.Words for .NET](https://products.aspose.com/words/net/) का उपयोग करके, आप HTML को RTF निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) स्प्रेडशीट प्रोग्रामिंग API का उपयोग करके, आप HTML को XLT में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="RTF को XLT में बदलने के लिए .NET API" %}}
1. [Document](https://reference.aspose.com/words/net/aspose.words/Document) वर्ग का उपयोग करके RTF फ़ाइल खोलें
2. [Save](https://reference.aspose.com/words/net/aspose.words.Document/save/methods/4) विधि का उपयोग करके RTF को HTML में बदलें
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) विधि का उपयोग करके दस्तावेज़ को XLT प्रारूप में सहेजें और `XLT` को SaveFormat के रूप में सेट करें
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
[Aspose.Words for .NET](https://products.aspose.com/words/net/) भी आपको स्ट्रीम के माध्यम से RTF दस्तावेज़ लोड करने की अनुमति देता है। किसी स्ट्रीम से दस्तावेज़ खोलने के लिए, बस एक स्ट्रीम ऑब्जेक्ट पास करें जिसमें दस्तावेज़ [Document](https://reference.aspose.com/words/net/aspose.words/Document) कंस्ट्रक्टर में हो। निम्न कोड उदाहरण दिखाता है कि किसी स्ट्रीम से दस्तावेज़ कैसे खोलें:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सी # के माध्यम से सीएसवी फ़ाइल में कस्टम गुण जोड़ें" %}}
RTF को XLT में कनवर्ट करते समय, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) आपको अपने XLT दस्तावेज़ों में कस्टम गुण जोड़ने में सक्षम बनाता है। कस्टम प्रॉपर्टी जोड़ने के लिए, आप [CustomDocumentPropertyCollection] के लिए [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection/methods/add/index) मेथड का इस्तेमाल कर सकते हैं। https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection) वर्ग। जोड़ें विधि संपत्ति को एक्सेल फ़ाइल में जोड़ती है और नई दस्तावेज़ संपत्ति के लिए एक [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties)  के रूप में एक संदर्भ देता है दस्तावेज़प्रॉपर्टी वस्तु। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-dif/" name="RTF सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-xlsb/" name="RTF सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-tsv/" name="RTF सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-fods/" name="RTF सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-xlt/" name="RTF सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-excel/" name="RTF सेवा EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-xlsx/" name="RTF सेवा XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-ods/" name="RTF सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-sxc/" name="RTF सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-xlam/" name="RTF सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-xltm/" name="RTF सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-xlsm/" name="RTF सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-xls/" name="RTF सेवा XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/rtf-to-xltx/" name="RTF सेवा XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}