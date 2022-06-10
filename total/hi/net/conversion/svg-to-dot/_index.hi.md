---
title: सी # एपीआई सीजीएम को डीओसीएम में निर्यात करने के लिए
description: Microsoft Word का उपयोग किए बिना SVG को DOT में बदलें
url_ignore: /hi/net/conversion/svg-to-dot/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: DOT
otherformats: RTF PS WORDML FLATOPC DOTX PCL MARKDOWN DOTM XAMLFLOW ODT OTT MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET . के माध्यम से डीओसीएम को सीजीएम प्रस्तुत करना" h2="माइक्रोसॉफ्ट वर्ड का उपयोग किए बिना विंडोज़, मैकोज़ और लिनक्स पर सीजीएम को डीओसीएम में निर्यात करने के लिए नेट एपीआई" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) आपके .NET एप्लिकेशन के अंदर दस्तावेज़ हेरफेर और रूपांतरण सुविधाओं को जोड़ने के लिए एक शक्तिशाली एपीआई है। उन्नत PDF संसाधन API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) का उपयोग करके, आप SVG फ़ाइल स्वरूप को DOC में बदल सकते हैं। उसके बाद, शक्तिशाली दस्तावेज़ प्रसंस्करण API [Aspose.Words for .NET](https://products.aspose.com/words/net/) का उपयोग करके, आप DOT को DOC प्रस्तुत कर सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी # एपीआई सीजीएम को डीओसीएम में कनवर्ट करने के लिए" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) पद्धति का उपयोग करके SVG को Doc में बदलें
3. Aspose.Words के [Document](https://reference.aspose.com/words/net/aspose.words/document) वर्ग का उपयोग करके दस्तावेज़ फ़ाइल लोड करें
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) विधि का उपयोग करके दस्तावेज़ को DOT प्रारूप में सहेजें और Dot को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ```Install-Package Aspose.Total``` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.svg");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dot", SaveFormat.Dot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET के माध्यम से ओनर पासवर्ड का उपयोग करके सीजीएम फ़ाइल को डिक्रिप्ट करें" %}}
SVG को DOT में बदलने से पहले, यदि आप अपने दस्तावेज़ को डिक्रिप्ट करना चाहते हैं तो आप इसे API का उपयोग करके कर सकते हैं। पीडीएफ फाइल को डिक्रिप्ट करने के लिए, आपको पहले एक [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) ऑब्जेक्ट बनाना होगा और मालिक के पासवर्ड का उपयोग करके सीजीएम खोलना होगा। उसके बाद, आपको दस्तावेज़ ऑब्जेक्ट की [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) विधि को कॉल करने की आवश्यकता है। अंत में, दस्तावेज़ ऑब्जेक्ट की सहेजें विधि का उपयोग करके अद्यतन फ़ाइल को सहेजें।  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.svg", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="केवल पढ़ने के लिए DOT बनाएं- .NET के माध्यम से फ़ाइल करें" %}}
अपने DOT को संपादन से बचाने के लिए और अन्य लोगों को अपने दस्तावेज़ में संवेदनशील और गोपनीय जानकारी को संपादित करने से रोकने के लिए, आप API का उपयोग करके दस्तावेज़ की सुरक्षा भी सेट कर सकते हैं। आप किसी दस्तावेज़ को संपादित करने की क्षमता को सीमित कर सकते हैं और इसके साथ केवल कुछ क्रियाओं की अनुमति दे सकते हैं। यह [Aspose.Words for .NET](https://products.aspose.com/words/net/) API का उपयोग करके किया जा सकता है। यह आपको [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) एन्यूमरेशन पैरामीटर का उपयोग करके सामग्री को प्रतिबंधित करने के तरीके को नियंत्रित करने में सक्षम बनाता है। आप कोड की निम्नलिखित पंक्तियों का उपयोग करके अपने दस्तावेज़ को केवल-पढ़ने के लिए सेट कर सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-ott/" name="SVG सेवा OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-mhtml/" name="SVG सेवा MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-wordml/" name="SVG सेवा WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-dot/" name="SVG सेवा DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-odt/" name="SVG सेवा ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-rtf/" name="SVG सेवा RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-ps/" name="SVG सेवा PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-flatopc/" name="SVG सेवा FLAसेवाPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-pcl/" name="SVG सेवा PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-markdown/" name="SVG सेवा MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-xamlflow/" name="SVG सेवा XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-dotx/" name="SVG सेवा DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}