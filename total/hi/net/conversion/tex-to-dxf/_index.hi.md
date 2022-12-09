---
title: C# API के माध्यम से TEX को DXF में बदलें
description: किसी भी तृतीय पक्ष एप्लिकेशन का उपयोग किए बिना अपने .NET अनुप्रयोगों में TEX को DXF में निर्यात करें
url_ignore: /hi/net/conversion/tex-to-dxf/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: DXF
otherformats: IMAGE TGA WMF JPEG2000 SVGZ DXF  EMZ PSD WMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सी # के माध्यम से सीजीएम फ़ाइल को एपीएनजी में कनवर्ट करें" h2="Adobe<sup>&reg;</sup> Acrobat Reader या किसी अन्य तृतीय पक्ष एप्लिकेशन का उपयोग किए बिना .NET अनुप्रयोगों के भीतर DXF को TEX निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) का उपयोग करके आप दो आसान चरणों में किसी भी .NET अनुप्रयोगों के भीतर आसानी से TEX को DXF छवि में निर्यात कर सकते हैं। सबसे पहले, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) का उपयोग करके, आप JPEG को TEX निर्यात कर सकते हैं। उसके बाद, [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) इमेज प्रोसेसिंग API का उपयोग करके, आप JPEG को DXF में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सीजीएम फ़ाइल को .NET के माध्यम से एपीएनजी में कनवर्ट करें" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) क्लास ऑब्जेक्ट को इनिशियलाइज़ करें और [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) विधि
3. [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) क्लास का इस्तेमाल करके JPEG फ़ाइल लोड करें
4. [सेव](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) विधि का उपयोग करके दस्तावेज़ को DXF प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ```Install-Package Aspose.Total``` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="सी # के माध्यम से एक ही फाइल में सीजीएम फ़ाइल को एपीएनजी में कनवर्ट करें" %}}
एपीआई का उपयोग करके, आप सीजीएम फ़ाइल को एपीएनजी में एकल छवि फ़ाइल में भी परिवर्तित कर सकते हैं। सभी पृष्ठों को परिवर्तित करने के लिए, आप पहले अपने सीजीएम दस्तावेज़ को एक टीआईएफएफ फ़ाइल में प्रस्तुत कर सकते हैं और उसके बाद आप टीआईएफएफ फ़ाइल को एपीएनजी में निर्यात कर सकते हैं। आप [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) वर्ग का उपयोग करके इनपुट फ़ाइल खोल सकते हैं और रिज़ॉल्यूशन, टिफ़सेटिंग और टीआईएफएफ डिवाइस ऑब्जेक्ट बना सकते हैं। आप TiffDevice की [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) पद्धति का उपयोग करके एकल TIFF छवि प्राप्त कर सकते हैं apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) वर्ग। अंत में, आप [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) वर्ग का उपयोग करके TIFF फ़ाइल लोड कर सकते हैं
और इसे [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) मेथड का इस्तेमाल करके DXF फॉर्मेट में सेव करें।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सी # के माध्यम से सीजीएम फ़ाइल को एपीएनजी में कनवर्ट और घुमाएं" %}}
एपीआई का उपयोग करके, आप अपनी आवश्यकताओं के अनुसार आउटपुट एपीएनजी छवि को घुमा भी सकते हैं। Image.RotateFlip विधि का उपयोग छवि को 90/180/270-डिग्री तक घुमाने और छवि को क्षैतिज या लंबवत रूप से फ़्लिप करने के लिए किया जा सकता है। आप रोटेशन के प्रकार को निर्दिष्ट कर सकते हैं और छवि पर लागू करने के लिए फ्लिप कर सकते हैं। छवि को घुमाने और फ़्लिप करने के लिए आप [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) वर्ग द्वारा उजागर फ़ैक्टरी विधि का उपयोग करके परिवर्तित JPEG छवि को लोड कर सकते हैं और छवि को कॉल कर सकते हैं उपयुक्त [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) निर्दिष्ट करते हुए .RotateFlip विधि। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tex-to-emz/" name="TEX सेवा EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tex-to-tga/" name="TEX सेवा TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tex-to-jpeg2000/" name="TEX सेवा JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tex-to-image/" name="TEX सेवा IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tex-to-psd/" name="TEX सेवा PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tex-to-wmz/" name="TEX सेवा WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tex-to-svgz/" name="TEX सेवा SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tex-to/" name="TEX सेवा" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tex-to-wmf/" name="TEX सेवा WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tex-to-dxf/" name="TEX सेवा DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tex-to-dicom/" name="TEX सेवा DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}