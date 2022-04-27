---
title: सी # एपीआई के माध्यम से सीजीएम को ओडीपी में निर्यात करें
description: Microsoft Word का उपयोग किए बिना EPUB को ODP में बदलने के लिए .NET API
url: /hi/net/conversion/epub-to-odp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: ODP
otherformats: POTM OTP POWERPOINT POTX POT PPS XAML PPSX PPTM PPT PPSM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET . के माध्यम से ओडीपी को सीजीएम प्रस्तुत करना" h2=".NET API Microsoft<sup>&reg;</sup> PowerPoint का उपयोग किए बिना Windows, macOS और Linux पर ODP को EPUB निर्यात करने के लिए" >}}

{{% blocks/products/pf/feature-page-summary %}}
शक्तिशाली फ़ाइल फ़ॉर्मेट ऑटोमेशन APIs [Aspose.Total for .NET](https://products.aspose.com/total/net/) के पैकेज का उपयोग करके आप आसानी से दो सरल चरणों में EPUB को ODP को प्रस्तुत कर सकते हैं। PDF संसाधन API [.NET के लिए Aspose.PDF](https://products.aspose.com/pdf/net/) का उपयोग करके, आप EPUB फ़ाइल स्वरूप को PPTX में बदल सकते हैं। उसके बाद, प्रेजेंटेशन प्रोसेसिंग एपीआई [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) का उपयोग करके, आप PPTX को ODP में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EPUB को ODP में बदलने के लिए .NET API" %}}
1. [दस्तावेज़](https://apireference.aspose.com/pdf/net/aspose.pdf/document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) पद्धति का उपयोग करके EPUB को PPTX में बदलें
3. [प्रस्तुति](https://apireference.aspose.com/slides/net/aspose.slides/presentation) वर्ग का उपयोग करके PPTX फ़ाइल लोड करें
4. [Save](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) विधि का उपयोग करके दस्तावेज़ को ODP प्रारूप में सहेजें और `Odp` को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ````Install-Package Aspose.Total`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.epub");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.odp", SaveFormat.Odp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="सीजीएम फ़ाइल से .NET . के माध्यम से एक्सएमपी मेटाडेटा प्राप्त करें" %}}
EPUB को ODP में कनवर्ट करते समय, आपको अपनी बैच रूपांतरण प्रक्रिया को प्राथमिकता देने के लिए अतिरिक्त XMP मेटाडेटा जानकारी की आवश्यकता हो सकती है। उदाहरण के लिए आप निर्माण तिथि के आधार पर अपने रूपांतरण दस्तावेजों को प्राप्त और क्रमबद्ध कर सकते हैं और तदनुसार दस्तावेजों को संसाधित कर सकते हैं। [.NET के लिए Aspose.PDF](https://products.aspose.com/pdf/net/) आपको EPUB फ़ाइल के XMP मेटाडेटा तक पहुंचने की अनुमति देता है। EPUB फ़ाइल का मेटाडेटा प्राप्त करने के लिए, आप एक [दस्तावेज़](https://apireference.aspose.com/pdf/net/aspose.pdf/document) ऑब्जेक्ट बना सकते हैं और इनपुट EPUB फ़ाइल खोल सकते हैं। उसके बाद, आप [मेटाडेटा](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) प्रॉपर्टी का उपयोग करके फ़ाइल का मेटाडेटा प्राप्त कर सकते हैं।  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.epub");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET . के माध्यम से केवल पढ़ने के लिए ODP फ़ाइल बनाएँ" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API का उपयोग करके, आप अपने रूपांतरण एप्लिकेशन की सुविधाओं को और बेहतर बना सकते हैं। सुरक्षा बढ़ाने के लिए केवल पढ़ने के लिए अपनी आउटपुट फ़ाइल बनाना एक विशेषता हो सकती है। एपीआई आपको अपनी ओडीपी फ़ाइल को केवल-पढ़ने के लिए सेट करने की अनुमति देता है, जिसका अर्थ है कि उपयोगकर्ता (प्रस्तुति खोलने के बाद) केवल-पढ़ने की सिफारिश देखते हैं। 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.odp", SaveFormat.Odp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-pot/" name="EPUB सेवा POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-ppsx/" name="EPUB सेवा PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-swf/" name="EPUB सेवा SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-powerpoint/" name="EPUB सेवा POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-otp/" name="EPUB सेवा OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-potm/" name="EPUB सेवा POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-ppt/" name="EPUB सेवा PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-pps/" name="EPUB सेवा PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-potx/" name="EPUB सेवा POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-xaml/" name="EPUB सेवा XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-ppsm/" name="EPUB सेवा PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-pptm/" name="EPUB सेवा PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}