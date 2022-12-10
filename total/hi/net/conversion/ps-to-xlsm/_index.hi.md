---
title: C# API के माध्यम से PS को XLSM में बदलें
description: सी # एपीआई माइक्रोसॉफ्ट एक्सेल या एडोब रीडर का उपयोग किए बिना सीजीएम फ़ाइल को सीएसवी में कनवर्ट करने के लिए
url_ignore: /hi/net/conversion/ps-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XLSM
otherformats: XLTM XLSB ODS DIF EXCEL XLSM MD TSV XLAM XLT SXC XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सी # एपीआई सीएसवी को सीजीएम प्रस्तुत करने के लिए" h2="Microsoft<sup>&reg;</sup> Excel या Adobe<sup>&reg;</sup> Acrobat Reader का उपयोग किए बिना C# के माध्यम से PS फ़ाइल को XLSM में निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) का उपयोग करके आप किसी भी .NET, C#, ASP.NET और VB.NET अनुप्रयोगों में आसानी से PS फ़ाइल को XLSM में कनवर्ट कर सकते हैं। सबसे पहले, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) का उपयोग करके, आप PS को XLSX में निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) स्प्रेडशीट प्रोग्रामिंग API का उपयोग करके, आप XLSX को XLSM में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सीजीएम को सीएसवी में बदलने के लिए .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) पद्धति का उपयोग करके PS को XLSX में बदलें
3. [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) क्लास का इस्तेमाल करके XLSX दस्तावेज़ लोड करें
4. [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) विधि का उपयोग करके दस्तावेज़ को XLSM प्रारूप में सहेजें और `Xlsm` को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ```Install-Package Aspose.Total``` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="सी#के माध्यम से संरक्षित सीजीएम को सीएसवी में कनवर्ट करें" %}}
यदि आपका सीजीएम दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप इसे पासवर्ड के बिना सीएसवी में परिवर्तित नहीं कर सकते। एपीआई का उपयोग करके, आप पहले एक वैध पासवर्ड का उपयोग करके संरक्षित दस्तावेज़ को खोल सकते हैं और उसके बाद उसे परिवर्तित कर सकते हैं। एन्क्रिप्ट की गई फ़ाइल को खोलने के लिए, आप [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) वर्ग का एक नया उदाहरण प्रारंभ कर सकते हैं और फ़ाइल नाम और पासवर्ड को तर्क के रूप में पास कर सकते हैं।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सी # के माध्यम से वॉटरमार्क के साथ सीजीएम फ़ाइल को सीएसवी में कनवर्ट करें" %}}
PS फ़ाइल को XLSM में कनवर्ट करते समय, आप अपने आउटपुट XLSM फ़ाइल स्वरूप में वॉटरमार्क भी जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, आप एक नई वर्कबुक ऑब्जेक्ट बना सकते हैं और परिवर्तित XLSX दस्तावेज़ खोल सकते हैं, इसके इंडेक्स के माध्यम से वर्कशीट का चयन कर सकते हैं, एक आकृति बना सकते हैं और इसके AddTextEffect फ़ंक्शन का उपयोग कर सकते हैं। उसके बाद आप अपने XLSX दस्तावेज़ को वॉटरमार्क के साथ XLSM के रूप में सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-sxc/" name="PS सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-xltx/" name="PS सेवा XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-md/" name="PS सेवा MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-tsv/" name="PS सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-txt/" name="PS सेवा TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-ods/" name="PS सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-xlt/" name="PS सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-xlsm/" name="PS सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-xlam/" name="PS सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-xltm/" name="PS सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-dif/" name="PS सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/ps-to-xlsb/" name="PS सेवा XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}