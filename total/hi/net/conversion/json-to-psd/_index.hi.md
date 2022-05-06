---
title: JSON प्रारूप को .NET के माध्यम से एपीएनजी में कनवर्ट करें
description: तीसरे पक्ष की निर्भरता का उपयोग किए बिना JSON को C# में PSD में पार्स करें
url_ignore: /hi/net/conversion/json-to-psd/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PSD
otherformats: EMZ WMZ PSD WMF JPEG2000 DXF DICOM IMAGE SVGZ TGA
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जेएसओएन प्रारूप को सी # के माध्यम से एपीएनजी में कनवर्ट करें" h2="सी # एपीआई तीसरे पक्ष की निर्भरता का उपयोग किए बिना JSON को PSD में पार्स करने के लिए" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) का उपयोग करके आप किसी भी .NET, C#, ASP.NET और VB.NET एप्लिकेशन में JSON को PSD में पार्स कर सकते हैं। कदम। सबसे पहले, [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) का उपयोग करके, आप JSON को JPEG में निर्यात कर सकते हैं। उसके बाद, [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) का उपयोग करके, आप JPEG को PSD में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जेएसओएन प्रारूप को सी # के माध्यम से एपीएनजी में कनवर्ट करें" %}}
1. एक नई [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) ऑब्जेक्ट बनाएं और फ़ाइल से JSON डेटा पढ़ें
2. [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) विधि का उपयोग करके JSON को JPEG में बदलें
3. [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) वर्ग का उपयोग करके JPEG दस्तावेज़ लोड करें
4. [सेव](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) विधि का उपयोग करके दस्तावेज़ को PSD प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ```Install-Package Aspose.Total``` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="लेआउट सेट करें और जेएसओएन प्रारूप को सी # के माध्यम से एपीएनजी में कनवर्ट करें" %}}
JSON को PSD में पार्स करते समय, आप [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) का उपयोग करके अपने JSON के लिए लेआउट विकल्प भी सेट कर सकते हैं। यह आपको सरणी को तालिका के रूप में संसाधित करने, नल को अनदेखा करने, सरणी शीर्षक को अनदेखा करने, ऑब्जेक्ट शीर्षक को अनदेखा करने, स्ट्रिंग को संख्या या दिनांक में कनवर्ट करने, दिनांक और संख्या प्रारूप सेट करने और शीर्षक शैली सेट करने की अनुमति देता है। ये सभी विकल्प आपको अपनी आवश्यकताओं के अनुसार अपना डेटा प्रस्तुत करने की अनुमति देते हैं। निम्न कोड स्निपेट आपको दिखाता है कि लेआउट विकल्प कैसे सेट करें।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="पार्स JSON प्रारूप वॉटरमार्क के साथ PSD करने के लिए" %}}
एपीआई का उपयोग करके, आप अपने एपीएनजी दस्तावेज़ में वॉटरमार्क के साथ JSON को PSD में भी बदल सकते हैं। वॉटरमार्क जोड़ने के लिए, आप पहले अपने JSON दस्तावेज़ को JPEG में रेंडर कर सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। ऑपरेशन को प्रदर्शित करने के लिए, आप अपनी परिवर्तित JPEG छवि को लोड कर सकते हैं, मैट्रिक्स क्लास के ऑब्जेक्ट का उपयोग करके ट्रांसफ़ॉर्मेशन जोड़ सकते हैं और [ग्राफ़िक्स](https://apireference.aspose.com/imaging/) का उपयोग करके छवि की सतह पर वॉटरमार्क के रूप में एक स्ट्रिंग बना सकते हैं। net/aspose.imaging/graphics) class' [DrawString](https://apireference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) विधि। इसमें वॉटरमार्क डालने के बाद आप JPEG को PSD फॉर्मेट में सेव कर सकते हैं। नीचे एक कोड उदाहरण दिया गया है जो दर्शाता है कि आपके दस्तावेज़ में एक विकर्ण वॉटरमार्क कैसे जोड़ा जाए। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-wmz/" name="JSON सेवा WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-dicom/" name="JSON सेवा DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-psd/" name="JSON सेवा PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-jpeg2000/" name="JSON सेवा JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-tga/" name="JSON सेवा TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-emz/" name="JSON सेवा EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-svgz/" name="JSON सेवा SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-wmf/" name="JSON सेवा WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-image/" name="JSON सेवा IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/json-to-dxf/" name="JSON सेवा DXF" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}